### arch install uefi lvm luks xfce

#### pre-check configuration 

Charger le clavier français en tapant "loqdkeys fr"
```
loadkeys fr
```
Verifier boot mode
```
ls /sys/firmware/efi/efivars    (Si le répertoire existe, l'ordinateur supporte l'efi)
```

#### Connexion au réseau

Vérifier le nom du reseau et si celui-ci est up
```
ip addr show
```

vérifier la connexion internet
```
ping -c 2 google.com
```

Connexion au wifi
```
iwctl
```
affichage du prompt [IWD]#
```
[iwd]# device list
[iwd]# station device scan
[iwd]# station device get-networks
[iwd]# station device connect SSID
```


Mise a jour des paquets et installation de reflector
```
pacman -Syy 
pacman -S reflector
```

Mise a jour des miroirs,tri par https
```
reflector --verbose --country 'France' -l 12 -p https --sort rate --save /etc/pacman.d/mirrorlist
```
#### partionnement

Préparation du disque dur et destruction complète des données avec shred, cela peut prendre un peu de temps
```
fdisk -l
shred -v -n 1 /dev/sda
```
Outil de partionnement cgdisk, nouvelle table de partition GPT
```
cgdisk /dev/sda
```
* /dev/sda1 EFI SYSTEM 512MB hex code ef00
* /dev/sda2 LVM 100%FREE hex code 8e00

Création de LVM
```
pvcreate –-dataalignment 1M /dev/sda2
```
Création du volume groupe « vglvm »
```
vgcreate vglvm /dev/sda2
```
Création des volumes logiques /root swap /tmp /home
```
lvcreate -L 17GO -n root vglvm
lvcreate -L 4GO -n swap vglvm
lvcreate -L 4GO -n tmp vglvm
lvcreate -l 100%FREE -n home vglvm
```
Ce qui donne comme label de partition :
* dev/sda1 =boot EFI
* /dev/vglvm/root
* /dev/vglvm/swap
* /dev/vglvm/tmp
* /dev/vglvm/home

Il reste également possible de contrôler les volumes créés que cela soit avec les commandes `pvdisplay`
`vgdisplay` ou encore `fdisk -l`

#### Chiffrement avec dm-crypt et LUKS
```
cryptsetup luksFormat -c aes-xts-plain64 -s 512 -h sha512 /dev/vglvm/root
```
Ouverture du container
```
cryptsetup luksOpen /dev/vglvm/root root
```

#### Monter et formater les partitions
```
mkfs.ext4 /dev/mapper/root
mount /dev/mapper/root /mnt
dd if=/dev/zero of=/dev/sda1 bs=1M
mkfs.vfat -F32 /dev/sda1
mkdir /mnt/boot && mount /dev/sda1 /mnt/boot

```
Vérifier les partitions avec `lsblk -l`

#### Installation du système de base
```
pacstrap /mnt linux base base-devel pacman-contrib linux-firmware lvm2 cryptsetup dhcpcd vim nano git man-db man-pages openssh zip p7zip unzip tar htop rsync tmux bash-completion wget pciutils lshw syslog-ng reflector iwd intel-ucode 
```

#### Generation et édition du fichier de la table des partitions
```
genfstab -L -p /mnt >> /mnt/etc/fstab
nano /mnt/etc/fstab
```
```
/dev/mapper/root / ext4 defaults,noatime 0 1
/dev/sda2 /boot ext2 defaults,noatime 0 2
#/dev/mapper/home /home ext4 defaults,noatime 0 2
#/dev/mapper/tmp /tmp tmpfs nodev,nosuid 0 0
#/dev/mapper/swap none swap sw 0 0
```
#### Paramétrage du fichier crypttab
```
nano /etc/crypttab
# home /dev/vglvm/home /etc/luks-keys/home
# swap /dev/vglvm/swap /dev/urandom swap,cipher=aes-xts-
plain64:whirlpool,size=512,hash=sha512
# tmp /dev/vglvm/tmp /dev/urandom tmp,cipher=aes-xts-
plain64,size=256
```

#### Chrooter le nouvel environnement
```
arch-chroot /mnt /bin/bash
```
Mot de passe super-administrateur root
```
passwd
```
Nom de la machine
```
nano /etc/hostname
```
Configuration de local paramétrage des langues
```
nano /etc/locale.gen
en_US.UTF-8 UTF-8
fr_FR.UTF-8 UTF-8
```
Génération du fichier
```
locale-gen
```
Configuration des langues par defaut
```
nano /etc/locale.conf
LANG="fr_FR.UTF-8"
LC_COLLATE="fr_FR.UTF-8"
```
Exporter le langage actuel pour création dans initramfs
```
export LANG=fr_FR.UTF-8
```
Console, fonts, clavier azerty
```
nano /etc/vconsole.conf
KEYMAP=fr-pc
FONT=
FONT_MAP=
```
Configuration du fuseau horaire
```
ln -s /usr/share/zoneinfo/Europe/Paris /etc/localtime
```
Paramétrage de l'horloge
```
hwclock --systohc --utc
```
Édition du rc.conf script au démarrage
```
nano /etc/rc.conf
# Configuration file for initscripts
DAEMONS=(hwclock syslog-ng network)
```
Démarrage du service dhcpcd avec systemd (ethernet)
```
systemctl enable dhcpcd
```
Démarrage du service iwd avec systemd (wifi)
```
systemctl enable iwd
```
Démarrage du service SSH
```
systemctl enable sshd.service
```

#### Préparation de initramfs
```
nano /etc/mkinitcpio.conf
Modifier les « hooks » qui devront être appelé pour lancer le système
.............
HOOKS = " base udev autodetect modconf block keymap lvm2 encrypt filesystems
keyboard shutdown fsck"
```
Génération du fichier
```
mkinitcpio -p linux
```

#### Installation de GRUB
```
pacman -S grub efibootmgr
```
Création du répertoire efi
```
mkdir -p /boot/efi
mount -t vfat /dev/sda1 /boot/efi
mkdir -p /boot/efi/EFI
grub-install --target=x86_64-efi --efi-directory=/boot/efi --bootloader-id=GRUB
```
Mise à jour de la langue local du GRUB
```
cp /usr/share/locale/en\@quot/LC_MESSAGES/grub.mo /boot/grub/locale/en.mo
```
Modification du fichier de configuration grub, appel de la partition root chiffrée
```
nano /etc/default/grub
GRUB_CMDLINE_LINUX="cryptdevice=/dev/vglvm/root"
```
```
grub-mkconfig -o /boot/grub/grub.cfg
```
#### Quitter et redémarrer

```
exit
umount /mnt/boot && umount /mnt
reboot
```
Après redémarrage du système fraîchement installé, le mot de passe de déchiffrement de la partition root est
demandé une fois à l'écran du bootloader passé. Si un problème persiste, il est possible de débuguer en relançant
un liveUSB sous arch et d'ouvrir le container LUKS par la commande `cryptsetup luksOpen /dev/vglvm/root root`

#### Activation de la swap
```
mkswap /dev/vglvm/swap && swapon /dev/vglvm/swap
```

#### Chiffrement et activation de /home
Création d'un fichier avec une clé privée dans la partition root. Il est possible de changer le nom du dossier pour
faire de la sécurité par l'obscurité ( pensez à changer dans crypttab également)
```
mkdir -p m 700 /etc/luks-keys
dd if=/dev/random of=/etc/luks-keys/home bs=1 count=256
```
Creation du container LUKS pour /home, format en ext4
```
cryptsetup luksFormat -c aes-xts-plain64 -s 512 /dev/vglvm/home /etc/luks-keys/home
cryptsetup luksOpen –allow-discards -d /etc/luks-keys/home /dev/vglvm/home home
mkfs.ext4 /dev/mapper/home
```
Extra 5 % d'espace disque sur /home
```
tune2fs -m 0 /dev/mapper/home
```
Monter et formater /tmp
```
mkfs.ext4 /dev/vglvm/tmp && mount /dev/vglvm/tmp /tmp
```
Activation de la partition /home et swap dans crypttab puis activation des partitions dans fstab, enfin redémarrer le
système reboot. Vérifier que les volumes sont montés avec la commande `lsblk -f`

#### Post-installation

Pour synchroniser la base de donnée pacman, il suffit de lancer la commande
```
pacman -Syu
```
*Initialisation pacman keyring*

Pacman Keyring est un outil pour synchroniser les clés PGP qui sont signées entres les développeurs, un outil
pour faire confiance aux dépôts et paquets téléchargés.
```
pacman-key –init
```

#### Modifier la liste des mirroirs des dépôts
Ici nous allons rechercher les dépôts ou la vitesse de téléchargement est optimisées selon notre pays. Il y a par
défaut une douzaine de miroirs, pour les mises à jours importantes utilisant le maximum de la capacité de
téléchargement réduit considérablement le temps d'attente. Installation de reflector
```
pacman -S reflector
reflector --verbose --country 'France' -l 12 -p https --sort rate --save /etc/pacman.d/mirrorlist
```

**Ajout d'un utilisateur**
```
groupadd -r autologin
useradd -m -g users -G wheel,storage,power,docker,autologin,audio -s /bin/bash trivial
passwd trivial
```

**Sudo access** 
```
export EDITOR=vim
visudo
%wheel ALL=(ALL) NOPASSWD: ALL
```
Changer d'utilisateur
```
su trivial
```
Installation d'un AUR package manager yay (dans /home)
```
mkdir sources 
cd sources 
git clone https://aur.archlinux.org/yay.git 
cd yay 
makepkg -si 
```
**Configuration de l'audio**
```
sudo pacman -S alsa-utils pulseaudio pulseaudio-alsa
```
Test du son et sauvegarde de la configuration
```
speaker-test -c 2
alsactl store
```
**Installation driver graphique, clavier, touchpad, openGL**
```
xf86-video-intel mesa-libgl xf86-input-libinput
```

**Installation du serveur X.Org**
```
sudo pacman -S xorg-server xorg-xinit xorg-server-utils xorg-twm xorg-xclock
xterm
```
Modification de la configuration du clavier sous Xorg
```
nano /etc/X11/xorg.conf.d/10-evdev.conf
Section "InputClass"
  Identifier "evdev keyboard catchall"
  MatchIsKeyboard "on"
  MatchDevicePath "/dev/input/event*"
  Option "XkbLayout" "fr"
  Driver "evdev"
EndSection
```
Lancement du serveur X
```
startx
```
**Installation de fonts et police**
```
sudo yay -S ttf-dejavu ttf-ms-fonts ttf- google-fonts-git ttf-ubuntu-title
```
#### Codecs multimedia

Nous allons installer l’ensemble des greffons gstreamer qui est le framework utilisé par de nombreux environnements de bureau pour gérer le multimedia.
```
pacman -S gst-plugins-{base,good,bad,ugly} gst-libav
```

#### Installation environnement graphique XFCE

```
pacman -S xfce4 xfce4-goodies lightdm-gtk-greeter-settings pavucontrol gtk-xfce-engine
sudo systemctl enable lightdm
```
**Editer le fichier de configuration ligthdm**
```
sudo nano /etc/lightdm/lightdm.conf
edit a la ligne
greeter-session = lightdm-gtk-greeter
```
Configuration de xinitrc
```
echo "exec startxfce4" > ~/.xinitrc
```

**Configuration de network manager**
Pour que celui-ci fonctionne et ne soit pas en conflit il est nécessaire de désactiver dhcpcd, networkmanager
prendra le relais
```
sudo systemctl disable dhcpcd.service
sudo systemctl enable NetworkManager.service
```
*Reboot*