### arch install uefi lvm luks xfce

nota:  désactiver dans le bios le secure boot pour booter en USB.
Vérifier le démarrage UEFI.

#### pre-check configuration 

Charger le clavier français en tapant "loqdkeys fr"
```
loadkeys fr
```

Changer la police d'affichage
```
setfont Lat2-Terminus16
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
pvcreate –-dataalignment 4M /dev/sda2
```
Création du volume groupe « vglvm »
```
vgcreate vglvm /dev/sda2
```
Création des volumes logiques /root swap /tmp /home
```
lvcreate -L 30GO -n root vglvm
lvcreate -L 16GO -n swap vglvm
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
pacstrap /mnt linux base base-devel pacman-contrib linux-firmware sudo lvm2 cryptsetup dhcpcd vim nano git man-db man-pages openssh zip p7zip unzip tar htop rsync tmux bash-completion wget pciutils lshw syslog-ng reflector iwd
```

#### Generation et édition du fichier de la table des partitions
```
genfstab -L -p /mnt >> /mnt/etc/fstab
nano /mnt/etc/fstab
```
```
/dev/mapper/root / ext4 defaults,noatime 0 1
/dev/sda1 /boot vfat defaults,noatime 0 2
#/dev/mapper/home /home ext4 rw,noatime 0 2
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
Activation de l'heure & ntp

Assigne le fuseau horaire
```
timedatectl set-timezone Europe/Paris
```
Active la synchronisation par serveur NTP
```
timedatectl set-ntp true
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
HOOKS = " base udev autodetect keyboard keymap consolefont modconf block encrypt lvm2 resume filesystems fsck"
```
Génération du fichier
```
mkinitcpio -p linux
```

Microcode
```
pacman -S intel-ucode 
```

Execution périodique du TRIM
```
pacman -S hdparm util-linux
systemctl enable fstrim.timer
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
GRUB_CMDLINE_LINUX="cryptdevice=/dev/vglvm/root:root"
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
pacman-key --init
```

#### Modifier la liste des mirroirs des dépôts
Ici nous allons rechercher les dépôts ou la vitesse de téléchargement est optimisées selon notre pays. Il y a par
défaut une douzaine de miroirs, pour les mises à jours importantes utilisant le maximum de la capacité de
téléchargement réduit considérablement le temps d'attente. Installation de reflector
```
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
%wheel ALL=(ALL) ALL
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
sudo pacman -S xf86-video-intel mesa-libgl xf86-input-libinput
```

**Installation du serveur X.Org**
```
sudo pacman -S xorg-server xorg-xinit xorg-twm xorg-xclock
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
Reboot & Lancement du serveur X
```
startx
```
**Installation de fonts et police**
```
# pacman -S ttf-ms-fonts ttf-dejavu ttf-bitstream-vera adobe-source-han-sans-otc-fonts noto-fonts noto-fonts-emoji ttf-liberation ttf-droid tex-gyre-fonts

```
Pour basculer la methode d'entrée clavier en Pinyin il faut installer Fcitx

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
sudo pacman -S networkmanager network-manager-applet
sudo systemctl disable dhcpcd.service
sudo systemctl enable NetworkManager.service
sudo systemctl start NetworkManager.service
```
*Reboot*

On va changer le thème et les icones GTK par Numix en installant ces deux paquets:
```
yay -S numix-icon-theme-git numix-gtk-theme-git
```
Il y a plus qu'à sélectionner dans setting/apparences Numix.

Pour prendre des notes et les ranger dans un wiki, installer zim
```
sudo pacman -S zim
```
Installation du terminal Guake, qui s'utilise avec la touche F12. Je conseil de l'utiliser que le terminal par défaut pour son ergonomie.
```
sudo pacman -S guake
```
Pour que Guake démarre au démarrage de l'environnement XFCE:
```
cp /usr/share/applications/guake.desktop /etc/xdg/autostart/
```

Installation de synapse + configuration sur le raccourci superL
```
sudo pacman -S synapse
```

#### Navigateur internet

On va installer Chrome via le paquet pour linux chromium qui est la version open-source:
```
sudo pacman -S chromium
```
La liste des extensions utiles pour la navigation et les développeurs:

* AdBlock — le meilleur bloqueur de pubs. Bloquez les publicités et pop-ups sur YouTube, Facebook, Twitch et tous vos sites préférés.
* Disconnect. Make the web faster, more private, and more secure.
* IP Address and Domain Information. L'outil d'enquête en ligne ultime ! Voir les informations détaillées sur chaque adresse IP, le nom de domaine et le fournisseur.
* Zotero Connector, Save references to Zotero from your web browser

Activer l'option "Envoyer une demande "Interdire le suivi" pendant la navigation" dans paramètres des cookies et autres données des sites.

Pensez à changer le moteur de recherche par défaut par DuckDuckGo dans les paramètres

#### Application divers

Penser à installer:
* keepass
* gimp
* vlc
* filezilla
* inkscape
* qBittorrent
* weechat
* Cmus
* gcalculator
* baobab
* neovim
* Discord
* Veracrypt
```
sudo pacman -S keepass gimp vlc filezilla inkscape qbittorrent weechat cmus gcalculator baobab neovim discord veracrypt
```

Autres applications:


* Eclipse JAVA

OpenJDK
``` 
sudo pacman -S jdk-openjdk
```

```
yay -S eclipse-java
```

Developpeur application documentation

```
yay -S zeal
```

#### Installer un service de cloud

Vous trouverez plusieurs services de cloud gratuit tels que qcloud, Google drive, Dropbox. Nous allons installer MEGA qui est plus sécurisé ques les autres offres de cloud, le service de l'entrepreneur Kim Dotcom a évolué sur les principes d'anonymat et de vie privée sur les données qui sont stocké sur son serveur depuis l'affaire de megaupload.

Editer le fichier de configuration de pacman pour ajouter le repository officiel de MEGA
```
sudo nano /etc/pacman.conf
```
Ajoutez ces lignes:
```
###Repository oficial MEGA###
 
[DEB_Arch_Extra]
 
SigLevel = Optional TrustAll
 
Server = https://mega.nz/linux/MEGAsync/Arch_Extra/$arch
```
Mettre à jour pacman
```
sudo pacman -Sy
```
Installation du logiciel et de l'intégration avec Thunar
```
sudo pacman -S megasync thunar-megasync
```

#### Sécurisation du réseau

Que cela soit pour protéger sa vie privée et sa navigation sur internet il est nécessaire de protéger le réseau, vos activités sont monitoré par les gouvernements et le renseignement ainsi que les GAFAM, le FAI pour revendre les données de navigation, tel que la pub ciblée. De plus un hacker doit savoir être furtif pour ne pas être détecté dans ces activités et éffacer ces traces(logs, historiques). Nous allons ainsi mettre en place le chiffrement du DNS, un VPN et un pare-feu. Rappelez-vous que qu'en vous prenez la décision d'être dans la mentalité d'un hacker vous devenez un fantome tel que le titre le livre de Kevin Mitnick "Ghost in the wires".

* Utilisation de DNScrypt et unbound https://linoxide.com/install-dnscrypt-unbound-archlinux/
* Utilisation d'un VPN https://wiki.archlinux.org/title/ProtonVPN
* Configuration du firewall Gufw https://infomars.fr/forum/index.php?showtopic=6273

DNSCrypt is a protocol that encrypt and authenticate communications between a DNS client and a DNS resolver. Prevent from DNS spoofing or man in the middle-attack. DNSCrypt are available for most operating system, including Linux, Windows, MacOSX android and iOS. And in this tutorial I'm using archlinux with kernel 4.1.


```
sudo pacman -S dnscrypt-proxy
```

Modifier le fichier de configuration, decommenter le # de `server_names` et vider `listen_addresses`:
sudo nano /etc/dnscrypt-proxy/dnscrypt-proxy.toml
server_names = ['dnscrypt.pl']
listen_addresses = [ ]

sudo systemctl enable --now dnscrypt-proxy.socket
sudo systemctl start dnscrypt-proxy.socket

Resolv.conf is a file used by linux to configure Domain Name Server(DNS) resolver. it is just plain-text created by administrator, so you must edit by root privileges and make it immutable/no one can edit it.

Edit it with nano editor remove all and add :
```
$ nano /etc/resolv.conf
nameserver ::1
nameserver 127.0.0.1
options edns0 single-request-reopen
```
 and now make it immutable with "chattr" command because dhcpcd rewrite the file :
```
$ chattr +i /etc/resolv.conf
```
Note :

If you want to edit it again, make it writable with command "chattr -i /etc/resolv.conf".

Now yo need to restart the network :

```
$ sudo systemctl restart dhcpcd iwd
```

Vérifier que le fournisseur DNS pointe bien vers DNScrypt.pl sur ce site:
https://dnsleaktest.com/

**Configuration du par-feu**

- Activation du pare-feu :
```
sudo ufw enable
```
- Activation des logs (très utile pour la suite) :
```
sudo ufw logging on
```
- Rejet par défaut des connexions entrantes :
```
sudo ufw default deny incoming
```
- Autorisation des connexions sortantes :
```
sudo ufw default allow outgoing
```
- Recherchement des règles du pare-feu pour finir :
```
sudo ufw reload
```
Après évidemment il y a le risque de virus/vers/etc : si un vers ou un rootkit ou quoi que ce soit d'autre se retrouve par une manipulation dangereuse sur Ubuntu, il peut envoyer des infos sortantes sur Internet sans intervention  du pare-feu (car configuré comme tel dans ses règles)… Mais après on est sur GNU/Linux, on est censé être savoir éviter les manipulations à risque (n'installer que des logiciels depuis des dépôts, ne favoriser que les dépôts officiels ou de confiance, faire ses mises à jour, etc.)

MODE PARANO

Si cela ne suffit pas, interdisez toutes les connexions sortantes et configurer des règles pour chaque port pour en fonction des services tel que HTTP, HTTPS, FTP, IMAP, POP, SMTP, DNS, IRC, TORRENT, RESEAU LOCAL. Ajouter à cela chkrootkit pour détecter des rootkits et mettez en place un IDS(Système de détection d'intrusion) tel que Snort pour surveiller le réseau. Ces précautions ne sont pas productive pour un ordinateur personnel, mais est plutôt adapté pour les serveurs et administrateurs systèmes.

**Configurer un VPN**

Installer le metapackage sur AUR:
```
yay -S protonvpn
```
CLI (Command Line Interface)

Login:

```
protonvpn-cli login <your_protonmail>
```
Connect to the VPN:
```
protonvpn-cli connect
```

Pour créer un compte protonVPN: https://protonvpn.com/free-vpn/linux/

Pour voir le status de la connexion:
```
protonvpn-cli status
```
Vérifier que votre adresse IP pointe sur le VPN: https://www.whatismyip.com/fr/

#### Applications pour écrivains et chercheurs

Quelques applications pour gérer et écrire des documents sous différents formats, ne soyez pas passif sur internet et consommer des données, produisez du savoir libre et partager pour rendre service à la communauté.

* Ghostwriter, éditeur en markdown
* wkhtmltopdf, converti du html en pdf
* pandoc, conversion de documents en ligne de commande
* Libreoffice, incluant le correcteur orthographique et grammalecte
* Texmaker, éditeur au format Latex pour écrire des formules mathématiques, symboles, documents tels que des thèses ou des papiers de recherche scientifique.
* Zotero, outil de bibliographie, références, sources de recherche

```
sudo pacman -S ghostwriter wkhtmltopdf pandoc libreoffice-still libreoffice-still-fr hunspell hunspell-fr texmaker 
```
Et les applications sous AUR:
```
yay -S zotero libreoffice-extension-grammalecte-fr
```
#### Gérer l'impression

```
pacman -S cups hplip xsane foomatic-{db,db-ppds,db-gutenprint-ppds,db-nonfree,db-nonfreeppds} gutenprint
```

### Sauvegarde

Dès le départ penser à mettre en place une politique de sauvegarde de vos données, cela peut-être juste sur un disque dur externe ou d'automatiser cela à intervalle régulier. Pensée à acheter un serveur NAS dédié à la tâche chez Synology avec 2 disques en RAID ou chez QNAP. Configurer-le sur votre LAN pour avoir un espace de partage SAMBA puis monter-le dans votre explorateur de fichier sous XFCE c'est thunar. En cas de vol ou dégradation à votre domicile il est possible de sauvegarder vos données dans le cloud tel que AWS S3 sous Synology.

Installation du client SAMBA pour thunar
```
sudo pacman -S smbclient gvfs-smb
```

Redémarrer le PC pour prendre en compte la découverte du réseau local.

Ensuite rechercher votre serveur dans thunar en tapant:
```
smb://192.168.X.X
```
Pour cela modifier en fonction d'IP de votre serveur.

Pour mettre en place les sauvegardes, le plus simple est d'utiliser deja-dup qui est une interface graphique de duplicity. La sauvegarde est chiffré et incrémental sur une période d'une semaine. Il existe d'autre méthode de sauvegarde tel que avec Borg-backup ou bien rync.
```
sudo pacman -S deja-dup
```
La configuration est relativement simple ou il faut juste indiquer l'emplacement de la sauvegarde de votre serveur SAMBA.
