HACKER INDUSTRIE 

*Mise en recette informatique*

---

Par Anthony J.R Le Goff

**LICENSE**

Copyright (C)  2021  ANTHONY JR. LE GOFF.

    Vous avez la permission de copier, distribuer ou modifier ce document selon
    les termes de la licence GNU de documentation libre, dans sa version 1.3 ou
    dans toute version ultérieure publiée par la Free Software Foundation ;
    sans Section Invariante, sans Texte De Première De Couverture, et sans
    Texte De Quatrième De Couverture.  Une copie de cette licence est incluse
    dans la section intitulée "Licence GNU de documentation libre"


Contact email: legoff.ant[at]gmail.com pour toutes questions relatives au livre, suggestion et correction.

# O. Généralités
---

## 0.1 Historique

Pour commencer cette université il est nécessaire d'introduire en faisant l'historique des grandes théories de l'informatique, ce qui vous permettera d'approfondir le sujet et de situer dans l'ordre chronologique les dates marquantes de la discipline et ces acteurs, mais retenez surtout: [AL-KHWARIZMI](https://en.wikipedia.org/wiki/Al-Khwarizmi), [ADA LOVELACE](https://fr.wikipedia.org/wiki/Ada_Lovelace), [GEORGE BOOLE](https://fr.wikipedia.org/wiki/George_Boole), [ALAN TURING](https://fr.wikipedia.org/wiki/Alan_Turing), [JOHN VON NEUMANN](https://fr.wikipedia.org/wiki/John_von_Neumann) & [CLAUDE SHANNON](https://fr.wikipedia.org/wiki/Claude_Shannon)


### Traitement de l'information et automatisation

**-3000 - Le binaire & le Ying/Yang chinois**

**-1750 - Code d'HAMMOURABI**

Le roi de Babylone (Mésopotamie), nommé HAMMOURABI, a fait graver cette stèle. Celle-ci est composée d'un ensemble de sentences royales sous la forme :
```
SI {personne} ET {action} ALORS {sentence}
```

**-330   Logique**

Elle est définie par le philosophe grec ARISTOTE dans l'ouvrage de référence l'[Organon](https://www.cosmovisions.com/textOrganon.htm)

**820   Travaux du mathématicien musulman AL KHWARIZMI**

L'algorithme dans un livre intitulé كتاب الجام والتبارك بحسب الهند “Kitab Al-Jam wal-tafriq bi hisab al-hind” dont – à cause du livre brûlé pendant l’invasion mongole – il ne reste qu’une traduction latine, à savoir; «Algoritmi de numero indorum».

**1000   Zéro**

Inventé en Inde et rapporté en Occident par les invasions arabes islamiques, le zéro trouvera un ardent défenseur en la personne de Gerbert d'AURILLAC qui tentera de l'imposer lorsqu'il deviendra le pape Sylvestre II. Mais, ce n'est que vers le XIVème siècle, que le monde occidental l'acceptera définitivement.

**1614   Logarithmes par John NEPER**

Grâce aux travaux de l'écossais NEPER, la multiplication et la division peuvent être ramenées à deux opérations très simples: l'addition et la soustraction.

**1697   Introduction du binaire en Europe par Gottfried LEIBNITZ**

Passionné par la Dyadique, LEIBNITZ fut conforté dans ses idées lorsqu'il apprit que le binaire avait été inventé par les Chinois plusieurs millénaires auparavant. Il exposera devant l'Académie des Sciences de Paris ses idées qui seront publiées dans "Explication de l'arithmétique binaire avec des remarques sur son utilité et sur le sens qu'elle donne des anciennes figures chinoises de Fou-Hi".

**1840   Principe des machines à calculer par Augusta LOVELACE**

Pour elle, une machine à calculer doit comporter :
```
   * Un dispositif permettant d'introduire les données numériques (cartes perforées, roues dentées...)

   * Une mémoire pour conserver les valeurs numériques entrées

   * Une unité de commande grâce à laquelle l'utilisateur va indiquer à la machine les tâches à effectuer

   * Un "moulin" chargé d'effectuer les calculs

   * Un dispositif permettant de prendre connaissance des résultats (imprimante...)
```
Ces principes seront, un siècle plus tard, à la base des premiers ordinateurs.

**1843   Théorie de la programmation par Ada LOVELACE**

Ici, elle définit le principe d'itérations successives dans l'exécution d'une opération. En l'honneur du mathématicien arabe AL KHWARIZMI, elle appelle "algorithme" le processus logique permettant l'exécution d'un programme.

**1854   Théorie de la logique binaire de George BOOLE**

Dans "Les lois de la pensée", il explique que l'on peut coder les démarches de la pensée à l'aide de système n'ayant que deux états: ZERO-UN; OUI-NON; VRAI-FAUX...

### L'ère de l'électronique

**1914   Principes de l'automatisme par TORRES QUEVEDO**

Il décrit tout ce qui est nécessaire pour faire fonctionner un automate dans "Essai sur l'Automatisme" :
```
   * des sens (thermomètres, boussoles, dynamomètres...)

   * des membres

   * une énergie (électricité, eau, air...)

   * une faculté de discernement

```

**1936   Définition de la notion d'Algorithme par Alan TURING**

Pour cela, il a décrit une machine (virtuelle) capable de résoudre tout problème pouvant être mis sous forme d'algorithme..

**1940   Système de calcul en Virgule flottante (floating-point)**

Mise au point séparément par George STIBITZ (aux USA) et Konrad ZUSE (en Allemagne), cette notion fait appel aux puissances de 10. Les grands nombres sont exprimés à l'aide d'une "mantisse" et d'un exposant. Exemple : 252 000=2,52 x 105. On a donc un gain de place en mémoire et des multiplications plus faciles à effectuer. Le Z3 est le premier calculateur à utiliser ce système avec succès.

**1943   "Énoncé des ordinateurs" par Alan TURING**

**1945 Architecture Von Neumann**

L'architecture générale des ordinateurs a été développée dans le cadre d'un projet EDVAC par John Von Neumann (et d'autres scientifiques de l'époque), mathématicien et physicien américano-hongrois en 1945. Ce modèle propose une structure dans laquelle le programme est stocké dans la mémoire de la machine.

**1945   Hypertexte par Vannevar BUSH**

Dans son système memex, il proposait des documents, des textes, des notes personnelles de façon à les retrouver facilement. Cette idée sera reprise par Douglas ENGELBART en 1963 puis par Ted NELSON (en 1975) qui lui donne le nom d'hypertexte.

**1948   "Théorie mathématique de l'information" par Claude SHANNON**

Issu de ses travaux pour sa thèse, ce mémoire décrit l'application de la théorie de BOOLE. Dans cet ouvrage, SHANNON introduit un terme nouveau : " le bit " (contraction de Binary digIT) qui fournit une mesure de la quantité d'information.

**1952 - Premier compilateur**

Grace Hopper a terminé son premier compilateur (pour ordinateur Sperry-Rand), connu sous le nom de système A-0.

**1958 - LISP & l'intelligence artificielle**

John Mc Carthy développe le langage de programmation Lisp qui devient le langage de programmation le plus populaire utilisé dans la recherche sur l’intelligence artificielle.

**1968 - 2001:L'odysée de l'espace**

Le film 2001 : Odyssée de l’espace sort, mettant en scène Hal, un ordinateur doué de sensibilité.

**1970 - Création du système d'exploitation UNIX**

Unix, officiellement UNIX, est une famille de systèmes d'exploitation multitâche et multi-utilisateur dérivé du Unix d'origine créé par AT&T, le développement de ce dernier ayant commencé dans les années 1970 au centre de recherche de Bell Labs mené par Kenneth Thompson

**1989 - La naissance du web**

Tim Berners-Lee, chercheur britannique, a inventé le Web au CERN. À l'origine, le projet, baptisé « World Wide Web », a été conçu et développé pour que des scientifiques travaillant dans des universités et instituts du monde entier puissent s'échanger des informations instantanément.

**1991   Unicode**

Afin de résoudre une fois pour toute les problèmes de codage de caractères et de ses différents jeux (ex: ISO 8859-1/Latin 1 etc...) incompatibles, l'Unicode a été créé pour être un sur-ensemble de tous les autres. Il est capable, en théorie, de supporter tous les langages existants (et disparus) avec leurs particularités. Il existe plusieurs formats de représentation : UTF-8 est de plus en plus utilisé pour les transmissions de documents (par exemple cette page web) et sur les serveurs UNIX. Il a l'inconvénient d'avoir une longeur par caractère qui est variable (1 caractère = 1,2,3 ou 4 octets) mais il a l'avantage d'être très compact pour l'alphabet occidental non accentué et n'a pas le problème d'ordre des octets comme UTF-16 (utilisé par Windows). Si la première version de la norme a été publiée en 1991, sa complexité rend son adoption très lente.

**1998   Logiciel Libre**

D'après les statuts de l'AFUL, sont considérés comme libres les logiciels disponibles sous forme de code source, librement redistribuables et modifiables, selon des termes proches des licences «GPL», «Berkeley» ou «artistique» et plus généralement des recommandations du groupe «Open Source». Les bases de ce mode de distribution ont été jetées par Richard Stallman, créateur de la FSF et du projet GNU. Depuis quelques temps, l'idée de logiciel libre se répend rapidement (un des plus connu étant Linux) comme alternative aux solutions propriétaires traditionnelles.

* Association Francophone des Utilisateurs de Logiciels Libres: [https://aful.org/](https://aful.org/)
* Free Software Foundation: [https://www.fsf.org/](https://www.fsf.org/)
* Open Source: [https://opensource.org/](https://opensource.org/)
* GNU: [https://www.gnu.org/home.fr.html](https://www.gnu.org/home.fr.html)

## 0.2 Préambule libriste

Il m'était impossible de ne pas introduire l'objet de l'étude de l'informatique par un mouvement de fond tel que le logiciel libre. Steve Ballmer(ex PDG Microsoft) disait du logiciel libre que c'était un cancer pour la propriété intellectuelle. Ce que l'on entend par propriété intellectuelle est le brevet pour une invention. Ce qui permet de rémunérer les inventeurs et d'accéder à la paternité d'une nouvelle idée mise en concept à bus de faire du profit commercial.C'est donc une manière d'éviter de ce faire copier et donc voler son travail. Personne n'aime le plagiat, qui représente un travail médiocre en qualité. Dans ce sens l'arrivée des logiciels informatiques allaient remettre en cause les pratiques dominantes sur les oeuvres de l'esprit. En particulier l'étude et la redistribution du code source. Un logiciel disposant du code source peut-être copié à l'infini ne vous dépouillant pas de votre travail ayant vous même une copie du code source. L'étude du code source permet donc d'améliorer les fonctionnalités et d'en faire des dérivées *fork*, de l'adapter sur plusieurs matériels mais également d'en faire un travail d'audit de recherche de faille de sécurité qui pourrait compromettre son utilisation. Ces quelques principes sur une économie du partage n'est pas venu instinctivement car des pratiques pour s'enrichir sur le dos du modèle capitaliste vont apparaitre fin des années 70. Le code ouvert en particulier par l'utilisation des universitaires se fermera par l'arrivée commerciale pour le grand public du micro-ordinateur dont le système d'exploitation DOS. Quelques projets vont rentrer en résistance dont le projet GNU de Richard Stallman en mémoire de l'esprit hacker des premiers jours pour faire un dérivée de système d'exploitation UNIX qui serait libre. On peu dire que Richard Stallman est le premier libriste en définissant le logiciel libre. Une véritable [bataille du libre](https://www.labatailledulibre.org/) va donc commencer marquant l'histoire de l'informatique.

Dans ce cadre, la volonté de la communauté est avant tout chose de résoudre un problème technique que de répondre à une offre marchande et donc la protection par un brevet contre la concurrence. Pourtant il est nécessaire de considérer la paternité d'une innovation technologique en informatique et de prendre en compte les auteurs. Ce que va définir Richard Stallman dans son projet GNU est une license d'utilisation. Les libristes donc se définissent comme des enfants du projet GNU et la définition des quatres libertés fondammentales tel que:

* la liberté d'exécuter le programme, pour tous les usages ;
* la liberté d'étudier le fonctionnement du programme et de l'adapter à ses besoins ;
* la liberté de redistribuer des copies du programme (ce qui implique la possibilité aussi bien de donner que de vendre des copies) ;
* la liberté d'améliorer le programme et de distribuer ces améliorations au public, pour en faire profiter toute la communauté.

Ainsi la nécessité d'accès au code source est une condition de ces libertés. Et après tout quand on y réfléchis bien n'est ce pas pareil en biologie? Un être humain à la liberté d'être copié et de ce reproduire et son programme codé dans l'ADN est disponible. Aujourd'hui en génétique on peut modifier cet ADN pour l'améliorer ou réparer des caractéristiques. On peut penser au processus d'amélioration continue et de mutation d'un logiciel comme l'évolution du vivant. Avec des branches dans l'origine d'un arbre d'une espèce. Ainsi un logiciel pour le traitement de texte est une famille qui demande d'être adapté à un environnement de travail qui évolue et donc mise à jour dans le temps en ajoutant des caractéristiques. Certaines personnes vont ajouter des fonctionnalités exclusives pour en tirer parti d'un point de vue commerciale. Tel est le constat caché le code source complique le processus d'innovation car on restreint la distribution à quelques acteurs et donc on élève des privilèges. Cela me rappel des affaires tel que Coca-Cola qui garda jalousement secrète sa recette et donc garder un monopole. Hors c'est bien la lutte contre les monopoles dont il est question dans le logiciel libre. C'est une stratégie qui est contre-productive car sur du long terme vous ne pouvez pas empêcher la recherche, également cela engendre dans le principe de concurrence une mise en place d'espionnage pour découvrir les secrets de fabrication et de production. Si on veut réduire la malveillance un secret doit être partagé. On retrouve dans d'autres domaines des exemples de raté, tel que la fabrication de la bombe atomique. les USA n'ont jamais gardé le monopole, au contraire cela n'a fait qu'accélérer une course à l'armement. La question de la propriété intellectuelle n'est pas vite répondu, la découverte d'une solution technique engendre un phénomène d'adoption rapide à partir du moment qu'il répond à un besoin. Dans le cadre de la bombe atomique, c'est la question de puissance qui est remis en cause et donc l'impact politique. Mais cela peut-être un impact sur la création tel que des logiciels de CAO(conception assisté par ordinateur). Doit-on restreindre la possibilité de création à l'industrie et quelques licences universitaires? Comment fait-on pour que l'étudiant ce forme si celui-ci ne peut qu'utiliser les ordinateurs à l'université? Et si on donne un travail personnel à faire chez soi? Que de contrainte. Au-delà de ça c'est croire une utopie de civilisation que la recherche de solution technique ne se fait qu'à l'industrie dans le cadre d'un travail rémunérer. Hors, l'histoire des découvertes de ce monde en science est une affaire de passionné et pas seulement qu'en laboratoire. C'est ce que démontre le logiciel libre par le bénévolat et hors temps de travail, on peut produire une solution technique. Il pourrait être question de développement durable et d'accès à la technologie pour des pays en voie de développement. Pour accèder à ces marchés le coût pour se fournir en matériel informatique est bien trop élevé. Donc on regarde des solutions alternatives parfois gratuite pour remplacer les industriels et logiciels privateurs. La circulation de l'information doit être accélérée en tout point du globe et définir les bonnes pratiques pour que chacun puisse avoir accès aux outils de création, de production en particulier d'oeuvre de l'esprit et donc intellectuel.

C'est sous cette nécessité que ce livre se construit. Par adhésion au mouvement de la culture libre initié par des informaticiens pour aller plus loin que l'idéologie, c'est un projet de société et de civilisation et la croyance en une futur [économie de l'abondance](https://www.cairn.info/revue-hermes-la-revue-2006-2-page-51.htm) dont le logiciel libre est la première brique qui déposa un standard sur l'utilisation de ressource illimité. Elle doit être tout d'abord développé dans un paradigme de la pensée et de l'immatériel dont la révolution informatique à propager l'économie de la connaissance actuelle, vers la possibilité pour l'humanité d'élargir les horizons vers l'espace et le minage d'astéroide et de exoplanète permettant l'utilisation de la ressource matériel illimité réduisant les conflits sur les problèmatiques de rareté. Il faut être clair pour tout programme spatial, c'est tout d'abord du calcul de trajectoire de projectile que l'informatique nous permet et la production d'un capital immateriel pour développer un produit avec succès. Le logiciel libre est le cheval de Troie de l'ouverture vers l'espace car c'est un univers fait de robotique terrain de jeu de la cybernétique.Aujourd'hui du logiciel libre est embarqué dans les fusées SpaceX ou sur le rover Persévérance sur Mars. Le succès du logiciel libre à travers la FSF(Free-software foundation) a permis de voir des projets tel que:

* Linux (noyau de système d'exploitation)
* Apache (serveur web)
* Mozilla Firefox (navigateur internet)
* Gimp (logiciel de dessin)
* Git (outil de contôle de version)
* Perl (langage de programmation)

Largement adopté par les industriels de nos jours par les pratiques des développeurs car répondant une solution technique et un réel besoin. 99% top 1 million des websites fonctionnent sur un serveur GNU/Linux et 100% des top 500 supercalculateurs mondiaux ont adopté GNU/Linux. Il y a une véritable suprématie des logiciels libres quand il est question de performance et de réduire les coûts de fonctionnement. On peut également noté que les scientifiques du CERN tournent sous GNU/Linux et sont très actif dans le développement par la propagation de la [science ouverte](https://www.science-ouverte.cnrs.fr/le-mouvement-pour-la-science-ouverte/). Le logiciel libre est moteur dans la mise en oeuvre de pratique développé par l'économie du partage qui réduit de plus en plus la portée des documents classifiés chez les industriels dans une optique de collaboration entre des parties prenantes pour chasser en meute.

## 0.3 L'héritage d'Unix

Revenons un peu sur la genèse du projet GNU, j'expliquai que ce livre est de vous permettre d'apprendre l'informatique et d'acquérir des libertés numériques. Nous allons donc faire une étude de cas à travers une distribution GNU/Linux. Il faudra donc connaitre GNU et Linux. Comme j'en parlais le projet GNU est une ré-écriture complète d'UNIX. UNIX est un système d'exploitation pour ordinateur, c'est à dire que c'est un logiciel qui permet la communication entre le matériel(hardware) physique tel que le clavier, l'écran, la souris, le processeur, etc... et des applications comme votre navigateur internet. GNU est une série de programmes, librairies et compilateurs pour l'utilisateur: c'est à dire un environnement complet de travail pour le développeur pour créer des logiciels. Vous trouverez à la page [GNU du wiki arch linux](https://wiki.archlinux.org/title/GNU) la liste complète de projet GNU de nos jours. Au commencement, en 1985, on retrouvait en particulier:

* Bash, un shell pour écrire des lignes de commande
* glibc, *GNU C Librairy* Implémentation de la librairie standard en C
* Emacs, un éditeur de texte
* gcc, GNU Compiler Collection est un logiciel de compilation en C

UNIX a été écrit en langage C. Les systèmes d'exploitation sont écrit dans ce langage, il était donc nécessaire de créer un compilateur pour faire des fichiers binaires éxecutables. Le compilateur transforme du code que peut lire et écrire l'humain en langage C vers du code machine binaire à base de 0,1 des bits que peu lire le processeur et exécuter. Pour écrire du code, on utilise un éditeur de texte. Sous UNIX, l'éditeur est Vi. Il existe une petite guerre de religion entre les puristes qui utilisent Emacs et Vi puis son héritier Vim. Mais cela vous aller le découvrir. On utilise un shell pour lancer un programme tel que Vi en ligne de commande pour éditer un fichier en langage C puis on compile toujours en ligne de commande avec gcc. Quand à glibc est une bibliothèque C qui apporte les appels système et les fonctions de base telles que open, malloc, printf, etc. Si vous cherchez à étudier la programmation système il vous faudra connaître ces notions, mais pour l'instant ce n'est que pour la culture.

## 0.4 Matériel

Nous allons parler un peu du materiel pour faire tourner GNU/Linux et surtout les laptops. j'aurai tendance à privilégier le materiel libre pour faire tourner du GNU/Linux que cela soit sur la politique de Licence. Ainsi préféré quand c'est possible du matériel sous RISC-V comme architecture de processeur open source.

Vous trouverez une [liste des projets](https://en.wikipedia.org/wiki/List_of_open-source_hardware_projects) sous matériel libre et vous pouvez aller sur le [site officiel oshwa](https://www.oshwa.org/). Si vous ne savez pas par ou commencer regarder du côté de Raspberry Pi sous processeur ARM, mais également MangoPi MQ Pro sous RISC-V. De plus pour avoir un nano-ordinateur performant de bureau je conseil la société SipeedIO avec le [LicheePi 4A](https://sipeed.com/licheepi4a).

En ce qui concerne les laptops. Utiliser des entreprises qui sont spécialisés dans le materiel sous GNU/Linux et qu'il l'utilise comme outil de travail comme les "Lenovo Thinkpad". Ils ont très bonne réputation et cela ce trouve à très bon prix en reconditionné sur [BackMarket](https://www.backmarket.fr/fr-fr/search?q=thinkpad#keyboard_type_language=AZERTY%20-%20Fran%C3%A7ais&price=0&price=450). jetez un oeil, on trouve de bon PC pour un prix moyen de 368€ pour les débutants en informatique.

Pour du haut de gamme et sur mesure, vous pouvez toujours achetez en neuf chez Lenovo à minimum 800€. D'autres marques ont des laptops haut de gamme tel que [Starlabs Starbook](https://fr.starlabs.systems/products/starbook?variant=43968785678590) en clavier AZERTY français.

## 0.5 Eco-système

On l'aura vue, depuis la genèse du projet GNU de Richard Stallman, un éco-système va ce mettre en place avec des programmeurs autour du logiciel libre qui donnera naissance à Linux. Tout d'abord la FSF ou free-software foundation. On va retrouver le premier système d'exploitation sous GNU/Linux et la communauté Debian, puis viendra la première entreprise avec Red Hat puis la distribution Fedora. On compte maintenant plus de 600 distribution sous GNU/Linux dans le monde avec des partisans et militants du logiciel libre. En France la promotion et la défense du logiciel libre est réalisé par l'[April](https://april.org/), mais aussi par l' association Framasoft qui publie des documents et ressources et également Linuxfr.org qui est le principal site communautaire. En 2021 la documentation la plus accessible est celle de la distribution Ubuntu pour s'initier à la communauté ainsi que le wiki Arch Linux sur internet. A noter que Wikipédia, l'encyclopédie libre est une réussite du mouvement, autant apprécié des internautes curieux de connaissance que des thésards comme source d'information. Les idées reçuent comme quoi on ne peu pas faire confiance à une source d'information que n'importe qui peu éditer et contribuer n'est plus d'actualité grâce au travail des wikipédiens. Concernant les infrastructures critiques financières, la bourse de New-York à migré vers des solutions "Red Hat entreprise"en 2008. Du côté des militaires, au USA le "Department of Defense" de l'US Army utilise egalement Linux ainsi que pour la flotte de sous-marin nucléaire et le système de sonar.

Un autre mouvement va apparaitre en 1998 sous l'impulsion de Eric Raymond nommé l'OSI(Open source initiative) mettait plutôt l'accent sur le développement
technologique en permettant aux créateurs de se servir librement du travail
de leurs devanciers. L'open source sera particulièrement plus adapté pour les entreprises pour développer de la technologie alors que le logiciel libre sera plus un mouvement social selon Richard Stallman. Lawrence Lessig, le créateur de Creative Commons (CC) et du livre "culture libre" en 2005 fera la remarque que le copyright est un obstacle à la production culturelle, au partage de la connaissance, à l'innovation technologique et l'intérêt privée. Une autre ONG représente le paysage de la culture libre à l'échelle internationnale est l'[EFF(Electronic frontier foundation)](https://www.eff.org/fr). l'EFF contribue à la protection des droits et liberté sur internet. L'objectif essentiel de l'EFF est de défendre la liberté d'expression sur Internet, et plus largement la vie privée en ligne des utilisateurs. Pour accompagner ces derniers dans cette optique, EFF a notamment mis en place un guide spécialisé dans la protection contre l'espionnage en ligne, intitulé Autodéfense contre la surveillance.

L'autre éco-système est la "Linux fondation". C'est un organisme à but non-lucratif qui regroupe plus de 70 membres tels que AT&T, Google, AMD, Fujitsu, HP, Hitachi, Intel, IBM, LG Group, Microsoft, NEC, Novell, Oracle, Orange, Samsung, Twitter, Valve, Yahoo!, Tencent, Huawei, Valve, Qualcomm. La "Linux Foundation" a pour mission de protéger et standardiser Linux en procurant les ressources et services centralisés nécessaires à concurrencer de manière efficace les autres systèmes d'exploitation. Sur leur site on retrouve des services de formation et des certificats, si vous avez envie de devenir "kernel developer" par la suite. Linus Torvalds est employé par l'organisme et quelques autres principaux programmeurs tel que Greg Kroah-Hartman. A noter que le fondateur d'Ubuntu et CEO de l'entreprise Canonical Ltd: Mark Shuttleworth est dans les administrateurs de la "Linux Fondation".

D'un autre côté on retrouve les entreprises contributeurs du noyau Linux incluant: Intel (12.9%), Red Hat (8%), Linaro (4%), Samsung (3.9%), SUSE (3.2%), et IBM (2.7%). La question de qui approuve le code et donc les mainteneurs du noyau Linux est un peu différente avec des acteurs qui patchs appartenant à la "Linux fondation" et également de Google. Ce qui parait normal sachant que Google a lancé Android sur smartphone sous noyau Linux ou encore les fameux Chromebook à la base d'une GNU/Linux Gentoo. Red Hat a été racheté par IBM pour 34 milliards de dollars. On peu faire confiance à Lenovo qui avait racheté la branche ordinateur de l'entreprise IBM pour un portage du materiel Linux. Donc voir IBM contributeur du noyau Linux consolide le travail de compatibilité. Il faut noter que parmis les rares constructeurs d'ordinateurs, on trouve des solutions en natif sous GNU/Linux chez Lenovo serie Thinkpad et DELL serie XPS specialement pour développeur.

Si vous cherchez un peu plus sur internet on peu tomber sur des alliances d'entreprises autour de l'open source tel que TODO,OSPO. C'est un phénomène assez récent de la décennie et la part croissante d'utilisation de l'open source dans les entreprises de la Tech.

Les alliances d'entreprises du logiciel libre en France se regroupe autour du CNLL. On retrouve 300 entreprises appartenant à 11 Clusters régionaux incluant des start-ups, des éditeurs de logiciels ou des cabinets de conseil et ENL(Entreprise du numérique libre).

La communauté du libre forme des groupes autour de personnalité public qui son des influenceurs et leader d'opinion que cela soit pour leur activisme ou compétence technique reconnue. Citons quelques un qui ont fait l'actualité ou prenne régulièrement la parole:

* **Philippe Aigrain**, est un informaticien et chercheur qui a fait du militantisme autour de l'idée des biens communs et des abus de la propriété intellectuelle. Ses analyses sont notamment développées dans son livre *Cause commune: l'information entre bien commun et propriété*, qui base une réflexion sur le sujet. Il est aussi cofondateur de la quadrature du net.
* **Stéphane Bortzmeyer** est informaticien à l’Association française pour le nommage Internet en coopération (Afnic). Il s'occupe entre autres de sécurité, notamment du DNS. C'est un pionnier du chiffrement en France, et l'auteur du livre *"Cyberstructure : L'Internet : un espace politique"*.
* **Fréderic Couchet**, est un militant des libertés informatiques, conférencier à TEDx "Logiciel libre" et et co-producteur de l'émission radio "Libre à vous".
* **Laurent Chemla**, considéré comme premier cyberpirate de France est le fondateur du registar Gandi.net.
* **Fabrice Epelboin**, est un entrepreneur français, spécialiste des médias sociaux et du web social. Cofondateur du site OWNI. Il est professeur à sciencePo et enseigne la guerre informationnelle, les usages politiques des réseaux sociaux, la surveillance de masse et l'astroturfing.
* **Roberto Di Cosmo**, est un chercheur informaticien italien, installé en France, membre du laboratoire Preuves, Programmes et Systèmes de l'université Paris Diderot. Il est membre de l'AFUL, association francophone des utilisateurs de Linux et de logiciels libres. C'est un conférencier qui traite de sujet autour du logiciel libre. Il a été porteur du projet de pole de competitivité Ouverture en Ile-de-France plus tard rattaché au sein du pôle Systematic. Le 30 juin 2016, Inria a dévoilé Software Heritage, une initiative qui vise à préserver l'ensemble du code source disponible publiquement. Roberto Di Cosmo est l'un des architectes de cette bibliothèque ainsi que directeur du projet.
* **Olivier Laurelli** est un hacker, spécialiste de la cybersécurité alias "Bluetouff" fondateur du site reflets.info.
* **Jean-Marc Manach** est un journaliste d'investigation français, spécialiste d'Internet et des questions de surveillance et de vie privée.Coauteur avec Julien Goetz et Sylvain Bergère d'*Une contre-histoire de l'Internet*, documentaire et webdocumentaire donnant la parole à de nombreux défenseurs des libertés sur Internet. Il tient un blog bugbrother au journal "Le Monde" et à écrit plusieurs livres.
* **Jérémie Zimmermann** cofondateur et l'ex-porte-parole de la Quadrature du Net, une organisation de défense des droits et libertés des citoyens sur Internet.

Cela permet dejà d'avoir un aperçu francophone de la communauté du libre, passons à l'internationnal avec plusieurs personnalités qui ont d'ailleurs fait coulé de l'encre durant la décennie 2010.

* **Jacob Appelbaum**, militant, chercheur et développeur de Tor. Appelbaum, un chercheur en informatique à l’Université de Washington, est l’un des principaux membres du projet Tor, qui permet de garantir l’anonymat de milliers d’internautes à travers le monde. Appelbaum a attiré l’attention du public après avoir été arrêté et fouillé à de nombreuses reprises par des douaniers américains, qui lui ont confisqué son matériel électronique, après qu’il a défendu Julian Assange pendant une conférence.
*  **Julian Assange** rédacteur en chef de Wikileaks, il a publié des documents classifiés sur la guerre en Irak et en Afghanistan, il s'était réfugié à l'ambassade de l'Equateur à Londres ou il a été arrêté et depuis est en prison et accusé d'espionnage. C'est un leader du mouvement de l'internet libre et un interlocuteur important.
*  **John Perry Barlow** Co-fondateur, Electronic Frontier Foundation. Elle est en première ligne quand les libertés numériques sont menacées. L'ONG est active par du lobbying auprès des politiques. Les sujets comme la vie privée, la surveillance de masse sont traité régulièrement.
*  **Sir Tim Berners Lee** est l'inventeur du world wide web, il milite toujours dans les hautes sphères de gouvernement pour l'open data à travers le monde.
*  **Heather Brooke** est une journaliste et activiste qui milite pour la liberté d'information, elle a écrit un livre sur la culture hacker, le numérique et les lanceurs d'alerte: *The Revolution Will Be Digitised* en 2011 incluant une recherche sur Wikileaks.
*  **Rickard Falkvinge** est fondateur du partie pirate. Falkvinge a fondé le parti Pirate Suédois en 2006 afin de se concentrer sur la réforme des lois sur le droit d’auteur, les brevets et le partage de fichiers. Il est la troisième force politique en Allemagne.
*  **Aaron Swartz** est un activiste, programmeur à l'origine entre autre de Creative Commons, Reddit, mais également du langage Markdown. Partisan de la liberté d'accès à la connaissance scientifique et de la transparence politique, son combat créa un scandale dans l'affaire JTSOR et le téléchargement de plus de 4 millions publications scientifiques. Un procès était programmé avant son suicide en 2013. Un livre lui est dédié regroupant ces textes sous : *Celui qui pourrait changer le monde*.
*  **Edward Snowden** est un informaticien et lanceur d'alerte, ancien employé de la CIA. Il met au jour l'affaire de la NSA et la surveillance de masse avec les projets PRISM, Xkeyscore. Il défend l'utilisation de Tail pour l'annonymat et la vie privée. Il est exilé en Russie et a publié un livre: *Mémoire vive*.

## 0.6 Les hackers

Jusqu'ou peut-on remonter à la source des hackers? A vrai dire aux premiers programmeurs et théoriciens de l'informatique. Après la trace commence à disparaitre historiquement, ou du moins à moins marqué la sous-culture "underground" des hackers. L'une des premières sources d'inspiration est Ada Lovelace pionnière dans l'écriture de programme informatique. Il faut voir un programme comme une recette de cuisine qui élabore une série d'instruction comprise par la machine qui lui permet de faire un travail. Ainsi la note G d'Ada Lovelace est un algorithme très détaillé pour calculer les nombres de Bernoulli. La mentalité du programmeur est d'élaborer une recette pour résoudre un problème par une machine qui influença la mentalité des hackers. Ainsi par la suite va apparaitre des théoriciens, pères de l'informatique qui vont profondemment marquer la théorie sur les machines et créer l'ordinateur sur le papier. Tout d'abord Alan Turing, c'est en 1936 qu'il présente une expérience de pensée: la machine de Turing, et également le concept de programme informatique et de programmation. Ces travaux vont être secret durant la guerre car il travailla sur la machine Enigma des Nazis en tant que cryptanalyste pour décoder les messages de l'ennemi. La cryptographie est un domaine majeur des hackers que la transmission des messages secrets et l'anonymat. La machine de Turing, L'idée générale de ce modèle est qu'un acteur modifie ce qui est inscrit sur un ruban découpé en plusieurs cases, en appliquant des règles mécaniques, sans réfléchir. Par exemple une règle pourrait être : « si il y a un A dans la case que tu lis, alors écrit à la place Z et va à la case suivante ». Une telle machine pourrait servir à remplacer les A par des Z dans un texte. La machine de Turing est un modèle abstrait du fonctionnement d'une machine (mécanique) à calculer (type ordinateur). Ce modèle pensé par Alan Turing permet d'apporter une définition précise au concept d'algorithme (appelé alors « procédure mécanique »). Description d'une machine de Turing:

* Un ruban infini divisé en cases consécutives. Chaque case contient un symbole d'un alphabet fini donné. L'alphabet contient un symbole spécial appelé « symbole blanc » ('0' dans les exemples qui suivent), et un ou plusieurs autres symboles. Le ruban est supposé être de longueur infinie vers la gauche ou vers la droite, en d'autres termes la machine doit toujours avoir assez de longueur de ruban pour son exécution. On considère que les cases du ruban contiennent par défaut le « symbole blanc » ;
* Une tête de lecture/écriture qui peut lire et écrire les symboles sur le ruban, et se déplacer vers la gauche ou vers la droite du ruban ;
* Un registre d'état qui mémorise l'état courant de la machine de Turing. Le nombre d'états possibles est toujours fini, et il existe un état spécial appelé « état de départ » qui est l'état initial de la machine avant son exécution ;
* Une table d'actions qui indique à la machine quel symbole écrire sur le ruban, comment déplacer la tête de lecture, et quel est le nouvel état, en fonction du symbole lu sur le ruban et de l'état courant de la machine. Si aucune action n'existe pour une combinaison donnée d'un symbole lu et d'un état courant, la machine s'arrête.

Pour aller plus loin, le modèle est défini selon un alphabet fini. Une évolution possible serait des travaux en linguistique et théorie du langage sur des alphabets dynamiques et inventifs de nouveaux symboles. La machine fonctionne que si elle a connaissance de l'alphabet et si celui-ci n'ajoute pas des symboles dans le temps. C'est des pistes en cryptographie. Si dans le langage il est permis d'inventer, il y a un flou décisionnel qui apparait dans le sens que la machine doit faire un choix de mettre à jour dynamiquement son alphabet. Dans cette contrainte la machine est isolée. L'écriture chinoise ne connait pas l'alphabet, on utilise des images (idéogrammes) pour faire des mots. On manipule des traits de base, des figures simples formant des sons. C'est une véritable prolifération des caractères qui permet l'invention à l'infini.

L'autre grand acteur est le mathématicien John Von Neumann. Ces travaux sur l'automate cellulaire utilisé dans le jeu de la vie de Conway créant un objet nommé "planeur" est le symbole des hackers. Il donna son nom en informatique à l'architecture Von Neumann d'un ordinateur, toujours utilisé de nos jours ce composant de:

* l’unité arithmétique et logique (UAL) ou unité de traitement, qui effectue les opérations de base ;
* l’unité de contrôle, qui est chargée du séquençage des opérations ;
* la mémoire, qui contient à la fois les données et le programme qui indique à l’unité de contrôle quels calculs faire sur ces données. La mémoire se divise en mémoire vive (programmes et données en cours de fonctionnement) et mémoire de masse (programmes et données de base de la machine) ;
* les dispositifs d’entrées-sorties, qui permettent de communiquer avec le monde extérieur.

Les hackers se disent héritier des tout premier programmeur et donc des langages informatiques, plus particulièrement à Lisp créé en 1959 par John McCarthy au MIT qui s'utilise à l'époque sur des ordinateurs "mainframe", c'est à dire des ordinateurs centraux massifs dans des salles climatiseés tel que l'IBM 704. Il en convient donc que seulement quelques individus y ont accès à travers des laboratoires dans des universités ou à des fins militaires. Pour la culture il est important de noter que le papier de la description du langage Lisp en 1959 est toujours une référence en informatique: *recursive functions of symbolic expressions and their computation by machine*. En raison de son expressivité et de sa flexibilité, Lisp eut beaucoup de succès dans la communauté de l'intelligence artificielle. John McCarthy créa le laboratoire en intelligence artificielle, le SAIL(Stanford Artificial Intelligence Laboratory) par la suite fondé en 1962. C'est cette tradition d'ingénierie et de culture universitaire qui donna naissance à la culture hacker et le logiciel libre.

C'est au même moment toujours au MIT qu'apparait pour la première fois le mot hacker. C'est le terme donné aux membres du TMRC(MIT Tech Model Railroad Club) qui ont fait l'acquisition d'un PDP-1 pour programmer un réseau férroviaire miniature. Devenu le jouet favori de ceux-ci, ils inventèrent des programmes et un jargon. Ce club est le noyau dur de hacker qui formeront le laboratoire d'intelligence artificielle du MIT. La suite est lié à la création de l'ARPAnet (Advanced Research Projects Agency Network) en 1969 par le DARPA. C'est l'ancêtre d'internet qui va relier des organismes militaires et universitaires. Ce qui va contribuer à aider l'innovation militaire et la recherche universitaire en joignant dans un réseau les plus grandes universités U.S ou la documentation va être partagée avec des niveaux de confidentialité.C'est un âge d'or de l'aérospatial avec des projets tels que Apollo de la NASA, mais aussi le SR-71 "Blackbird" de Lockeed Martin en 1966. La recherche en intelligence artificielle et le spatial inspire des oeuvres tel que le roman "2001: L'Odysée de l'espace" d'Arthur C. Clarke et le mythique ordinateur HAL 9000. Dans la culture hacker, la science-fiction et l'espace sont omniprésent. On peut le noter par le premier jeu vidéo concocter par un hack d'un ordinateur et d'un oscilloscope matériel par les hackers du MIT qui ont inventé "Spacewar!" dès 1961. La gamification du quotidien allait naître, ou on y défini des buts qui vont souder la communauté. On peut penser que EVE Online est un héritier de l'esprit hacker par la simulation de combat spatial ou l'on va explorer les étoiles à travers la physique newtonienne dans un premier temps puis relativiste. La dernière frontière des hackers, le hack ultime.

Une autre histoire commença avec le PDP-10 et la création du système d'exploitation *ITS* au MIT qui refusa les logiciels du constructeur pour faire à sa sauce le sien. Il était codé en assembleur mais les projets relatifs à son utilisation utilisaient Lisp. L'une des raisons que Lisp et ces innovations, son jargon fait parti de la culture hacker par son utilisation intensive par les étudiants sur PDP-10. Emacs du projet GNU est codé en Lisp et reste un succès parmi les éditeurs de texte préférés des programmeurs.

Les hackers avaient trois origines ou laboratoire de formation et d'étude qui sont le laboratoire d'IA du MIT, Le SAIL et le CMU. Ou l'on inventa les premières applications des systèmes experts, de la robotique industrielle et des interfaces utilisateurs. Le Xerox PARC apporta de nombreuse innovation également tel que l'imprimante laser ou le LAN(Local area network).

UNIX fut un tournant par la création du système d'exploitation par Ken Thompson au laboratoire *Bell* en 1971. On retrouve une certaine maturité des systèmes d'exploitations en prenant les bonnes recettes de *Multics* et ITS. Le but rechercher est d'aider la programmation et donc l'accès aux logiciels. C'est ainsi que le langage C va être créer pour écrire UNIX par le hacker Denis Ritchie. Le livre "Langage C ANSI" ou K&R ecrit par celui-ci fait partie des must-have de la connaissance du langage C. Ce langage proche de la machine permet de ce passer d'assembleur qui n'est pas facile à lire pour les humains. UNIX et C vont largement être distribué dans les laboratoires et milieux universitaires jusqu'à l'arrivée du micro-ordinateur en 1975 et de la création de Microsoft par Bill Gates qui va privatiser le marché, il va écrire un document "An Open Letter to Hobbyists" ou il condamne l'open source et le piratage. Apple sera créé par le hacker Steve Wozniak et Steve Jobs en 1977 dont le système d'exploitation sera un dérivé d'UNIX. On peut parler des UNIX à cette époque tels que Berkeley ou celle de AT&T. Le système allait devenir propriétaire et donc la distribution du code source compromis.

Les années 80 va être l'apparition des premiers groupes de hacker et de l'essor de l'ingénierie sociale, l'exploitation de la ressource humaine. Le phreaking et les blues box pour téléphoner gratuitement ont débuté auparavent. Le cyberespace fait son apparition dans le roman de science-fiction avec Neuromancien de William Gibson précurseur à Matrix. Le groupe "414s" sera par le FBI accusé des 60 premières intrusions dans un système informatique. De nos jours il y a une culture "old school" de hackers lié à Legion Of Doom au USA, Le Chaos Computer Club en Allemagne donnant lieu aux premières affaires de cyberespionnage et les magazines "2600:The Hacker Quaterly" et "Phrack". C'est l'époque de protagoniste tels que Kevin Mitnick qui passa des années en prison pour vol de logiciel et destruction d'ordinateur mais également Kevin Poulsen alias "Dark Dante" qui s'introduisa sur l'ARPAnet de l'université de Californie(UCLA) en 1983. En 1984, Fred Cohen développe le terme de Virus informatique. L'année 1988, le célebre protocole de chat IRC fait son apparition, toujours utilisé par une partie des hackers pour sa sécurité, même si des applications tel que Discord à vue le jour. En 1989 aura lieu le premier "Denial of service" par Robert Morris et le ver Morris à l'université de Cornell, il voulait tester l'effet sur un système UNIX sur l'ARPAnet. Les USA allaient règlementer le cybercrime qui prenait son envol à travers "Computer fraud et abuse act" en 1986. L'émergence des premiers blacks hats dans le jargon nécessitait d'arrêter les actes de malveillance. Un incident aura lieu ou un hacker nommé "The Mentor" sera arrêté. Il va jouer un rôle dans la propagation de l'esprit hacker à travers le [manifeste hacker](https://www.larevuedesressources.org/le-manifeste-du-hacker,2298.html) qu'il aura écrit suite à son arrestation. Devenu symbole de la culture et de la psychologie derrière.

L'esprit hacker d'UNIX va être ré-écrite par le projet GNU de Richard Stallman qui va définir le logiciel libre face à la privatisation du secteur depuis l'arrivée du micro-ordinateur. Avec le noyau Linux la communauté hacker va rebondir.

Les services secrets vont faire de plus en plus d'investigation sur les activités de groupe d'hacker soupçonné de fraude tel que l'opération Sundevil en 1990. La recherche de faille sur les systèmes informatiques et ce connecter sur une machine à distance fait partie des techniques utilisées.

En France la communauté hacker va se structurer, mais l'autoroute de l'information qu'est internet fait des débuts hasardeux face au Minitel. Pourtant un homme, Jean-Bernard Condat, consultant pour la DST, les services secrets français va créer le Chaos Computer Club France, comme faux groupe de hacker pour les surveiller et les ficher par le renseignement durant les années 90. 

L'arrivée d'internet et le www(world wide web) accélère le basculement vers l'âge de l'information. C'est en 1991 que PGP développé par Philip Zimmerman sera diffusé sur le web comme logiciel libre et garantir un droit aux communications chiffrées par email. Parmis les hackers et puriste d'UNIX, freeBSD sera créé comme une solution libre. En 1994, Vladimir Levin, mathématicien, va hacker la Citibank et dérober 10 millions de dollars. La [déclaration d'indépendance du cyberespace](http://editions-hache.com/essais/barlow/barlow2.html) est déclaré le 8 février 1996, par John Perry Barlow (un des co-fondateurs de l'EFF). C'est une déclaration très engagé sur la souveraineté d'internet qui n'appartient pas aux gouvernements. De nos jours la surveillance d'internet par les gouvernements est un enjeu ou chacun aimerait se déclarer possesseur des données transitant sur le réseau. La législation prend en compte le pays pour le stockage des données. Le chiffrement des connexions du protocole TCP/IP a été acceléré à travers le HTTPS depuis l'annonce de la surveillance du réseau par la NSA ou encore le GCHQ du Royaume-Unis. En 1998, deux hackers chinois Hao Jinglong et Hao Jingwen vont pénétrer dans un système bancaire et voler 720 000 Yuans, ils seront condamné à la peine de mort. Cette même année le célèbre groupe "The cult of Dead Cow" va montrer à la conférence du hacking Def Con à travers le programme Back Orifice, un trojan( cheval de Troie) que l'on peu obtenir des accès non-autorisé à Windows à distance. L'année 1999 fut marqué par le développement de la trilogie Matrix, un univers cyberpunk ayant une grande influence sur la culture Hacker rendant mainstream l'[hypothèse de simulation](https://www.polytechnique-insights.com/tribunes/science/comment-savoir-si-nous-vivons-dans-une-simulation/) de Nick Bostrom au grand jour comme quoi nous vivons dans un programme informatique et questionne la réalité, cela fit couler beaucoup d'encre en philosophie. L'an 2000 va être marqué par l'un des plus grandes attaques DDos de l'histoire sur Yahoo, eBay, Amazon.com, CNN et quelques autres sites d'un hacker nommé "MafiaBoy", un adolescent canadien pour épater la communauté des hackers. Eric S. Raymond, à l'origine de l'open source va écrire un article célèbre ["Comment devenir un Hacker"](https://www.cairn.info/libres-enfants-du-savoir-numerique--9782841620432-page-255.htm%20-%20no10) ou entre autre pour résumer le papier il est nécessaire d'apprendre à utiliser un système UNIX, savoir programmer dans plusieurs langages tels que C pour les systèmes, Perl, Python et Lisp. Il préconise d'écrire des programmes au code source ouvert pour la communauté. L'auteur souligne l'importance de former l'esprit à la résolution de problème et automatiser les tâches ennuyeuses. Il parle d'apprendre à utiliser internet le WWW et de savoir utiliser l'HTML.

En 2003 va naître un mouvement et groupe d'hacktiviste: Anonymous. Le système de bulletin électronique, 4chan sera très associé à la genèse du groupe qui défend la liberté d'expression par des actions tels que l'attaque DDoS ou le défaçage de site web. Le groupe dénonce et attaque régulièrement la secte de la scientologie par le projet Chanology. Selon Chris Lander, du Baltimore City Paper datant du 2 avril 2008, "Anonymous est la première superconscience construite à l'aide d'Internet" dans le sens qu'il n'y a pas de leadership par un réseau décentralisé. C'est un exemple à suivre dans les méthodes de management que permet internet. La même année sortira Metasploit, par H.D Moore écrit tout d'abord en Perl puis la version d'après en Ruby. Il deviendra l'outil de test de pénétration le plus populaire parmis les hackers permettant de fournir des vulnérabilités sur les systèmes informatiques et de faire des tests d'intrusion, on peut écrire des exploits et des shellcodes(chaîne de caractères qui représente un code binaire exécutable, invoque un shell) en vue de tester un système cible. En 2006 le système d'exploitation BackTrack verra le jour comme suite complète de logiciel pour les tests de pénétration(Pentesting) qui sera ré-écrit en 2013 à la base de Debian sous le nom de Kali Linux.
Bien des groupes de hacker vont proliférer qui sont au coeur de la résistance numérique ont peu noter en particulier Telecomix, Lulzsec, ou encore Lizard Squad. La décennie 2010, une nouvelle forme de menace informatique sous le couvert des Etats s'annonce sous le nom d'APT(Advanced Persistent Threat). L'attaque est furtive et sophistiquée souvent sponsorisé par les gouvernements et militaires dans le but d'opération d'influence et de renseignement tel que de cyberespionnage d'entreprise, mais aussi de déstabilisation d'infrastructure stratégique tel que l'énergie. C'est le cas du malware Stuxnet, un programme informatique attribué à la NSA aux U.S pour pénétrer dans un système industriel SCADA et perturber le fonctionnement d'équipement pour l'enrichissement d'uranium en Iran. On compte aujourd'hui [94 APT référencés par mitre att&ck](https://attack.mitre.org/groups/). En 2017 le ransomware WannaCry a infecté des ordinateurs remontant à un groupe de hacker en Corée du Nord, le groupe Lazarus. D'autres groupes sont sponsorisés par des Etats tels que Double Dragon en Chine, Equation Group aux USA, Fancy Bear en Russie. La technique est en constante évolution et l'avenir est à l'utilisation de Machine Learning en intelligence artificielle permettant de nouvelle manière d'aborder l'ingénierie sociale. Ce chapitre résume bien l'évolution des hackers depuis les origines de l'informatique et l'état des lieux du champ d'application des compétences. Les mercenaires de l'informatique prolifèrent tel que la vente de faille 0days pour des entreprises ou des Etats mais egalement le programme de bug bounty qui permet dans un cadre légal de trouver des failles de sécurité contre une prime dans le but d'améliorer les logiciels. Des hackers ont pu devenir millionaire comme Santiago Lopez. Le cybercrime n'est plus la seule source de revenue et de profit. Mais certain hacktivisme ne recherche que la destruction par idéologie pour que ce monde brule forçant le capitalisme à la remise en question ouvrant la voie à d'autres systèmes de gouvernance supervisé dans le futur par l'intelligence artificielle permettant un meilleur traitement des données pour la prise de décision. Dans un monde informationnel, à l'age d'internet, la compétence de hacking est la clé de ce siècle pour maitriser l'information mais aussi créer et faire évoluer la société.

Quelques hackers qui ont marqué la culture par leurs actes passés:
* **Kevin Mitnick**, en 1982, il a hacké le NORAD( North American Defense Command ) qui a inspiré le film *War Games*, plus tard c'est la société DEC ou il pénétra sur ces réseaux et copia les logiciels. 
* **Adrian Lamo** surnomé "the homeless hacker" sans domicile fixe, il n'avait qu'un sac léger pour voyager, sans adresse fixe, il est connu pour avoir pénétrer les réseaux du New York Times, Yahoo et Microsoft.
* **Albert Gonzalez** a organisé une fraude touchant 135 millions numéros de carte de crédit, il fut egalement un informateur des services secrets pour éviter la prison. Pour exploiter ces fraudes il utilisa l'injection SQL pour mettre en place des backdoors.
* **Matthew Bevan et Richard Pryce** qui ont joué au *war games* avec le Pentagone. Ils ont pénétré dans plusieurs systèmes militaires dont: Griffiss Air Force Base, the Defense Information System Agency et the Korean Atomic Research Institute (KARI). Ils ont été accusé de vouloir lancer une troisième guerre mondiale. Pour leur défense, l'un parla qu'il cherchait à prouver une conspiration d'OVNI.
* **ASTRA**, est un mathématicien grec de 58 ans qui a sévit sous le pseudo de ASTRA et pénétrer l'entreprise Dassault pour voler des informations sur des systèmes d'armement ainsi que des logiciels pour les revendres.

## 0.7 Ou Obtenir de l'aide?

Il existe bien des ressources disponible pour celui qui veut progresser en informatique et particulièrement touchant au logiciel libre et à l'open source. Le réflexe en l'occurence se réfère à *RTFM* >> Read The Fucking Manual! On le dira jamais assez, lisez le manuel et la documentation. Ainsi chaque commande dans un terminal est documenté. Un problème pensez `man` pour *manual* et taper le nom de la commande. C'est déjà un début. Pour ce familiariser à la ligne de commande car c'est de ça qu'il est question plus tard dans ce livre en particulier Arch Linux, mettez dans votre navigateur ces liens suivants:

* [https://www.webminal.org/](https://www.webminal.org/) est un site pour apprendre la ligne de commande
* Les wikis Arch Linux en français [https://wiki.archlinux.fr/](https://wiki.archlinux.fr/) et anglais [https://wiki.archlinux.org/](https://wiki.archlinux.org/)
* Le livre disponible chez framabook [*Unix, pour aller plus loin avec la ligne de commande*](https://framabook.org/unixpou-allerplusloinaveclalignedecommande/)

Parlons des communautés, malgré l'élistisme parfois à tord attaché à Linux, il est possible de poser des questions, obtenir de l'aide et chercher si le problème n'a pas dejà été résolu auparavent sur le web. Quelques communautés francophones:
* Linux sur developpez.net et son forum
* Trouvez un GUL(groupe d’utilisateur de Linux) près de chez vous sur le site de l’[aful](https://aful.org/) et contactez-les.
* Le canal IRC de #archlinux-fr et son forum. Sur Windows utilisez le client IRC xchat. Et configurer le serveur sur libera. Ou directement via le navigateur Web https://web.libera.chat/#archlinux-fr
* Arch Linux fr sur [Signal](https://signal.group/#CjQKILMI8IXAepQEWDL7SM7ZWxVDxUV6N2T7IurW2mPWHKI8EhDDHdp1VQlE9YjhzG-_XoZ_) 
* Arch Linux fr sur [telegram](https://t.me/archlinux_fr)

Pour les sites généralistes sur Linux anglophone à l'internationnal, les principaux sur le web traitant des demandes d'aides sont:

* LinuxQuestions.org
* StackOverflow 
* Reddit (r/linux) et l'IRC Linux https://web.libera.chat/#r/linux
* unix.stackexchange.com

En ce qui concerne des questions sur le logiciel libre et la vie privée, l’auto- défense numerique et la surveillance du web rejoignez la quadrature du net. Sur le canal IRC `#laquadrature@irc.libera.chat`. Vous pouvez trouver de l’aide pour se protéger dans le cyberespace en contactant et utilisant les outils du mouvement [Crypto Party](https://www.cryptoparty.in/) sur l’IRC `#cryptoparty@irc.oftc.net`.

Une bonne solution pour rejoindre un groupe est de ce rapprocher d'un Hackerspace. Un hackerspace c'est quoi? C'est une communauté de passionné en informatique et électronique, des personnes qui bidouille et démonte les ordinateurs mais également qui ont un intérêt pour la science et la créativité. La liste des hackerspaces dans le monde est disponible sur ce site:
https://wiki.hackerspaces.org/Hackerspaces.

Le hackerspace le plus connu est surement *c-base* du CCC(Chaos Computer Club) dans le monde en Allemagne à Berlin. Les hackerspaces sont les précurseurs aux FabLabs qui sont apparu dans la décennie 2010, en particulier par l'arrivée du materiel libre tel que Arduino et de la Rep Rap qui est une imprimante 3D. 

Pour trouver des hackers, le web à rassemblé des ressources utile pour la communauté. Un point d'entrée intéressant est Reddit et r/Hacking dont le wiki est particulièrement bien documenté à cette adresse: [https://new.reddit.com/r/hacking/wiki/index](https://new.reddit.com/r/hacking/wiki/index). Sur Reddit, la communauté compte 2,1 millions d'abonnés. Mais continuons à creuser plus profondemment comme les forums:

* [https://raidforums.com/index.php](https://raidforums.com/index.php)
* [https://hackforums.net/](https://hackforums.net/)
* [https://evilzone.org/](https://evilzone.org/)
* [https://0x00sec.org/](https://0x00sec.org/)

La communauté française est présente à travers quelques sites et chats de discussion, pour certain facile d'accès et pour d'autres il faut réaliser une série d'épreuve en tant que hacker.

* [https://instant-hack.to/](https://instant-hack.to/) 
* [https://hackademics.fr/](https://hackademics.fr/)
* [https://forum.zenk-security.com/](https://forum.zenk-security.com/
)

En ce qui concerne le dark web, on retrouve des activités illégalles de service tel que la vente de malware, mais utile si vous cherchez à vous fournir en materiel pour l'analyse et l'étude. On peut trouver des contenus sujet à contreverse mais intéressant pour la connaissance. Certain de ces communautés sont élitiste et restreint l'accès tel que:

* cryptBB
* Torum
* KickAss
* 0days

En résumé, vous n'êtes pas seul, ce poser des questions est le début de l'aventure, résoudre des problèmes et faire appel à la communauté est un processus normal, on ne peut pas tout connaitre, même moi je vais sur google de temps en temps pour des commandes basiques, YouTube pour des tutoriaux sur des sujets plus précis qui évoluent dans le temps. Apprendre à apprendre, que cela soit du junior au senior n'est pas forcément un comportement que l'on adopte naturellement, cela demande de mettre en place des automatismes que j'espère ces quelques lignes permettent d'aiguiller sur le territoire de l'informatique. 

## 0.8 Ce former en informatique sur le web

Dans ce livre je traite de la formation en informatique, et je me suis dis que cela serait bien que de faire un chapitre sur les ressources sur internet en accès libre, car je crois que l'éducation devrait être accessible à tous et sans payer le prix fort comme les outils de création aidant les processus d'innovation. Ce livre aborde en particulier le sujet de la création du système d'exploitation Arch Linux et les outils de développement pour créer du contenu en particulier des logiciels libres. La suite est d'introduire des cours de programmation, approfondir des sujets en informatique ou encore faire du webdev (développement web). Quelques sites qui vont bien:

* **Khan Academy** a une section informatique, c'est un site généraliste pour l'apprentissage scolaire et la science. On y trouve des cours intéressant sur l'HTML, le Javascript ainsi que la cryptographie.
* **Cybrary** est le site de la formation IT et cybersécurité pour faire une carrière professionnelle. On y retrouve des cours sur les réseaux, le pentesting, linux etc.
* **Coursera** la plateforme de MOOC largement adopté par la communauté.
* **The Odin Project** La philosophie du projet est de rendre accessible le développement web et l'informatique à travers des cours hors des prix d'aller à l'université ou de bootcamp comme formation intensive. Au programme du HTML, CSS, Javascript et l'apprentissage de Ruby pour maitriser le framework *Ruby On Rails*.
* **MIT OpenCourseWare** L'arrivée des MOOCs sur internet depuis la décennie 2010 voit l'accès à l'éducation non plus restreint aux amphithéatres des grandes écoles. Ainsi le MIT a mis en ligne ces cours dans plusieurs domaines dont l'informatique.
* **OSSU, Open Source University** est une initiative sur Github pour les autodidactes en informatique regroupant par catégories tous les pré-requis pour la formation universitaire en informatique en libre accès. Cela traite de programmation, mathématiques, base de données, architecture logicielle, langages et des specialisations en cybersécurité ou intelligence artificielle.
* **Teach Yourself computer science** est une liste des meilleurs livres pour autodidacte pour l'apprentissage de l'informatique de la littérature anglaise.
* **OpenClassRooms** Le site français de formation en informatique avec des cours gratuits, référence depuis plusieurs années, a également publié des bouquins sur l'apprentissage de la programmation comme du Python, C++,C.

## 0.9 Ce que dit la loi

Un sujet qui divise les hackers en catégorie, c'est bien l'éthique ainsi que la morale de produire un hack. La légalité n'est pas toujours légitime. Il est parfois nécessaire d'agir dans l'ombre par idéologie mais également pour du profit. Le monde n'est pas manichéen ou il existe les bons et les méchants. On navigue autour d'un spectre ou en fonction de la situation parfois on peut excuser la personne abordant une jurisprudence. Chacun assume ces responsabilités, nous ne vivons pas avec les mêmes moyen et personnellement une personne vivant dans la précarité qui cherche à faire du profit en hackant des organisations n'est pas forcément condamnable moralement, car chacun a le droit à un confort de vie meilleur, et tous les moyens sont bon en particulier l'escaladation de privilège dans la société. 

Le capitalisme a pour but d'enrichir les individus en faisant du profit, malgré cela la pauvreté existe qui est source de cybercriminalité, blamez la faille de sécurité que le hacker qui l'exploite. Celui-ci fait preuve de curiosité et de créativité pour utiliser le système en testant des limites. Malgrez cela la loi qui régule la société met un frein aux dérives les plus extrèmes pour ne pas porter préjudice aux autres et empieter sur les libertés de chacun. Comme dernièrement le montre l'affaire très médiatique de Julian Assange, porte parole majeur du mouvement nous pouvons prendre le risque de finir en prison pas seulement pour du vol d'argent mais pour la libre circulation de l'information qui condamne des crimes. Cet hactivisme est louable, c'est une leçon de courage contre le système et en particulier les documents classifiés des Etats rendant opaque la gouvernance des nations voir des entreprises pour des intérêts commerciaux ou technologiques. On voit alors les limites de la répression pour sauvegarder un système. Il est donc nécessaire de faire un rappel à la loi française sur les risques que prennent les hackers. La prison est une mesure de dissuasion censé combattre le cybercrime mais nous pouvons être dur au mal, ou la solitude d'une cellule n'est qu'un passage éphémère de la vie. La peur de l'enfermement est pour les faibles d'esprit, bien des recherches ont été faite au-delà des lois avec parfois des découvertes en science. La recherche du profit n'étant pas condamnable dans un monde ou nos libertés sont conditionnés par la possession de bien permettant le logement, le transport, l'alimentation.

Ce que dit les textes de loi relatif au piratage informatique:

**Loi informatique et libertés**
Il s’agit de la principale loi relative à la protection des informations privées des utilisateurs dans les systèmes informatiques, même si la loi est également applicable pour des fichiers non informatisés. Elle protège les personnes physiques et la circulation des informations les concernant.

La loi informatique et libertés est datée du 6 janvier 1978 et a été mise à jour en 2004. Elle définit les principes à respecter lors de la collecte, du traitement et de la conservation des données personnelles. Cette loi assure la protection de la vie privée des personnes dans le cadre des systèmes d’information.

Elle définit les données susceptibles d'être collectés et celle qui sont interdites à la collecte, par exemple les information relatives aux origines ethniques, à l'appartenance religieuse... sauf accord des personnes concernées.

La loi s'assure de la bonne utilisation des informations (conformes au but de la collecte) et définit les droits des utilisateurs quant aux données les concernant : droit d'accès, d'opposition, de rectification et de suppression.

C’est aussi dans le cadre de cette loi qu’a été instaurée la première autorité administrative indépendante : la CNIL.


**Loi Godfrain**
Cette loi du 5 janvier 1988 est la première loi instaurée contre le piratage informatique. Elle prévoit un cadre pénal pour l'intrusion sans autorisation dans un système de traitement automatisé de données (STAD) : cela peut être un ordinateur, un réseau téléphonique, un serveur...

Elle prévoit ainsi un certain nombre de sanctions en cas d'intrusion dans ce type de système sans autorisation. Ces sanctions seront plus ou moins lourdes en fonction des dommages causés dans les systèmes, du caractère volontaire ou non de l'infraction ou encore du fait que l'infraction soit commise seul ou en bande organisée.

Le **Code pénal** (articles 323-1 à 323-8) sanctionne la cybercriminalité. Pour avoir accédé frauduleusement dans un traitement automatisé des données, une personne peut être punie de 2 ans d'emprisonnement et de 60.000 euros d'amende. En cas d'altération grave du système piraté, la peine est alors portée à 3 ans d'emprisonnement et 100.000 euros d'amende. Quand le système de l'Etat et ses données sont piratés, la peine est de 5 ans d'emprisonnement et 150.000 euros d'amende. Si le traitement des données piraté est un traitement automatisé de données à caractère personnel mis en œuvre par l'État, la peine peut aller jusqu'à 7 ans de prison et 300.000 euros d'amende. La personne qui introduit frauduleusement des données dans un système de traitement automatisé encourt :

* jusqu'à 5 ans de prison et 150.000 euros d'amende ;
* 7 ans et 300.000 euros s'il s'agit d'un traitement automatisé de données à caractère personnel mis en œuvre par l'État.

Outre ces peines, les personnes physiques qui commettent ces infractions pénales encourent des peines complémentaires :

* interdiction des droits civiques,
* interdiction d'exercer une fonction publique pour cinq années,
* exclusion des marchés publics pour la même durée,
* interdiction d'émettre des chèques pour la même durée,
* confiscation du matériel informatique, etc.

En ce qui concerne la protection d'une découverte d'une faille informatique sur un site web, le texte de loi dit:

C'est donc l'article 47 de la loi du 7 octobre 2016 qui prévoit que le code de la défense soit complété par un article L. 2321-4 ainsi rédigé :

« Art. L. 2321-4.-Pour les besoins de la sécurité des systèmes d'information, l'obligation prévue à l'article 40 du code de procédure pénale n'est pas applicable à l'égard d'une personne de bonne foi qui transmet à la seule autorité nationale de sécurité des systèmes d'information une information sur l'existence d'une vulnérabilité concernant la sécurité d'un système de traitement automatisé de données. 
« L'autorité préserve la confidentialité de l'identité de la personne à l'origine de la transmission ainsi que des conditions dans lesquelles celle-ci a été effectuée. 
« L'autorité peut procéder aux opérations techniques strictement nécessaires à la caractérisation du risque ou de la menace mentionnés au premier alinéa du présent article aux fins d'avertir l'hébergeur, l'opérateur ou le responsable du système d'information. »

La protection des citoyens détecteurs de faille informatique, est donc assurée par cette nouvelle disposition, afin de les inciter à révéler ces failles à l’Agence nationale pour la sécurité des systèmes d’information, sans encourir de risque pénal pour cette action.

## 0.10 Cyberculture

Parlons un peu de la *culture numérique*, je vais introduire ma connaissance sur le sujet et synthétiser l'information, car je suis un peu formateur sur mon blog en informatique, en particulier pour les gens un peu loin de tout ça tels que des Boomers ou vivant dans la ruralité. 

### Noosphère 

L'une des figures qui a théorisé le concept est le jésuite, théologien français et scientifique **Pierre Teilhard de Chardin** 1881 - 1955 à travers le terme **noosphère** dérivant inéluctablement du progrès de l’évolution, celle-ci s’achèvera selon lui vers une transhumanité "lorsque les consciences, mises en réseau les unes avec les autres, créeront de facto, une sorte de super-être." C'est une **gnose transhumaniste** qui fait toujours débat ou après la géosphère puis la biosphère généra la noosphère sur une idée du progrès. 

Dans ses écrits, il parle de l’avancement de la biosphère et de l’étape transitoire qui doit mener vers la noosphère : il s’agit de la technosphère. Il s’agit d’après Teilhard d’un réseau d’information mondial – il parle de géotechnologie – qui se rapproche énormément de l’Internet tel qu’il existe aujourd’hui.

Cette avant-dernière étape dans le développement de la couche de pensée serait le moyen de connecter la noosphère avant d’atteindre le moment mystique du point Oméga.

Ce réseau de conscience globale imaginé par Teilhard, fait penser à la théorie de l'intelligence collective.

### Cybernétique

Une autre approche théorique de la *cyberculture* datant de 1948 est celle de la théorie cybernétique de Norbert Wiener, science qui étudie la circulation de l’information dans les systèmes autorégulés. 

La cybernétique est une théorie de la gestion des processus automatisés par calcul des flux d'informations rentrants (input) et sortants (output). Ses concepts clés sont: l'équilibre, le système, la boîte noire, la rétroaction (feedback) et l'information. Cette pensée est née avec l'informatique et elle a été par la suite fortement inspirée par la biologie. On introduit alors une pensée en système complexe.

L'étude des automates va devenir l'un des "fer de lance" de la communauté des Hackers avec le célèbre *jeu de la vie de Conway*.

### Planétisation

Ce que l'on pensait isolé n'ayant pas d’interaction entre eux, vont ce voir être mise en réseau grâce au progrès des télécommunications et des médias. Cette globalisation va générer des tensions culturels et conflits, des théories de domination mondiale vont émergé tels que le NWO "Nouvel Ordre Mondial" aux lignées Illuminati et la question du pouvoir. Rien de cela ne serait possible sans faire des connexions avec l'information que va générer le **cyberespace**.

### Le Cyberespace

Le terme est apparu dans un classique de la science-fiction qui a eu le prix Hugo qui récompense les meilleurs oeuvres du genre par l'oeuvre de William Gibson: **Neuromancien** en 1984. C'est l'histoire d'un hacker dans un monde futuriste cyberpunk capitaliste en proie à des mégacorporation ou il connecte un casque avec des implants cybernétique pour entrée dans la Matrice, un monde informatique. En quête de donnée à monnayer à travers des failles de sécurité il pirate le système. 

### Copyleft

De la culture des hackers va naître le projet GNU en 1983 par Richard Stallman qui est une ré-écriture d'UNIX propriétaire. La question de la propriété intellectuelle va être débattu en introduisant le **Copyleft** fondant la notion de logiciel libre. La libération de l'émission fait parti des lois de la cyberculture né dans le logiciel libre suivi de concept tels que le **fork** ou le remix d'une oeuvre que cela soit pour l'étude, la modification et l'amélioration que l'on voit particulièrement chez les écrivains mais également dans les programmes informatiques. Le média est un vecteur d'une culture du partage et des communs.


### Le World Wide Web

A l'origine du WWW, l'un des père de l'internet en 1989 au CERN est Tim Berner-Lee ou il créé un réseau informatique en pensant aux scientifiques et la notion de peer-reviewing des documents pour accélérer le partage et l'étude par des pairs de progrès en science en connectant les réseaux universitaires entre eux. Des sites internet vont naître grâce au **HTML** permettant de mettre à disposition des documents. 

La mise en réseau des acteurs fait partie des lois de la cyberculture à travers le partage tels que le Peer-To-Peer et de nos jours le fédiverse.

### Déclaration d'indépendance

La [Déclaration d'indépendance du cyberespace](https://movilab.org/wiki/D%C3%A9claration_d%E2%80%99ind%C3%A9pendance_du_cyberespace) est un document rédigé le 8 février 1996 à Davos en Suisse par John Perry Barlow, un des fondateurs de l'Electronic Frontier Foundation. Il soutient l'idée qu'aucun gouvernement (ou qu'aucune autre forme de pouvoir) ne peut s'imposer et s'approprier Internet, alors en pleine extension. Il a été écrit en partie en réponse à l'adoption de la Loi sur les télécommunications de 1996 aux États-Unis. C'est la naissance de la neutralité du net et ces combats sous diverse loi des gouvernements qui cherchent à contrôler les communications et surveiller la population. En France, la communauté va se structurer sous la loi Hadopi et la Quadrature du net sur les chat IRC.

Citation:

>Gouvernements du monde industrialisé, géants fatigués de chair et d’acier, je viens du cyberspace, le nouveau domicile de l’esprit. Au nom du futur, je vous demande, à vous qui appartenez au passé, de nous laisser en paix. Vous n’êtes pas les bienvenus parmi nous. Vous n’avez aucune souveraineté sur le territoire où nous nous assemblons. 

### Reconfiguration culturelle

La dernière loi de la cyberculture est la reconfiguration culturelle né du cyberpunk. Les déviants tels que le cipherpunk vont construire des communautés virtuels protégeant la vie privée et les communication tels que la naissance de la cryptomonnaie, le **bitcoin** dans l'échange monétaire. Des figures du mouvement vont apparaître tel que Julian Assange et WikiLeaks avec le monde souterrain du darknet. Des lanceurs d'alertes vont dénoncé l'action des gouvernements et la surveillance de masse avec Edward Snowden et le projet de la NSA aux USA. Des actions d'hacktivisme vont avoir lieu tels que l'apparition du groupe Anonymous ou Télécomix.

Des objets vont apparaître de la cyberculture open-source hardware comme **Arduino** révolutionnant le monde des bidouilleurs et ingénieurs.

Des figures tels que "le geek, le nerd, no-life etc" seront les agents sur les réseaux dans des MMO comme *Second Life* ou *EVE Online* au célèbre *WoW* dans un univers fantaisiste.

Des phénomènes de la culture internet vont envahir les réseaux, du lolcat à travers des Memes en passant par Pedobear aux trolls sur le web, c'est tout un eco-système culturel.

La cyberculture est un vaste champ d'étude, y trouver sa place est un long chemin, si vous décidez d'y entrée vous pourriez bien y être surpris par la pensée, un vaste champ d'étude tels que les humanités numériques émerge. Vous pourriez y faire votre emploi et construire le cyberespace ou l'exploiter à votre fin pour en tirer du bénéfice. Ce choix vous appartiens, mais ne croyez pas que vous pourriez vous isolez et retourner à la nature sans être confronter à son impact autour de vous. 

## 0.11 Principe des machines

Pour une machine, tout commence par un signal électrique. Un courant qui est généré par des charges dans un conducteur avec des électrons. On a donc inventé les semi-conducteurs en particulier le transistor qui est la base des ordinateurs et c'est un commutateur.  

### Le transistor  

A la même époque vont naître les travaux sur les machines de Turing et les architectures de Von Neumann qui sont la base de la conception des ordinateurs moderne.  

Le transistor a été inventé en **1947** par trois ingénieurs américains des laboratoires Bell : **John Bardeen, Walter Brattain** et **William Schockley**. L’invention de ce dispositif qui permet de détecter et d'amplifier les courants électriques leur a valu le **prix Nobel de physique en 1956**. John Bardeen va remporter un second Prix de Nobel de physique en 1972, il oriente ses recherches vers la compréhension des mécanismes de la **supraconductivité**. La formulation d'un modèle de couplage d'électrons et de leurs interactions avec les vibrations du réseau cristallin des solides sous le nom de théorie BCS, des initiales de Bardeen et de ses collègues **Leon Neil Cooper** et **John Robert Schrieffer**, permet d'expliquer les phénomènes de résistivité électrique nulle observés dans les supraconducteurs.  

Sur le principe un transistor est un commutateur qui permet de commander un courant électrique. C'est un signal carré. Soit ouvert ou fermé que l'on défini par 0 ou 1. Les systèmes de traitement du calcul travail que sous forme binaire. Ce que l'on appel les bits. C'est le langage machine. Celui-ci admet des cycles de traitement de l'information à travers une fréquence en Hertz, ce qui permet d'avoir une horloge.  

L'assemblage de plusieurs transistors permet de créer des circuits logiques utilisant l'algèbre de Boole. Ainsi on utilise des portes logiques (AND, NOT, OR, XOR, NAND) permettent de traiter des instructions du processeur sur la logique combinatoire basé sur des [propositions et des prédicats](https://zestedesavoir.com/tutoriels/2256/de-la-logique-aux-processeurs/la-logique-des-propositions-et-des-predicats/).  

### La représentation de l'information  

La base de la théorie de l'information de Shannon est le bit. Un regroupement de 8 bits correspond à l'octet qui prend la valeur de 0 à 255. Pourquoi 8 bits? C'est des puissances de 2 (8 = 2^3) qui permet d'accélérer le traitement du code informatique. Ainsi on converti le binaire en base 16 hexadécimal qui est un regroupement de 2 x 8 bits (Octets). Mais il y a d'autres base, en particulier pour améliorer la cryptographie tel que la base 36, 64, 128, 256 qui sont des puissances de 2, voir certaine des bases carrés. sqrt(16) = 4, sqrt(36) = 6, sqrt(64) = 8 . Un système de nombre en informatique pour optimiser le calcul utilise une base de puissance de 2 (binaire) avec une combinaison de base carré. En cryptographie le MD5 est un hash sur 128 bits sur la base 64. Il est donc nécessaire de faire des changements de base entre des systèmes numériques ce qui augmente le temps de calcul et donc de casser le code. Sha-256 est une des fonctions de hachage les plus efficaces actuellement en base 64. Une base 512 se forme sur 8x8x8 et donc plus de 512 caractères différents. 8 étant une puissance de 2 et représente un octet.  

Pour représenter les caractères on a inventé une table nommé ASCII. Ce qui est suffisant pour l'anglais et l'alphabet codé sur 255 valeurs et donc un octet. Mais cela n'est pas suffisant pour le chinois et ces symboles, il faut de l'UTF-8. Ce qui augmente les temps de traitements pour calculer et déchiffrer du code qui est basé sur 214 radicaux. l'UTF-8 pouvait coder n'importe quel point de code entre U+0000 et U+7FFFFFFF (donc jusqu'à 31 bits).  

Il y aurai également a traiter les nombres en particulier les flottants qui ont une représentation spécifique.  

### CPU  

Les composants du CPU des ordinateurs:  

*   Bus : nappes transportant l'info  
    
*   Registres : emplacements de stockage à accès rapide  
    
*   ALU :unité de calcul (entiers et booléens)
*   Unité de contrôle :interprète les instructions
*   Horloge :cadence les instructions  
    

Les architectures de processeur:  

*   x86-64 (Intel, AMD) : PC et compatibles  
    
*   ARM : beaucoup de téléphone, Raspberry Pi
*   PowerPC (IBM) : Wii, PS3, XBox 360
*   MIPS, RISC-V etc.  
    

Les instructions machine:  

Instruction Set Architecture (ISA): modèle qui définit comment le logiciel contrôle le hardware (code binaire)  

chaque processeur possède son propre jeu d'instructions machine

*   ARM is RISC (Reduced Instruction Set Computing)  
    
*   x86 is CISC (Complex Instruction Set Computing)
*   chaque instruction possède un identifiant numérique : opcode  
    

La programmation directe du processeur avec les instructions machines est difficile, fastidieuse et quasi-impossible à comprendre. Le **microcode** est un programme composés de micro-instructions dont l'exécution au sein du processeur ou microprocesseur définit le jeu d'instructions de celui-ci.  

**RISC-V** (prononcé en anglais « RISC five » et signifiant « RISC cinq ») est une architecture de jeu d'instructions (instruction set architecture ou ISA) RISC ouverte et libre, disponible en versions 32, 64 et 128 bits. Ses spécifications sont ouvertes et peuvent être utilisées librement par l'enseignement, la recherche et l'industrie. Les specifications sont ratifiées de façon ouverte par la communauté internationale des développeurs.  

### Le langage assembleur  

C'est le langage le plus proche de la machine compréhensible par les humains. Il est variant en fonction de l'architecture du processeur défini par le constructeur. Les combinaisons de bits du langage machine sont représentées par des symboles dits « mnémoniques », c'est-à-dire faciles à retenir.  

Certaines opérations fondamentales sont disponibles dans la plupart des jeux d'instructions.

*   Déplacement dans la mémoire :
    *   chargement d'une valeur dans un registre ;
    *   déplacement d'une valeur depuis un emplacement mémoire dans un registre, et inversement ;
*   Calcul :
    *   addition, ou soustraction des valeurs de deux registres et chargement du résultat dans un registre ;  
        
    *   combinaison de valeurs de deux registres suivant une opération booléenne (ou opération bit à bit) ;  
        
*   Modification du déroulement du programme :
    *   saut à un autre emplacement dans le programme (normalement, les instructions sont exécutées séquentiellement, les unes après les autres) ;
    *   saut à un autre emplacement, mais après avoir sauvegardé l'emplacement de l'instruction suivante afin de pouvoir y revenir (point de retour) ;
    *   retour au dernier point de retour ;
*   Comparaison :
    *   comparer les valeurs de deux registres.

Et on trouve des instructions spécifiques avec une ou quelques instructions pour des opérations qui auraient dû en prendre beaucoup. Exemples :

*   déplacement de grands blocs de mémoire ;  
    
*   multiplication, division ;  
    
*   arithmétique lourde (sinus, cosinus, racine carrée, opérations sur des vecteurs) ;  
    
*   application d'une opération simple (par exemple, une addition) à un ensemble de données par l'intermédiaire des extensions MMX ou SSE des nouveaux processeurs.  
    


### Linux et la routine de démarrage du noyau  

Pour démarrer le noyau Linux au bootloader on utilise le langage assembleur, si vous voulez créer et comprendre les systèmes d'exploitation il est nécessaire de lancer le noyau en assembleur avant le traitement en langage C. Quand la bzImage (pour une image destinée au i386) est appelée, vous commencez à [./arch/x86/boot/header.S](https://elixir.bootlin.com/linux/latest/source/arch/x86/boot/header.S) dans la routine assembleur nommée start.  


### sysCall  

Les process utilisent les sysCall pour communiquer avec le noyau comme API avec l'assembleur. Les sysCall sont listés _dans /usr/include/asm/unistd.h_  

### Les compilateurs  

Le principal compilateur en langage C, nommé **GCC** est écrit en assembleur + C. Il permet également de produire du code en assembleur, car le compilateur converti les programmes en langage machine. Pour écrire du code assembleur pure et le compiler sur Linux on utilise NASM sans passé par l'intermédiaire du langage C. Je crois que c'est le seul compilateur GCC qui permet de traduire en assembleur. Le langage C est l'anneau de pouvoir de l'informatique ou tous les autres langages dérives mais également les compilateurs et interpréteurs. Ainsi l'interpréteur en Python(CPython) est écrit en langage C. Il faut donc apprendre le langage C dans les premiers langages de programmation et ce familiariser avec spécificité tel que l'accès à la mémoire et les pointeurs.

## 0.12 Contribuer à l'open source

La carrière d'un hacker suit souvent le même cadre d'apprentissage. Tout d'abord on cherche à apprendre un langage de programmation. Je conseil de commencer avec le langage C car un héritage de la création d'UNIX. Puis on se familiarise à la ligne de commande. On switch sous Linux par idéologie, mais également pratique pour avoir les outils pour développeurs et chercheur en cybersécurité. On approfondi rapidement les structures de données et les algorithmes. On peut chercher à monter et administrer des systèmes sur mesure tel que sous Arch Linux et Gentoo par sécurité mais également de l'art numérique en customisant son OS. Tout ça dans l'optique de rependre le contrôle sur la machine. Vous n'êtes plus consommateur, mais devenez un créateur. Cette étape, le mindset est importante dans la construction cognitive. Vous allez pouvoir agir à votre manière sur le monde, et le modifier selon vos perspectives. La recherche de vulnérabilité ne vient pas tout de suite dans l'apprentissage. On attribue le hacking trop souvent à l'exploitation de serveur distant, élévation de privilège. Vous pouvez devenir un kernel hacker en devenant spécialiste du noyau Linux et le patcher écrit en C.Il y a environ 5000 kernel développeurs dans le monde mais c'est l'élite et le salaire tourne en moyenne à 9000€/mois. Forcément sans les bases du langages vous ne pourrez pas rechercher des vulnérabilités dans le code. Une autre activité est de casser les licences propriétaires des logiciels ou limitations généralement du C++. Une connaissance du langage, de la retro-ingénierie de binaire est nécessaire. Lancer un botnet de cryptomonnaie et infecter des ordinateurs demande un minimum de code. Pour le langage de scripting tourné vous vers Python est Ruby. Vous pouvez faire de l'argent par vos malwares et revendre sur le darknet, personnellement je ne juge pas, chacun sa manière de contribuer à la communauté. Mais l'une des manières la plus répandu est le social coding tels que sous des plateformes comme Github(Microsoft depuis 2018) avec 76 millions de développeurs et Gitee en Chine avec plus de 5 millions de développeurs, ne négligez pas les chinois par un frein de la langue. Github c'est quoi? A la base il y a un logiciel développé par Linus Torvalds pour les besoins de gestion de version du code du kernel nommé: Git. Maintenir et développer du code de logiciel libre en public sur un repository distant est la norme en passant généralement par Github. Plus généralement c'est la contribution à l'open source dérivé commercial créer par Eric S. Raymond. Utilisez Git demande un peu de temps, mais devient rapidement indispensable au développeur. Un exercice intéressant pour débutant est d'apprendre à coder avec Vim + plugins "Fugitive" un petit jeu vidéo comme Space Invader sur un repo distant Github avec Python et Pygame. Vous trouverez comment utiliser Git + Github sur internet. N'oubliez pas vous êtes évaluez par vos pairs via vos projets que vous partagez, le diplome n'a pas d'importance, mais la qualité du code intéresse les parties prenantes.

Pour démarrer un projet Github ce que je fais:

* Créer le repository sur Github, ajout licence, readme + .gitignore
* Git clone en ssh le repository sur mon ordinateur en local
* Je commit mon code via Vim+fugitive
* Je push sur le repo distant les modifications 

**Liens**

* 1 [Pourquoi contribuer à l'open source](https://opensource.guide/fr/how-to-contribute/)
* 2 [Les bases pour créer un projet Github](https://gamebuino.com/fr/academy/workshop/partagez-votre-projet-sur-github-1/les-bases-1)
* 3 [Apprendre à utiliser Git et GitHub | Cours Complet (2020)](https://www.pierre-giraud.com/git-github-apprendre-cours/)
* 4 [Générer des clés SSH pour Github](https://kinsta.com/fr/blog/generer-cles-ssh-github/)
* 5 [Complément d'information le livre Pro Git](https://git-scm.com/book/fr/v2)

# 1. Introduction à Linux
---

## 1.1 Linux

Le projet GNU n'est pas complet, il manque un noyau pour dialoguer avec le matériel de l'ordinateur, le noyau Hurd sera une tentative de concevoir une solution, mais qui sera pas opérationnel. Cette partie sera introduite par un finlandais du nom de Linus Torvalds en 1991 comme bénévole. Celui-ci va écrire un noyau à l'origine avec 10 000 lignes de code d'après le projet Minix. Le noyau [Linux](https://www.blaess.fr/christophe/articles/linux-histoire-dun-noyau/) fonctionne pour les architectures de processeur x86 et fait 64Ko une fois compressé. La version 0.0.1, disponible sur le visualisateur de [code source du noyau](https://elixir.bootlin.com/linux/0.01/source/kernel), était composé d'une cinquantaine d'appel système, c'est à dire la gestion de base pour les processus, la mémoire et les fichiers. Ainsi le système d'exploitation sera finalisé par une fusion des projets GNU/Linux et l'arrivée d'interface graphique(GUI) comme le projet Debian. Une entreprise va rapidement entrée dans le jeu avec la fondation de Red Hat par Robert Young. C'est la naissance d'un éco-système économique commercial et communautaire. En 2021 il existe environ 15 600 développeurs du noyau qui ont contribué depuis 2005 et environ 1400 compagnies. Grâce a l'arrivée de Git il est possible de tracer les contributions. Il est possible de devenir un "kernel dev" et de hacker le noyau. La [documentation](https://www.kernel.org/doc/html/latest/) pour contribuer pour le noyau est copieuse sur internet ainsi que des formations tel que chez la "Linux Foundation" gratuitement. Il faudra tout d'abord connaitre le langage C comme prérequis et être à l'aise avec Git.

## 1.2 Pas à pas

### Choisir une image ISO Live USB

On commence à apprendre doucement, on va utiliser des images ISO du système d'exploitation que l'on va installer sur le disque dur de l'ordinateur. Vous devez commencer à Googler sur internet comment accéder au BIOS / UEFI de votre ordinateur, en tapant le modèle. Il va être nécessaire de faire une manipulation, tel que désactiver le "secure boot" et "booter" sur une clé USB avec l'image ISO.

Entre temps, choisissez un logiciel pour graver l'image ISO du système d'exploitation sur une clé USB tels que:

* [Ventoy](https://www.ventoy.net/en/index.html)
* [Etcher](https://etcherpc.com/)
* [Rufus](http://rufus.ie/fr/)

Nous allons graver une image de la distribution [Xubuntu](https://xubuntu.org/download/) qui est une version alléger d'Ubuntu avec le bureau XFCE. Nous allons tout le temps utiliser ce bureau. Car il est facile à utiliser, léger et simple à installer, voir à customiser. Ainsi il fonctionne très bien sur des vieux ordinateurs. Il a l'avantage d'être une "Ubuntu" et donc le support associé en particulier la documentation. Suivez la procédure d'installation. Si vous êtes perdu il est temps d'aller sur la [documentation du wiki-fr](https://doc.ubuntu-fr.org/)

* N'oubliez pas de parcourir le [guide de débutant](https://doc.ubuntu-fr.org/debutant) pour la prise en main
* Suivez votre premier cours en ligne en [reprenant le contrôle sous GNU/Linux](https://openclassrooms.com/fr/courses/7170491-initiez-vous-a-linux?archived-source=43538)
* Cours De la Linux Foundation [Introduction à Linux](https://training.linuxfoundation.org/training/introduction-to-linux/)

### Lancer vous dans le LPIC

Pour une maîtrise des compétences sous GNU/Linux, rien de tel que le passage de la [certification LPIC](https://www.lpi.org/fr/our-certifications/summary-of-certifications) qui n'est pas trop cher. Ainsi trouvez-vous le livre(pirater-le s'il faut):

* [Préparation à la certification LPIC-1 Linux 101 et 102](https://www.editions-eni.fr/livre/linux-preparation-a-la-certification-lpic-1-examens-lpi-101-et-lpi-102-6e-edition-9782409024962)

Vous allez comme ça valider des bases:

* Package Manager
* Shell Scripting
* Gestion des disques
* Automatisation des tâches
* Sauvegardes
* Sécurité
* Gestion des utilisateurs et privilèges 
* Réseaux TCP/IP, SSH, DNS
* Monitoring

Cela fera de vous un administrateur système "sysAdmin" prêt pour une utilisation avancée du système d'exploitation. 

Pour allez plus loin:

* Linux Administration [https://linux.goffinet.org/](https://linux.goffinet.org/)
* [Pour aller plus loins avec la ligne de commande UNIX](https://archives.framabook.org/docs/Pour_aller_plus_loin_avec_la_ligne_de_commande/Pour_aller_plus_loin_avec_la_ligne_de_commande_art-libre.pdf)
* Langage de scripting: le Python dont le [livre de Gerard Swinnen](https://inforef.be/swi/download/apprendre_python3_5.pdf) comme base d'apprentissage

## 1.3 Distribution minimaliste

Petit tour d'horizon des meilleurs distribution minimaliste sous Linux. Pourquoi choisir le minimalisme? Car "Less is more", mais également plus vous réduisez l'inferface graphique GUI, plus vous apprenez avec la ligne de commande CLI. Mais encore?

* Permet de recycler des vieux PC, ou du reconditionné
* Peut s'utiliser comme ordinateur de secours en cas de panne du principal
* Idéal pour les débutants, moins de clics et de parasitage d'icones etc..., dans les interfaces minimalistes.


### Les Bureaux minimalistes.

Il y a plusieurs bureaux dans les distributions minimaliste. En règle générale:

Sous X.org:

* XFCE
* LXQT

CUSTOM (windows manager):

* Openbox
* i3
* Awesome

Sous Wayland:

* Sway
* hyprland

Des distributions sur-mesure comme Arch Linux ou Gentoo permet de choisir n'importe quel environnement à l'installation. Personnellement je suis sous XFCE, car j'ai mes habitudes et outils. 

### Les distributions

1. [#!++ CrunchbangPlusPlus](https://www.crunchbangplusplus.org/) - basé sur une minimale Debian et OpenBox
2. [Manjaro i3](https://manjaro.org/download/) - Basé sur Arch Linux avec i3
3. [Zorin OS lite](https://zorin.com/os/pro/#lite) - Dérivé d'Ubuntu sous XFCE
4. [Bodhi Linux](https://www.bodhilinux.com/) - Basé sur Ubuntu avec une surcouche graphique légère et stylé verte Moksha
5. [MX Linux](https://mxlinux.org/download-links/) - Basé sur Debian avec le bureau léger Fluxbox
6. [Lubuntu](https://lubuntu.me/) - Basé sous Ubuntu avec le bureau LXQT

## 1.4 Kernel Developpement

Mise à jours des ressources. Il vous faudra apprendre le langage C pour [explorer le code source](https://elixir.bootlin.com/linux/latest/source/kernel) du kernel Linux. Mais également c'est mieux d'avoir des compétences d'administrateur système. L'équipe de développeur de Greg K-H, le principal mainteneur du kernel Linux tourne sur Arch Linux.  

Vous trouverez une liste de livre \[PDF\] essentiel pour monter en compétence sur le kernel:  

```
git clone https://github.com/legoffant/book-kernelDev.git
```

  

Linux & Kernel  

*   How Linux Works  
    
*   Linux Kernel Development  
    
*   Understanding Linux Kernel  
    
*   Linux system programming  
    
*   Linux device drivers  
    
*   The Linux programming interface  
    

Langage C  

*   The C programming Language ANSI C  
    
*   Learn C The Hard Way  
    
*   C in the nutshell  
    
*   C programming for absolute beginner  
    
*   C pocket reference  
    

### Configurer son environnement  

Notre base va utiliser:  

*   Editeur de texte Vim/Neovim (autocompletion, ctags)  
    
*   Compilateur GCC  
    
*   Debugger GDB  
    
*   QEMU vm snapshot  
    
*   Buildroot  
    

Liens pour approfondir:  

*   [Prepare the environnment Linux kernel with QEMU](https://medium.com/@daeseok.youn/prepare-the-environment-for-developing-linux-kernel-with-qemu-c55e37ba8ade)  
    
*   [Linux kernel exploit development environnment](https://www.nullbyte.cat/post/linux-kernel-exploit-development-environment/)  
    

Autres ressources:  

*   [Kernel Hacking](https://www.kernel.org/doc/html/latest/kernel-hacking/)  
    
*   [Linux Insides](https://github.com/0xAX/linux-insides)  
    
*   [Kernel Newbies](https://kernelnewbies.org/)

## 1.5 Reverse Engineering

Très loin des scripts kiddies, totalement à l'opposer des outils qui suffit de maîtriser en quelques clics, le monde très obscure du Reverse Engineering de binaire. Avec les célèbres "[Obfuscation](https://code-garage.fr/blog/quest-ce-que-lobfuscation-de-code-et-a-quoi-ca-sert/)" dans le langage C. Bienvenue chez les fous et paranos de la sécurité informatique.  

Pour ce lancer dans le reverse engineering il faut des connaissances en langage C/C++ et en assembleur x86-64. Connaître des principes sur la construction de binaire et les compilateurs. Le principe est de faire de l'analyse lexicale, pré-traitement ( préprocesseur ), de l'analyse sémantique et syntaxique au plus proche du langage machine sachant que les ordinateurs utilisent pour le calcul la base hexadécimale.  

Les retro-ingénieurs sont utilisés dans tous domaine ou l'on a pas les plans de conception d'un produit tel qu'en mécanique et l'espionnage industriel ou sur le code source des programmes propriétaires. On appel souvent des crackers. C'est également le domaine de l'analyse de malware(Virus, Trojans, Botnet....) par rétro-conception pour apprendre à les créer, les améliorer ou s'en prévenir. Un domaine émergeant est la génétique sur l'ADN et les algorithmes. C'est de la retro-conception que de retrouver des fonctions de l'ADN ou de la mémoire des ancêtres enregistrée sur le support de stockage de l'information.  

Généralement les vulnérabilités 0-Days sont reportés par des retro-ingénieurs, ou des Kernel Hackers sous Linux. Tel que l'entreprise qui avait fait un peu de bruit à une époque sur l'espionnage et la vente de faille à la NSA: [Vupen](https://fr.wikipedia.org/wiki/Vupen)  

Les failles 0-Days peuvent ce négocier à des millions de dollars pour leur report et exploitation (ie: [The rise of millionaire zero-day exploit markets](https://securityaffairs.com/124690/cyber-crime/zero-day-exploit-markets.html))  

Par malchance, ce monde de l'élite des hackers est encore plus ultra-fermé en France car il n'y a pas de ressource d'apprentissage disponible en français. Vous ne trouverez aucune littérature francophone et éditeur avec des experts sur le sujet, et rare sont les formations académiques faisant une introduction dans leurs cours. C'est un monde d'autodidacte anglophone.  

Clairement, ce lancer dans la retro-ingénierie sous Linux, vous allez manger du ELF.  

J'ai sélectionner les meilleurs livres sur le sujet pour apprendre en autodidacte sur mon repo Git en PDF.  

Cela inclus:  

*   Practical reverse engineering, x86, x64, ARM, Windows Kernel, Reversing Tools, and Obfuscation  
    
*   Reversing: Secrets of Reverse Engineering  
    
*   Mastering Reverse Engineering  
    
*   Compilers: Principles, Techniques, and Tools (dragon book)  
    
*   The Linux programming interface  
    
*   Practical Malware Analysis, The Hands-On Guide to Dissecting Malicious Software  
    
*   The Shellcoder's Handbook: Discovering and Exploiting Security Holes  
    
*   Practical Binary Analysis, Build Your Own Linux Tools for Binary Instrumentation, Analysis, and Disassembly  
    
*   Hacking: The Art of Exploitation, 2nd Edition  
    
```
$ git clone https://github.com/legoffant/reverseengineering.git  
```

Je recommande par lire "Hacking: The Art of Exploitation" c'est une bonne introduction.

## 1.6 Apprendre les bases des commandes UNIX

Les commandes UNIX s'utilise dans le cadre de procédure avec le shell dans un terminal, c'est des outils basics pour intéragir avec le système en ligne de commande. Cela est particulièrement utile pour les programmeurs et la gestion de serveur, ou il n'y a pas d'interface graphique. Egalement cela permet d'optimiser la productivité et automatiser des tâches avec des scripts bash. Vous pouvez absolument tout controler depuis votre terminal. Ceci est une liste de 42 commandes essentiels sous UNIX. Cela est nécessaire pour tous débutant en informatique que la maitrise des lignes de commande dans un terminal.

* **vim**

Vim est l'outil basic d'éditeur de texte du programmeur, c'est votre meilleur allié, ça maitrise au départ est complexe avec son mode modal, mais on s'y fait avec le tutorial à lancer en ligne de commande `vimtutor`.

```
$ vim hello.c
```
Créer un fichier hello en langage C.

* **ls**

Affiche les informations sur les fichiers et les dossiers ainsi que les permissions d'accès

```bash
$ ls -la

total 3364
drwxr-xr-x 1 trivial trivial     206 28 juil. 20:31 .
drwxr-xr-x 1 trivial trivial     448 29 juil. 08:16 ..
-rwxr--r-- 1 trivial trivial   85344 28 juil. 19:33 hello
-rwxr--r-- 1 trivial trivial   85792 28 juil. 20:31 hello-gui
-rw-r--r-- 1 trivial trivial     116 28 juil. 20:31 hello-gui.red
-rw-r--r-- 1 trivial trivial     223 28 juil. 20:15 hello.red
-rw-r--r-- 1 trivial trivial  332088 28 juil. 19:32 libRedRT-defs.r
-rw-r--r-- 1 trivial trivial     414 28 juil. 19:33 libRedRT-extras.r
-rw-r--r-- 1 trivial trivial   69005 28 juil. 19:32 libRedRT-include.red
-rwxr--r-- 1 trivial trivial 1300352 28 juil. 19:33 libRedRT.so
-rwxr--r-- 1 trivial trivial 1551836 28 juil. 02:54 redc
```

* **pwd**

Affiche le dossier de travail

```bash
$ pwd

/home/trivial/red/src
```

* **cd**

Permet de naviguer dans les différents dossiers

Naviguer à la racine
```
$ cd /
```

Naviguer dans le dossier home
```
$ cd ~
```

Naviguer dans le dossier Documents
```
$ cd ~/Documents
```

Retourner au dossier parents
```
$ cd ..
```

* **mkdir**

Créer un nouveau dossier
```
$ mkdir sources
```
* **rmdir**

Supprimer un dossier
```
$ rmdir sources
```

* **rm**

Commande pour supprimer un fichier
```
$ rm fichier.txt
```

* **mv**

Commande pour bouger ou renomer un fichier
```
mv fichier1.txt fichier2.txt
```

* **cp**

Commande pour copier un fichier
```
$ cp fichier.txt fichierv2.txt
```

* **touch**

Créer un simple fichier vide brut ou avec une extension
```
$ touch fichier
```

* **cat**

Affiche le contenu d'un fichier
```bash
$ cat /etc/resolv.conf

# Generated by NetworkManager
nameserver 192.168.121.246
nameserver 2a04:cec0:c029:6580::b
```

* **clear**

Permet de nettoyer l'ecran du terminal
```
$ clear
```

* **echo**

Permet d'afficher dans un terminal
```bash
$ echo "hello world"

hello world
```

* **less**

Permet d'afficher des pages

* **man**

Commande d'aide et d'affichage du manuel
```bash
$ man sudo

SUDO(8)                              System Manager's Manual                                     SUDO(8)

NAME
       sudo, sudoedit — execute a command as another user

SYNOPSIS
[...]
```

* **uname**

Obtenir les informations basics sur l'OS
```bash
$ uname -a

Linux arch-t480 6.4.12-zen1-1-zen #1 ZEN SMP PREEMPT_DYNAMIC Thu, 24 Aug 2023 00:37:46 +0000 x86_64 GNU/Linux
```

* **whoami**

Connaitre l'utilisateur actif
```
$ whoami

trivial
```

* **tar**

Commande pour extraire et compresser des fichier sous Linux

Pour créer une archive tar
```
$ tar -cvf exempleArchive.tar /home/exempleArchive
```

* **grep**

Grep permet de chercher dans un fichier un pattern que nous définissons
```bash
cat fichier.txt | grep pattern
```

* **diff**

Permet d'afficher la différence entre deux fichiers

* **export**

Permet de créer des variables d'environnement et gérer le PATH
```bash
$ export myvar=5
$ echo $myvar
5
```

* **ssh**

Permet de ce connecter à un serveur distant sur le modèle "utilisateur"@"ip"
```
ssh trivial@83.13.145.56
```

* **git**

Outil de controle de version

* **ps**

Affiche les processus actifs
```
$ ps -aux

USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.0  23844  9972 ?        Ss   août29   0:21 /usr/lib/systemd/systemd --switched-root --syst
root           2  0.0  0.0      0     0 ?        S    août29   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        I<   août29   0:00 [rcu_gp]
```

* **kill**

Permet d'arrêter un processus via le PID
```
$ sudo kill 51
```

* **df**

vérifier l'espace disque
```
$ df -H

Sys. de fichiers       Taille Utilisé Dispo Uti% Monté sur
/dev/mapper/vg-arch      256G    102G  152G  41% /
devtmpfs                 4,2M       0  4,2M   0% /dev
tmpfs                    8,3G    319M  8,0G   4% /dev/shm
tmpfs                    3,4G    9,9M  3,3G   1% /run
tmpfs                    8,3G     81M  8,2G   1% /tmp
/dev/mapper/vg-arch      256G    102G  152G  41% /_snapshot
/dev/mapper/vg-arch      256G    102G  152G  41% /home
/dev/nvme0n1p1           535M    254M  282M  48% /boot
tmpfs                    1,7G    209k  1,7G   1% /run/user/1000
/dev/mapper/veracrypt1   349M    154M  172M  48% /mnt/veracrypt1
```

* **lsblk**

Affiche les partitions
```bash
$ lsblk -l

NAME                                      MAJ:MIN RM   SIZE RO TYPE  MOUNTPOINTS
loop0                                       7:0    0   366M  0 loop  
sda                                         8:0    1     0B  0 disk 
zram0                                     253:0    0     8G  0 disk  
luks-4779cffb-39d7-43a8-734e-5fff5180cff9 254:0    0   238G  0 crypt 
vg-arch                                   254:1    0   238G  0 lvm   /home
                                                                     /_snapshot
                                                                     /
veracrypt1_1                              254:2    0 365,8M  0 dm    
veracrypt1_0                              254:3    0 365,8M  0 dm    
veracrypt1                                254:4    0 365,8M  0 dm    /mnt/veracrypt1
nvme0n1                                   259:0    0 238,5G  0 disk  
nvme0n1p1                                 259:1    0   511M  0 part  /boot
nvme0n1p2                                 259:2    0   238G  0 part 
```


* **ip**

Commande pour manipuler les outils réseaux, routage, équipements et tunneling
```bash
$ ip addr

1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: enp0s31f6: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc fq_codel state DOWN group default qlen 1000
    link/ether e8:6a:64:8d:c0:4b brd ff:ff:ff:ff:ff:ff
3: wlp3s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether 50:76:af:2c:e2:42 brd ff:ff:ff:ff:ff:ff
    inet 192.168.121.196/24 brd 192.168.121.255 scope global dynamic noprefixroute wlp3s0
       valid_lft 2102sec preferred_lft 2102sec
    inet6 2a04:cec0:c020:6580:c031:c188:4cdb:66/64 scope global dynamic noprefixroute 
       valid_lft 6140sec preferred_lft 6140sec
    inet6 fe80::89aa:f14f:c341:2216/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
```

* **ping**

Outil réseau qui permet de ping la connexion à un site, état du réseau
```bash
$ ping www.google.fr

PING www.google.fr(par21s06-in-x03.1e100.net (2a00:1450:4007:813::2003)) 56 octets de données
64 octets de par21s06-in-x03.1e100.net (2a00:1450:4007:813::2003) : icmp_seq=1 ttl=111 temps=40.9 ms
64 octets de par21s06-in-x03.1e100.net (2a00:1450:4007:813::2003) : icmp_seq=2 ttl=111 temps=50.2 ms
^C
--- statistiques ping www.google.fr ---
2 paquets transmis, 2 reçus, 0% packet loss, time 1002ms
rtt min/avg/max/mdev = 40.920/45.561/50.203/4.641 ms
```

* **traceroute**

Traceroute est un outil de Linux qui vous permet d’étudier les itinéraires des paquets de réseau. Il peut vous aider à identifier le facteur limitant les parcours de paquets de réseau.
Traceroute est également utile pour dépanner des connexions de réseau lent en vérifiant le chemin empreinte par des paquets vers une destination.

```bash
$ traceroute www.google.fr

traceroute to www.google.fr (142.250.179.99), 30 hops max, 60 byte packets
 1  _gateway (192.168.121.246)  9.946 ms  9.825 ms  9.762 ms
 2  * * *
 3  * * *
 4  * * *
 5  * * *
 6  * * *
 7  * * *
 8  * * *
 9  * * *
10  * * *
11  * * *
12  * * *
13  * * *
14  * * *
15  * * *
16  * * *
17  * * *
18  * * *
19  * * *
20  * * *
21  * * *
22  * * *
23  * * *
24  * * *
25  * * *
26  * * *
27  * * *
28  * * *
29  * * *
30  * * *
```

* **wget**

Outil de téléchargement de fichier, ou de website tout entier avec une fonction récursive

* **ufw**

Le par-feu le plus simple d'utilisation

* **sudo**

Commande pour obtenir les droits administrateur

* **cal**

Afficher le calendrier
```bash
$ cal
               
   septembre 2023   
lu ma me je ve sa di
             1  2  3
 4  5  6  7  8  9 10
11 12 13 14 15 16 17
18 19 20 21 22 23 24
25 26 27 28 29 30 
```

* **date**

Affiche la date actuel
```
$ date

jeu. 07 sept. 2023 22:08:33 CEST
```
Affiche la date en seconde EPOCH UNIX
```
$ date +%s

1694117320
```

* **dd**

La commande dd permet de copier tout ou partie d'un disque − EN BON ÉTAT − par blocs d'octets, indépendamment de la structure du contenu du disque en fichiers et en répertoires. Exemple réaliser une image .iso d'un cd.
```bash
$ dd if=/dev/hdc of=/home/${USER}/moncd.iso bs=2048 conv=notrunc
```

Cette commande est utile pour graver des .iso vers des clés USB plus particulièrement.

* **whereis**

Permet de localiser un binaire executable
```
$ whereis ruby

ruby: /usr/bin/ruby /usr/lib/ruby /usr/share/man/man1/ruby.1.gz
```


* **locate et find**

Recherche de fichier

* **top**

Outil de monitoring, affiche les processus, espace disque, état de la charge mémoire, des CPU

* **passwd**

Commande pour changer de mot de passe à un utilisateur
```
$ passwd trivial
```

* **chown**

Gestion de la propriété des fichiers et répertoires. L’utilisation correcte de la commande chown peut empêcher les utilisateurs indésirables d’apporter des modifications à vos fichiers et contribuer à les protéger des personnes extérieures.

* **shutdown**

Permet d'éteindre l'ordinateur
```
$ sudo shutdown now
```

* **chmod**

Rendre executable un script ou un fichier
```
$ sudo chmod +x monScript.sh
```

Sinon pour en savoir plus: [Unix. Pour aller plus loin avec la ligne de commande PDF](https://archives.framabook.org/unixpou-allerplusloinaveclalignedecommande/index.html)


# 2. Installation d'Arch Linux
---

## 2.1 Keep it simple, stupid

Allons, présenter Arch Linux dans cette section qui le système d'exploitation que l'on va manipuler. Un système d'exploitation: OS est un logiciel qui permet la communication entre le matériel de l'ordinateur et les applications. La gestion du matériel est faite par le noyau ou kernel à cela on ajoute une couche graphique ou GUI pour simplifier les tâches avec l'utilisateur.

Ce qui peu choquer en première approche: il n'y a pas durant l'installation d'Arch Linux d'interface graphique. Tout est fait par la ligne de commande et en réalité c'est le meilleur moyen d'apprendre Linux. Vous n'êtes pas seulement un utilisateur du système d'exploitation, mais vous devenez un administrateur de système. Vous allez acquérir une base solide en informatique comment fonctionne le système d'exploitation.

Ainsi de plus en plus d'utilisateurs de Linux choisissent Arch Linux pour la finesse du paramètrage de la distribution, dans le sens que rien n'est caché à l'utilisateur, il est impossible de mettre du code malveillant dans une installation de base car le code est open source. Pour des personnes qui on un soucis de la vie privée et de la confidentialité, savoir que l'on n'est pas tracké par son outil de travail ou loisir est un facteur important. 

Les hackers choisissent le meilleur matériel pour opérer dans le cyberespace dans le sens qu'ils sont capable de laisser le moindre trace possible de leur action. L'information doit être protégée, si un hacker fait une enquête sur un individu ou une entreprise et collecte de l'information, cela ne doit pas fuiter, ni ces contrats commerciaux pour remonter au client. Même la NSA qui est l'organisme de renseignement le plus intrusive n'à pas à connaitre les activités d'un hacker. Vous devenez un sous-marin dans le cyberespace. Le choix du système d'exploitation devient centrale.

Ce que propose Arch Linux, mais egalement Gentoo est de partir *from scratch* pour monter soit même son système tel un Légo. Vous voulez pouvoir personnaliser la configuration, alors faites-le vous même. Gentoo est très utilisé chez les hackers russes, certain dirait que c'est trop old school, mais compiler soit même les sources est une garantie de garder le contrôle sur l'outil informatique. Après c'est une affaire d'école et de philosophie que de choisir Gentoo ou Arch voir du purisme.Certain ont entendu parler de Kali Linux. Comme la distribution de choix pour les hackers. Ce n'est pas totalement vrai. Même si Linux est le choix de référence pour les hackers car 85% des malwares touchent Windows, il y a des distributions ou l'on peut entièrement démonter et construire son système, et c'est très recherché par les hackers tels que Arch et Gentoo. Un hacker n'est pas seulement savoir utiliser des outils de hacking, il y a une véritable envie d'approfondir la connaissance en informatique en générale.

Nous allons aborder la philosophie KISS "Keep it simple, stupid", une expression empreinté à UNIX dans le jargon de l'informatique signifiant littéralement Faites Simple, Stupide et Restez-le. Dans ce sens Arch Linux emprunte le mot de la simplicité avant toute chose. Ainsi la simplicité selon Arch Linux c'est une conception sans complications (techniques), sans superflu et dont le code reste simple et élégant. 

Jamais Arch Linux ne prendra l'initiative de cacher ou d'interfacer des fonctionnalités ou des possibilités à l'utilisateur. Si un outil doit exister, la philosophie d'Arch Linux est de laisser son développemen aux auteurs du logiciel.

**Concrètement cela ce traduit par:**

* La configuration du système de base ce fait par des fichiers texte. Ceux-ci sont bien documentés et le moins nombreux possible.
* Le système de paquets ABS/pacman. Pacman est un gestionnaire de paquets simple qui stocke ses informations dans des fichiers et non des bases de données relationnelles. Les paquets sont produits par un simple script shell, makepkg.
* Les paquets sont réalisés avec un minimum de modifications aux sources fournies par l'auteur dont sa signature PGP est vérifiée: les seules corrections admises concernent les bugs et incompatibilités
* Le gestionnaire de pacman ne prend pas l'iniative de modifier ou mettre à jour vos fichiers de configuraion.

Apprendre Arch est plus difficile que les autres distributions GNU/Linux, cela peut paraître rude mais l'intérêt pédagogique de connaitre le fonctionnement du système offre des libertés ou l'utilisateur est en connaissance à chaques instant de son système.

Si nous devions définir une tendance Arch Linux appartient à la tendance du DIY (Do It Yourself) par cela traduire "à faire soit même". On fait confiance à l'utilisateur qui doit lui-même prendre des décisions.

Arch est une distribution communautaire. Cela veut dire que aucune entreprise n'est derrière la distribution, c'est un travail pour la plupart du temps bénévole par des développeurs de confiance.

La plupart des dépôts des binaires compilés à partir des sources sont des logiciels libres. Mais on peut trouver quelques logiciels propriétaires comme certain pilotes.

## 2.2 LxQt intégration Arch Install

Mise à jours en 2022 de mon installation d'Arch Linux avec quelques nouveautés en particulier la prise en charge de snapshot avec BTRFS.

Cette configuration rentre en compte dans mes projets d'entreprise et de formation à l'informatique cherchant le minimalisme. Le système tourne parfaitement sur mon Lenovo Thinkpad Helix de 2013 à 270€ Intel i5, 4GB RAM, 160GB SSD. Je peux lancer sans problème une machine virtuelle sous KVM, ou avoir < 10 onglets dans mon navigateur internet tout en ayant un flux video ou audio en streaming. C'est une machine de production stable avec le strict mininum à paramêtrer axé sur le minimalisme et la performance.

Ce qui fonctionne *out of the box*:
* Editeur de texte Neovim avec l'autocompletion,ctags du code en C/C++ et Python
* Oh My Zsh
* Synchro Cloud MEGA
* VPN Proton
* L'aide à l'écriture Manuskript
* Second cerveau Obsidian
* VScodium
* Calcul numérique avec les notebook Jupyter en Python
* Calcul Formel Sagemath
* Recherche en vulnérabilité et le repo Blackarch
* Interpréteur Ruby IRB
* Launcher Sinapse
* Machine virtuelle KVM et Virt-manager
* Gestion du par-feu ufw
* Navigateur Firefox
* Gestion de bibliothèque ebook avec calibre et bibliographie avec Zotero
* Editeur LaTex texmaker
* Editeur markdown Ghostwriter

Screenshot neofetch de la configuration: [https://imgur.com/a/cEecXob](https://imgur.com/a/cEecXob)

*Comme vous pouvez le constater au repos j'utilise 650MB de RAM sur 4GB.*

**Pour qui c'est destiné?**

* Les hackers
* Ingénieurs et dévéloppeurs informatique
* Chercheurs
* Ecrivains

**Peut-on faire du jeu-video?**

Installer Steam est possible, ou Minecraft, vous serez limité en ressource graphique.

```
yay -S minecraft-launcher
```

**Stack:**

* OS: [Arch Linux](https://archlinux.org/)
* Chiffrement: [dmcrypt-LUKS](https://fr.wikipedia.org/wiki/Dm-crypt)
* Bootloader: [systemd-boot](https://systemd.network/systemd-boot.html)
* Système de fichier: [BTRFS](https://fr.wikipedia.org/wiki/Btrfs)
* Shell: [Zsh](https://zsh.sourceforge.io/)
* Environnement: [LXQt](https://lxqt-project.org/)
* Windows Manager: [Open Box](http://openbox.org/wiki/Main_Page)
* Terminal: [QTerminal](https://github.com/lxqt/qterminal)
* Prompt: [Oh-My-Zsh](https://ohmyz.sh/)
* File Manager: [Ranger](https://ranger.github.io/) (term)
* Launcher: [Synapse](https://archlinux.org/packages/community/x86_64/synapse/)
* Virtualisation: [Virt-Manager QEMU/KVM](https://virt-manager.org/)
* Lecteur audio: [CMUS](https://cmus.github.io/) (term)
* Lecteur video: [Vlc](https://www.videolan.org/vlc/)
* IRC: [Weechat](https://weechat.org/) (term)
* Editeur de texte: [Neovim](http://neovim.io/) (term)
* Contrôle de version: [Git](https://git-scm.com/) (term)
* Notepad: [Leafpad](https://archlinux.org/packages/extra/x86_64/leafpad/)
* Calculatrice: [Galculator](https://archlinux.org/packages/community/x86_64/galculator/)
* P2P Torrent: [Qbittorrent](https://www.qbittorrent.org/)
* Navigateur internet: [Firefox](https://www.mozilla.org/fr/firefox/new/)
* Documentation langage: [Zeal](https://zealdocs.org/)
* Gestionnaire de mot de passe: [Keepass](https://keepass.info/)
* Client Serveur FTP: [Filezilla](https://filezilla-project.org/)
* Carte Mentale: [Freemind](https://freemind.fr.softonic.com/)
* Editeur d'image: [Gimp](https://www.gimp.org/)
* EDI Java: [Eclipse](https://www.eclipse.org/downloads/packages/release/kepler/sr1/eclipse-ide-java-developers)
* Compilateur: [GCC](https://gcc.gnu.org/)
* Interpréteur Ruby: [IRB](https://github.com/ruby/irb)
* Notebook Python: [Jupyter](https://jupyter.org/)
* Container chiffré: [Veracrypt](https://www.veracrypt.fr/code/VeraCrypt/)
* Outil d'écrivain: [Manuskript](https://www.theologeek.ch/manuskript/)
* Calcul formel: [SageMath](https://www.sagemath.org/fr/)
* Par-feu: [Gufw](http://gufw.org/)
* Sauvegarde: [Deja-dup](https://apps.gnome.org/fr/app/org.gnome.DejaDup/)
* Cloud: [MEGA](https://mega.nz/)
* VPN: [Proton](https://protonvpn.com/)
* Gestion bibliographique: [Zotéro](https://www.zotero.org/)
* Base de connaissance: [Obsidian](https://obsidian.md/)
* Editeur LaTex: [Texmaker](https://www.xm1math.net/texmaker/)
* Office: [Cryptpad](https://cryptpad.fr/)
* Flowchart & Diagram: [draw.io](https://www.draw.io/index.html)
* Documentation langage en ligne: [https://devdocs.io/](https://devdocs.io/)
* Social Bookmarking: [Pearltrees](https://www.pearltrees.com/)

Listes d'applications spécifique à la recherche de vulnérabilité:

* Exploration réseau et audit de sécurité: [nmap](https://nmap.org/)
* Collection de classe Python pour travailler avec les protocoles réseaux: [impacket](https://www.secureauth.com/labs/open-source-tools/impacket/)
* Outil d'analyse de protocoles réseaux: [wireshark](https://www.wireshark.org/)
* Capturer et analyser les packets sur le réseau: [tcpdump](https://www.tcpdump.org/)
* Outil de récupération de mot de passe: [hashcat](https://hashcat.net/hashcat/)
* Sécurité audit de mot de passe: [john](https://www.openwall.com/john/)
* Surfer anonymement via TOR ou un serveur proxy: [proxychains-ng](https://proxychains.sourceforge.net/)
* Base de donnée d'exploits [exploitdb](https://www.exploit-db.com/)
* Client HTTP CLI [httpie](https://httpie.io/)
* Framework d'audit de sécurité, développement d'exploits: [metasploit](https://www.metasploit.com/)
* Front-end GUI pour metasploit, aide à l'utilisation [armitage](https://www.offensive-security.com/metasploit-unleashed/armitage/)
* Bind outil d'administration DNS: [bind-tools]()
* Framework de retro-ingénierie et analyse de fichier binaire r2: [radare2](https://rada.re/n/radare2.html)
* Automatisation détection et exploitation injection SQL: [sqlmap](https://sqlmap.org/)
* Wordpress security scanner: [wpscan](https://wpscan.com/)
* Outil de copy/coller clipboard en CLI: [xclip]()
* Navigateur exploitation framework: [beef](https://beefproject.com/)
* Outils d'ingénierie sociale: [set](https://github.com/trustedsec/social-engineer-toolkit)
* DDoS service outils: [ufonet](https://ufonet.03c8.net/)
* Traffic capture implementation d'attaque de type man-in-the-middle: [ettercap](https://www.ettercap-project.org/index.html)
* Web Application Attack and Audit Framework: [w3af](http://w3af.org/)
* Vulnerability Assessment Scanner: [openvas](https://www.openvas.org/)
* Command and control server et agent post-exploitation HTTP/2 [Merlin](https://github.com/Ne0nd0g/merlin)


---

nota:  désactiver dans le bios le secure boot pour booter en USB.
Vérifier le démarrage UEFI.

### pre-check configuration 

Charger le clavier français en tapant "loqdkeys fr"
```
loadkeys fr
```

Verifier boot mode
```
ls /sys/firmware/efi/efivars    (Si le répertoire existe, l'ordinateur supporte l'efi)
```

### Connexion au réseau

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

### Check les disques

Vérifier le nom de votre disque dur ou SSD
```
lsblk
```

### Partitionnement

Destruction des données sécurisées du disque
```
shred -v -n 1 /dev/sda
```

Utilitaire de partitionnement
```
gdisk /dev/sda
```
Créer une nouvelle table de partition GPT

Mise en place de la table de partition:
```
/dev/sda1 EFI ef00 512MB
/dev/sda2 Linux 8300
```

Formatage de la partition EFI
```
mkfs.vfat -F32 -n BOOT /dev/sda1
```

### Chiffrement 
```
cryptsetup --align-payload 8192 --type luks2 --pbkdf argon2id --verify-passphrase luksFormat /dev/sda2
```

Ouverture du container chiffré:
```
cryptsetup luksOpen --allow-discards /dev/sda2 root
```

### Systèmes de fichiers

```
# Initialize un groupe physique de volume LVM
pvcreate --dataalignment 4M /dev/mapper/root

# Initialise un groupe virtuel attaché au groupe physique
vgcreate vg /dev/mapper/root

# Initialise une partition nommée 'arch' dans le volume group 'vg'
$ lvcreate -l +100%FREE vg -n arch

# Affiche les volumes logiques créés
$ lvdisplay
```

Formater la partition root
```
mkfs.btrfs -KL ARCH /dev/mapper/vg-arch
```

Monter les partitions:
```
mount /dev/mapper/vg-arch /mnt
cd /mnt
```

Créer les subvolumes
```
btrfs subvolume create @
btrfs subvolume create @home
```

Démonter la partition
```
umount /mnt
```

Remonter le subvolume @
```
mount -o noatime,space_cache=v2,compress=zstd,ssd,subvol=@ /dev/mapper/vg-arch /mnt
```

Créer les dossiers boot et home
```
mkdir /mnt/{boot,home}
```

Monter le subvolume @home
```
mount -o noatime,space_cache=v2,compress=zstd,ssd,subvol=@home /dev/mapper/vg-arch /mnt/home
```

Monter la partition EFI
```
mount /dev/sda1 /mnt/boot
```


### Système de base
```
pacstrap /mnt base linux linux-firmware btrfs-progs git lvm2 vim intel-ucode
```

Générer fstab
```
genfstab -L -p /mnt >> /mnt/etc/fstab
```

Chrooter l'environnement
```
arch-chroot /mnt
```

Nom de la machine
```
vim /etc/hostname
```
Configuration de local paramétrage des langues
```
vim /etc/locale.gen
en_US.UTF-8 UTF-8
fr_FR.UTF-8 UTF-8
```
Génération du fichier
```
locale-gen
```
Configuration des langues par defaut
```
vim /etc/locale.conf
LANG="fr_FR.UTF-8"
LC_COLLATE="fr_FR.UTF-8"
```
Exporter le langage actuel pour création dans initramfs
```
export LANG=fr_FR.UTF-8
```
Console, fonts, clavier azerty
```
vim /etc/vconsole.conf
KEYMAP=fr-pc
FONT=
FONT_MAP=
```

Assigne le fuseau horaire
```
ln -sf /usr/share/zoneinfo/Europe/Paris /etc/localtime 
```


```
hwclock --systohc
```

Editer mkinitcpio
```
vim /etc/mkinitcpio.conf
	BINARIES=(btrfsck)
	HOOKS=(base systemd autodetect keyboard sd-vconsole modconf block sd-encrypt sd-lvm2 fsck filesystems)

```

Générer initramfs
```
mkinitcpio -p linux
```

Mot de passe super-administrateur root
```
passwd
```

Installation de paquets supplémentaires:
```
pacman - S networkmanager network-manager-applet dialog wpa_supplicant reflector base-devel linux-headers avahi xdg-user-dirs xdg-utils gvfs gvfs-smb nfs-utils inetutils dnsutils cups hplip alsa-utils pipewire pipewire-alsa pipewire-pulse pipewire-jack pavucontrol bash-completion openssh rsync acpi acpi_call tlp ipset ufw sof-firmware nss-mdns acpid ntfs-3g terminus-font nano man-db man-pages zip p7zip unzip tar htop tmux wget pciutils lshw syslog-ng
```

Driver carte graphique, openGL, touchpad
```
pacman -S xf86-video-intel xf86-input-libinput
```

Installation de QEMU/KVM pour la virtualisation
```
pacman -S virt-manager qemu qemu-arch-extra edk2-ovmf bridge-utils dnsmasq vde2 openbsd-netcat
```

### Configuration de systemd-boot

```
bootctl --esp=/boot install
```

Configuration générale du chargeur

```
vim /boot/loader/loader.conf
default arch.conf
editor no
timeout 4
console-mode max
```

Récupérez le champs UUID= de la partition LUKS

```
blkid | grep /dev/sda2
```

Configuration d’une entrée du menu de démarrage.

```
vim /boot/loader/entries/arch.conf

title Arch Linux
linux /vmlinuz-linux
initrd <cpu>-ucode.img
initrd /initramfs-linux.img
options rd.luks.uuid=<UUID> rd.luks.options=discard root=/dev/mapper/vg-arch rootflags=subvol=@ rw
```

### Activer les services systemD

```
systemctl enable NetworkManager
systemctl enable cups.service
systemctl enable sshd
systemctl enable avahi-daemon
systemctl enable tlp
systemctl enable reflector.timer
systemctl enable libvirtd
systemctl enable acpid
systemctl enable ufw
```

### Créer un utilisateur

```
useradd -m trivial
passwd trivial
```

```
usermod -aG libvirt trivial
```

Ajout dans sudoers de l'utilisateur
```
echo "trivial ALL=(ALL) ALL" >> /etc/sudoers.d/trivial
```

Démonter et reboot
```
exit
umount -R /mnt
reboot
```

### Post-installation

Check ip adresse
```
ip a
```

Connexion au wifi via Networkmanager TUI
```
nmtui
```

Synchronisation repository MAJ
```
sudo pacman -Sy
```

Installation AUR Helper
```
mkdir sources 
cd sources 
git clone https://aur.archlinux.org/yay.git 
cd yay 
makepkg -si 
```

Installation de timeshift et zramd
```
yay -S timeshift-bin zramd
```

```
sudo systemctl enable zramd.service
sudo systemctl start zramd.service
```

Vérification que la swap est active:
```
lsblk -l
```

Configuration de reflector
```
reflector --verbose --country 'France' -l 50 -p https --sort rate --save /etc/pacman.d/mirrorlist
```

```
sudo pacman -Syy
```

### Installation du bureau LXQt

Installation environnement LXQt
```
sudo pacman -S xorg-server xorg-xinit sddm lxqt ranger
```

Activer le gestionnaire de démarrage
```
sudo systemctl enable sddm
```


Configuration de xinitrc
```
echo "exec startlxqt" > ~/.xinitrc
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


Installation de fonts
```
sudo pacman -S ttf-dejavu ttf-bitstream-vera adobe-source-han-sans-otc-fonts noto-fonts noto-fonts-emoji ttf-liberation ttf-droid tex-gyre-fonts
```

NOTA: Pour activer la prise en charge Pinyin, utiliser fcitx.

**Codec Multimédia**

Nous allons installer l’ensemble des greffons gstreamer qui est le framework utilisé par de nombreux environnements de bureau pour gérer le multimedia.
```
sudo pacman -S gst-plugins-{base,good,bad,ugly} gst-libav
```

Installation de navigateurs web
```
sudo pacman -S firefox
```

Extension essentiel sur Firefox:

* DuckDuckGo Privacy Essentials
* Smart HTTPS
* Disconnect
* U-Block Origin
* Privacy Badger

```
reboot
```

### Configuration des applications

#### Configuration de Oh-my-Zsh 

Install Zsh
```bash
$ yay -S zsh oh-my-zsh-git
```

Mettre zsh shell par default
```bash
$ chsh -l
$ chsh -s /usr/bin/zsh
```

Install et activer le thème powerlevel10k
```bash
$ yay -S --noconfirm zsh-theme-powerlevel10k-git
$ echo 'source /usr/share/zsh-theme-powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```

Install nerd fonds
```bash
yay -S nerd-fonts-complete
```

Fichier de configuration ~/.zshrc
```bash
# Enable Powerlevel10k instant prompt. Should stay close to the top of ~/.zshrc.
# Initialization code that may require console input (password prompts, [y/n]
# confirmations, etc.) must go above this block; everything else may go below.
if [[ -r "${XDG_CACHE_HOME:-$HOME/.cache}/p10k-instant-prompt-${(%):-%n}.zsh" ]]; then
  source "${XDG_CACHE_HOME:-$HOME/.cache}/p10k-instant-prompt-${(%):-%n}.zsh"
fi

# Path to your oh-my-zsh installation.
ZSH=/usr/share/oh-my-zsh/

export DEFAULT_USER="anth"
export TERM="xterm-256color"
export ZSH=/usr/share/oh-my-zsh
export ZSH_POWER_LEVEL_THEME=/usr/share/zsh-theme-powerlevel10k

source $ZSH_POWER_LEVEL_THEME/powerlevel10k.zsh-theme

plugins=(archlinux 
	bundler 
	docker 
	jsontools 
	vscode web-search 
	tig 
	gitfast 
	colored-man-pages
	colorize 
	command-not-found 
	cp 
	dirhistory 
	sudo
	zsh-syntax-highlighting
	zsh-autosuggestions) 
# /!\ zsh-syntax-highlighting and then zsh-autosuggestions must be at the end

source $ZSH/oh-my-zsh.sh

# Uncomment the following line to disable bi-weekly auto-update checks.
DISABLE_AUTO_UPDATE="true"

ZSH_CACHE_DIR=$HOME/.cache/oh-my-zsh
if [[ ! -d $ZSH_CACHE_DIR ]]; then
  mkdir $ZSH_CACHE_DIR
fi

source $ZSH/oh-my-zsh.sh
```

Cloner les repos de zsh-syntax-highlighting et zsh-autosuggestions

Dossier de travail: /usr/share/oh-my-zsh/customs/plugins

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git zsh-syntax-highlighting
```
redémarrer zsh

#### Outil de recherche et lanceur Sinapse basé sur Zeitgeist

Installation de synapse + configuration sur le raccourci superL
```
sudo pacman -S synapse
```

#### Application pour développeur et designer

```
sudo pacman -S keepass gimp vlc filezilla inkscape qbittorrent weechat cmus galculator neovim discord veracrypt kazam yt-dlp calibre obsidian neofetch leafpad
```

Documentation des langages
```
yay -S zeal
```
NOTA: Problème de lenteur de compilation de qt5-webkit

Installation des outils de développeurs C/C++, Clang, Python, Ruby
```
sudo pacman -S llvm clang python python-pip python-virtualenv nodejs npm ruby ruby-irb ctags
```

Installation de Jedi autocompletion pour python
```
pip install jedi
```

Editeur de texte VSCodium
```
yay - S vscodium-bin
```

Installation de Java Eclipse
```
sudo pacman -S jdk-openjdk
yay -S eclipse-java
```

Outil de mind mapping (java)
```
yay -S freemind
```

**Configuration de Neovim**

Installation du gestionnaire de plugin "vim-plug" cf: [https://github.com/junegunn/vim-plug](https://github.com/junegunn/vim-plug)
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```


init.vim
```
" Neovim configuration file init.vim
" author: Anthony J.R Le Goff legoff.ant@gmail.com
" date: 16th april 2022

:set number
:set autoindent
:set tabstop=4
:set shiftwidth=4
:set smarttab
:set softtabstop=4
":set mouse=a

call plug#begin() 

Plug 'tpope/vim-fugitive'
Plug 'tpope/vim-surround'
Plug 'scrooloose/nerdtree'
Plug 'scrooloose/syntastic'
Plug 'vim-airline/vim-airline'
Plug 'tomasr/molokai'
Plug 'raimondi/delimitmate'
Plug 'kien/ctrlp.vim'
Plug 'ryanoasis/vim-devicons'
Plug 'majutsushi/tagbar'
Plug 'neoclide/coc.nvim', {'branch': 'release'}

set encoding=UTF-8

call plug#end()

:set statusline+=%#warningmsg#
:set statusline+=%{SyntasticStatuslineFlag()}
:set statusline+=%*

:let g:syntastic_always_populate_loc_list = 1
:let g:syntastic_auto_loc_list = 1
:let g:syntastic_check_on_open = 1
:let g:syntastic_check_on_wq = 0

nnoremap <C-f> :NERDTreeFocus<CR>
nnoremap <C-n> :NERDTree<CR>
nnoremap <C-t> :NERDTreeToggle<CR>

nmap <C-r> :TagbarToggle<CR>
nmap <C-p> :CtrlP<CR>

:colorscheme molokai

let g:NERDTreeDirArrowExpandable="+"
let g:NERDTreeDirArrowCollapsible="~"

" air-line
let g:airline_powerline_fonts = 1


" :CocInstall coc-python
" :CocInstall coc-clangd
```

#### Outils de Hacking, pentesting, bug bounty, CTF

Installation de dépot BlackArch >> [https://blackarch.org/](https://blackarch.org/)
```
curl -O https://blackarch.org/strap.sh
sha1sum strap.sh # doit etre egal a 5ea40d49ecd14c2e024deecf90605426db97ea0c
sudo chmod +x strap.sh
sudo ./strap.sh
```

```
sudo pacman -S blackman
```
Vous pouvez installer tous les outils Blackarch via cette commande (recommandé):
```
sudo blackman -a
```
SINON Installer les outils un par un:

Installation des outils basics
```
sudo pacman -S nmap impacket wireshark-qt tcpdump ruby hashcat john proxychains-ng exploitdb httpie metasploit armitage bind-tools radare2 sqlmap wpscan xclip beef set ufonet ettercap w3af merlin-server

```
L'installation d'OpenVAS est un peu plus complexe, voir la page: [https://wiki.archlinux.org/title/OpenVAS](https://wiki.archlinux.org/title/OpenVAS)

Configuration WordLists
```
mkdir -p /usr/share/wordlists
wget -q https://github.com/danielmiessler/SecLists/raw/master/Passwords/Leaked-Databases/rockyou.txt.tar.gz -O /usr/share/wordlists/rockyou.txt.tar.gz
wget -q https://github.com/danielmiessler/SecLists/raw/master/Discovery/Web-Content/common.txt -O /usr/share/wordlists/common.txt
```

#### Outils pour écrivain et chercheur
```
sudo pacman -S ghostwriter pdfjs pandoc texmaker manuskript
```

Extension Grammalecte et gestion de bibliographie
```
yay -S zotero 
```

#### Calcul numérique et scientifique (remplace Matlab)

```
python -m pip install jupyter scipy numpy matplotlib pandas ipython
```

Calcul Formel
```
sudo pacman -S sagemath
```

### Sauvegarde

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

### Par-feu ufw

Activation des logs (très utile pour la suite) :
```
sudo ufw logging on
```

Rejet par défaut des connexions entrantes :
```
sudo ufw default deny incoming
```

Autorisation des connexions sortantes :
```
sudo ufw default allow outgoing
```

Recherchement des règles du pare-feu pour finir :
```
sudo ufw reload
```

### Services Cloud

Vous trouverez plusieurs services de cloud gratuit tels que qcloud, Google drive, Dropbox. Nous allons installer MEGA qui est plus sécurisé ques les autres offres de cloud, le service de l'entrepreneur Kim Dotcom a évolué sur les principes d'anonymat et de vie privée sur les données qui sont stocké sur son serveur depuis l'affaire de megaupload.

Aller sur le site [https://mega.io/desktop](https://mega.io/desktop)

Sélectionner Arch Linux et télécharger l'application.

Pour installer sélectionner le package via:
```
sudo pacman -U package
```

### Service VPN Proton

Configurer un VPN. Installer le metapackage sur AUR:
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

Pour créer un compte protonVPN: [https://protonvpn.com/free-vpn/linux/](https://protonvpn.com/free-vpn/linux/)

Pour voir le status de la connexion:
```
protonvpn-cli status
```

Vérifier que votre adresse IP pointe sur le VPN: [https://www.whatismyip.com/fr/](https://www.whatismyip.com/fr/)


## 2.3 hyprland intégration Arch Install

Mise à jours en 07/2023 de mon installation d'Arch Linux avec quelques nouveautés en particulier la prise en charge de snapshot avec BTRFS, modification container luks2, ajout kernel linux-zen, bureau hyprland.

Voila sur quoi je travail sur ma nouvelle installation d'Arch Linux en mode dev dans une VM sous Proxmox, avant de déployer sur mon thinkpad Helix. Tout fonctionne pour l'instant jusqu'à l'installation du bureau hyprland.

Ce qui est une grosse mise à jour de ma machine de production actuel > [code l'ancienne config sous LUKS + LVM + EXT4 + GRUB + XFCE + Zsh](https://gist.github.com/legoffant/8a7503430d2663549f982ea7f97622f3)

Inclus:

* Editeur de texte Neovim avec l'autocompletion,ctags du code en C/C++ et Python
* Shell Fish
* Synchro Cloud MEGA
* VPN Proton
* L'aide à l'écriture Manuskript
* Second cerveau Obsidian
* VScodium
* Calcul numérique avec les notebook Jupyter en Python
* Calcul Formel Sagemath
* Recherche en vulnérabilité et le repo Blackarch
* Interpréteur Ruby Pry via RVM
* Launcher fzf
* Machine virtuelle KVM et Virt-manager
* Gestion du par-feu ufw
* Navigateur Firefox
* Gestion de bibliothèque ebook avec calibre et bibliographie avec Zotero
* Editeur LaTex texmaker
* Editeur markdown Ghostwriter


**Pour qui c'est destiné?**

* Les hackers
* Ingénieurs et dévéloppeurs informatique
* Chercheurs
* Ecrivains

**Peut-on faire du jeu-video?**

Installer Steam est possible, ou Minecraft, vous serez limité en ressource graphique.

```
yay -S minecraft-launcher
```

**Stack:**

* OS: [Arch Linux](https://archlinux.org/)
* Chiffrement: [dmcrypt-LUKS](https://fr.wikipedia.org/wiki/Dm-crypt)
* Bootloader: [systemd-boot](https://systemd.network/systemd-boot.html)
* Système de fichier: [BTRFS](https://fr.wikipedia.org/wiki/Btrfs)
* Shell: [Fish](https://fishshell.com/)
* Windows Manager: [hyprland](https://hyprland.org/)
* Terminal: [Kitty](https://sw.kovidgoyal.net/kitty/)
* Prompt: [Starship.rs](https://starship.rs/)
* File Manager: [Broot](https://dystroy.org/broot/) (term)
* Launcher: [fzf](https://archlinux.org/packages/community/x86_64/synapse/) (term)
* Navigation rapide directory: [z](https://github.com/rupa/z) (term) 
* Historique intelligent: [mcFly](https://github.com/cantino/mcfly) (term)
* Corriger et fixer des erreurs, typos de la commande précédente: [thefuck](https://github.com/nvbn/thefuck) (term)
* Moderne replacement pour ls: [exa](https://github.com/ogham/exa) (term)
* cat clone avec coloration syntaxique et git integration : [bat](https://github.com/sharkdp/bat) (term)
* Disque monitoring: [duf](https://github.com/muesli/duf) (term)
* Outil de téléchargement supportant HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink: [aria2](https://aria2.github.io/) (term)
* Recherche récursive dans le directory à base de pattern de regex: [ripgrep](https://github.com/BurntSushi/ripgrep) (term)
* grep-like optimisé pour la recherche dans le code source: [ack3](https://github.com/beyondgrep/ack3) (term)
* Interactive monitoring des ressources, gestion des processus: [htop](https://htop.dev/) (term)
* Rapide et facile, outil de partage de fichier: [transfer.sh](https://transfer.sh/) (term)
* Virtualisation: [Virt-Manager QEMU/KVM](https://virt-manager.org/)
* Lecteur audio: [CMUS](https://cmus.github.io/) (term)
* Lecteur video: [Vlc](https://www.videolan.org/vlc/)
* Spotify TUI client: [spotify-tui](https://github.com/Rigellute/spotify-tui) (term) 
* Recherche et regarder des vidéos sur Youtube: [ytfzf](https://github.com/pystardust/ytfzf) (term)
* Télécharger de l'audio et des vidéos sur Youtube + d'autres sites: [yt-dlp](https://github.com/yt-dlp/yt-dlp) (term)
* Simple iptv player avec fuzzy finder: [IPTV](https://github.com/shahin8r/iptv) (term)
* Utilitaire pour rechercher et télécharger des liens torrents: [tordl](https://github.com/X0R0X/cli-torrent-dl) (term)
* IRC: [Weechat](https://weechat.org/) (term)
* Editeur de texte: [Neovim](http://neovim.io/) (term)
* Contrôle de version: [Git](https://git-scm.com/) (term)
* Commande Git TUI: [lazygit](https://github.com/jesseduffield/lazygit) (term)
* Extension ligne de commande Git intégrant Github: [hub](https://hub.github.com/) (term)
* Interface de monitoring de container Docker: [ctop](https://github.com/bcicen/ctop) (term) 
* Management des containers Dockers et services: [dockly](https://github.com/lirantal/dockly) (term) 
* HTTP Client pour les API: [HTTPie](https://github.com/httpie/httpie) (term) 
* Rapide prise de note: [terminal velocity](https://vhp.github.io/terminal_velocity/) (term)
* SSH + VPN connexion: [xiringuito](https://github.com/ivanilves/xiringuito) (term)
* User-friendly détails et statistiques de sockets TUI: [neoss](https://github.com/PabloLec/neoss) (term)
* Analyseur de packet réseau: [wireshark-cli](https://archlinux.org/packages/?name=wireshark-cli) (term)
* Force TCP connection avec un proxy utilisant TOR, SOCK, HTTP: [proxychains](https://github.com/haad/proxychains) (term)
* Outil de diagnostique réseau: [mtr](https://github.com/traviscross/mtr) (term)
* TUI Client pour Network Manager pour configurer le réseau: [nmtui](https://wiki.archlinux.org/title/NetworkManager) (term)
* Notepad: [Mousepad](https://archlinux.org/packages/extra/x86_64/mousepad/)
* Calculatrice: [Galculator](https://archlinux.org/packages/community/x86_64/galculator/)
* P2P Torrent: [Deluge](https://deluge-torrent.org/)
* Navigateur internet: [Firefox](https://www.mozilla.org/fr/firefox/new/)
* Documentation langage: [Zeal](https://zealdocs.org/)
* Gestionnaire de mot de passe: [Keepass](https://keepass.info/)
* Client Serveur FTP: [Filezilla](https://filezilla-project.org/)
* Carte Mentale: [Freemind](https://freemind.fr.softonic.com/)
* Editeur d'image: [Gimp](https://www.gimp.org/)
* EDI Java: [Eclipse](https://www.eclipse.org/downloads/packages/release/kepler/sr1/eclipse-ide-java-developers)
* Compilateur: [GCC](https://gcc.gnu.org/)
* Interpréteur Ruby: [IRB](https://github.com/ruby/irb)
* Notebook Python: [Jupyter](https://jupyter.org/)
* Container chiffré: [Veracrypt](https://www.veracrypt.fr/code/VeraCrypt/)
* Outil d'écrivain: [Manuskript](https://www.theologeek.ch/manuskript/)
* Calcul formel: [SageMath](https://www.sagemath.org/fr/)
* Par-feu: [Gufw](http://gufw.org/)
* Sauvegarde: [Deja-dup](https://apps.gnome.org/fr/app/org.gnome.DejaDup/)
* Cloud: [MEGA](https://mega.nz/)
* VPN: [Proton](https://protonvpn.com/)
* Gestion bibliographique: [Zotéro](https://www.zotero.org/)
* Base de connaissance: [Obsidian](https://obsidian.md/)
* Wiki local: [Zim](https://www.zim-wiki.org/index.html)
* Editeur LaTex: [Texmaker](https://www.xm1math.net/texmaker/)
* Office: [Cryptpad](https://cryptpad.fr/)
* Flowchart & Diagram: [draw.io](https://www.draw.io/index.html)
* Documentation langage en ligne: [https://devdocs.io/](https://devdocs.io/)
* Social Bookmarking: [Pearltrees](https://www.pearltrees.com/)
* Explication détaillée d'une ligne de commande: [explainshell](https://www.explainshell.com/) 
* Construit, test et debug des expressions régulières: [Regex101](https://regex101.com/) 
* Gestion communautaire de man pages: [tldr](https://tldr.sh/) (term)
* Réponse instantannée à propos du code: [howdoi](https://github.com/gleitz/howdoi) (term) 
* Construction communautaire de docs et cheatsheet, tous langages et frameworks: [wat](https://github.com/dthree/wat) 
* Outil interactif cheatsheet [navi](https://github.com/denisidoro/navi) 
* Recherche dans stack overflow quand une erreur ou une exception est levé dans le code à la compilation: [rebound](https://github.com/shobrook/rebound)
* Utiliser chatGPT via l'API d'OpenAI: [chatGPT-cli](https://github.com/0xacx/chatGPT-shell-cli) & [gpt-cli](https://github.com/kharvd/gpt-cli) (term)
* Surveiller le marché des cryptomonnaies: [cointop](https://github.com/cointop-sh/cointop) (term) 
* Maths calculateur, calcul symbolique, matrice, équation: [Qalculate](https://github.com/Qalculate/libqalculate) (term)
* Sauvegarde chiffrée à distance (cloud service, NAS, etc): [rclone](https://rclone.org/) (term)
* Enregistrement de session terminal: [asciinema](https://asciinema.org/) (term) 
* Un terminal façon Matrix: [cmatrix](https://github.com/matriex/cmatrix) (term)
* Generateur de bannière ASCII Art: [figlet](http://www.figlet.org/) (term) 
* Information sur le système: [neofetch](https://github.com/dylanaraps/neofetch) (term)
* Recherche les informations de l'architecture du CPU: [cpufetch](https://github.com/Dr-Noob/cpufetch) (term)
* Partage de terminal: [duckly](https://duckly.com/)
* Encodage de gifs: [gifski](https://gif.ski/)


Listes d'applications spécifique à la recherche de vulnérabilité:

* Exploration réseau et audit de sécurité: [nmap](https://nmap.org/)
* Collection de classe Python pour travailler avec les protocoles réseaux: [impacket](https://www.secureauth.com/labs/open-source-tools/impacket/)
* Outil d'analyse de protocoles réseaux: [wireshark](https://www.wireshark.org/)
* Capturer et analyser les packets sur le réseau: [tcpdump](https://www.tcpdump.org/)
* Outil de récupération de mot de passe: [hashcat](https://hashcat.net/hashcat/)
* Sécurité audit de mot de passe: [john](https://www.openwall.com/john/)
* Surfer anonymement via TOR ou un serveur proxy: [proxychains-ng](https://proxychains.sourceforge.net/)
* Base de donnée d'exploits [exploitdb](https://www.exploit-db.com/)
* Client HTTP CLI [httpie](https://httpie.io/)
* Framework d'audit de sécurité, développement d'exploits: [metasploit](https://www.metasploit.com/)
* Front-end GUI pour metasploit, aide à l'utilisation [armitage](https://www.offensive-security.com/metasploit-unleashed/armitage/)
* Bind outil d'administration DNS: [bind-tools]()
* Framework de retro-ingénierie et analyse de fichier binaire r2: [radare2](https://rada.re/n/radare2.html)
* Automatisation détection et exploitation injection SQL: [sqlmap](https://sqlmap.org/)
* Wordpress security scanner: [wpscan](https://wpscan.com/)
* Outil de copy/coller clipboard en CLI: [xclip]()
* Navigateur exploitation framework: [beef](https://beefproject.com/)
* Outils d'ingénierie sociale: [set](https://github.com/trustedsec/social-engineer-toolkit)
* DDoS service outils: [ufonet](https://ufonet.03c8.net/)
* Traffic capture implementation d'attaque de type man-in-the-middle: [ettercap](https://www.ettercap-project.org/index.html)
* Web Application Attack and Audit Framework: [w3af](http://w3af.org/)
* Vulnerability Assessment Scanner: [openvas](https://www.openvas.org/)
* Command and control server et agent post-exploitation HTTP/2 [Merlin](https://github.com/Ne0nd0g/merlin)


---

nota:  désactiver dans le bios le secure boot pour booter en USB.
Vérifier le démarrage UEFI.

### pre-check configuration 

Charger le clavier français en tapant "loqdkeys fr"
```bash
$ loadkeys fr
```

Verifier boot mode
```bash
$ ls /sys/firmware/efi/efivars    (Si le répertoire existe, l'ordinateur supporte l'efi)
```

### Connexion au réseau

Vérifier le nom du reseau et si celui-ci est up
```bash
$ ip addr show
```

vérifier la connexion internet
```bash
$ ping -c 2 google.com
```

Connexion au wifi
```bash
$ iwctl
```
affichage du prompt [IWD]#
```text
[iwd]# device list
[iwd]# station device scan
[iwd]# station device get-networks
[iwd]# station device connect SSID
```

MAJ
```bash
$ sudo mount -o rw,remount /
$ reflector --verbose --country 'France' -l 50 -p https --sort rate --save /etc/pacman.d/mirrorlist
$ pacman -Syu
```

### Check les disques

Vérifier le nom de votre disque dur ou SSD (ie sda ou NVME)
```bash
lsblk
```

### Partitionnement

Destruction des données sécurisées du disque
```bash
$ shred -v -n 1 /dev/sda
```

Utilitaire de partitionnement
```bash
$ gdisk /dev/sda
```

Commande gdisk:

1. o (écrire table de partition GPT)
2. n (nouvelle partition), default, 512MB, ef00
3. n (nouvelle partition), default, default, 8300
4. w (écrire et quitter)

Mise en place de la table de partition:
```text
/dev/sda1 EFI ef00 512MB
/dev/sda2 Linux 8300
```

Formatage de la partition EFI
```bash
$ mkfs.vfat -F32 -n BOOT /dev/sda1
```

### Chiffrement 
```bash
$ cryptsetup --type luks2 --cipher aes-xts-plain64 --key-size 512 --pbkdf argon2id --use-random --verify-passphrase luksFormat /dev/sda2
```

Ouverture du container chiffré:
```bash
$ cryptsetup luksOpen /dev/sda2 cryptlvm
```

### Systèmes de fichiers

```bash
# Initialize un groupe physique de volume LVM
$ pvcreate --dataalignment 4M /dev/mapper/cryptlvm

# Initialise un groupe virtuel attaché au groupe physique
$ vgcreate vg /dev/mapper/cryptlvm

# Initialise une partition nommée 'arch' dans le volume group 'vg'
$ lvcreate -l +100%FREE vg -n arch

# Affiche les volumes logiques créés
$ lvdisplay
```

Formater la partition root
```bash
$ mkfs.btrfs -KL ARCH /dev/mapper/vg-arch
```

Monter les partitions:
```bash
$ mount /dev/mapper/vg-arch /mnt
```

Créer les subvolumes
```bash
$ btrfs subvolume create /mnt/@
$ btrfs subvolume create /mnt/@home
$ btrfs subvolume create /mnt/@_snapshot
$ brtfs subvolume list /mnt
```

Démonter la partition
```bash
$ cd /
$ umount /mnt
```

Remonter le subvolume @
```bash
$ mount -o noatime,space_cache=v2,compress=zstd,ssd,subvol=@ /dev/mapper/vg-arch /mnt
```

Créer les dossiers boot et home
```bash
$ mkdir -p /mnt/{home,_snapshot}
$ lsblk -l
```

Monter le subvolume @home
```bash
$ mount -o noatime,space_cache=v2,compress=zstd,ssd,subvol=@home /dev/mapper/vg-arch /mnt/home
```

Monter le subvolume @_snapshot
```bash
$ mount -o noatime,space_cache=v2,compress=zstd,ssd,subvol=@_snapshot /dev/mapper/vg-arch /mnt/_snapshot
```

Créer et Monter la partition EFI
```bash
$ mkdir -p /mnt/boot
$ mount /dev/sda1 /mnt/boot
```


### Système de base
```bash
$ pacstrap /mnt base base-devel linux-zen linux-firmware btrfs-progs sudo git linux-tools lvm2 cryptsetup vim intel-ucode fwupd
```

Générer fstab
```bash
$ genfstab -L -p /mnt >> /mnt/etc/fstab
```

Chrooter l'environnement
```bash
$ arch-chroot /mnt
```

Nom de la machine
```bash
$ echo archbox > /etc/hostname
```

Edit `/etc/hosts`:

```text
127.0.0.1		localhost
::1					localhost
127.0.1.1		archbox.localdomain	archbox
```


Configuration de local paramétrage des langues
```bash
$ vim /etc/locale.gen
en_US.UTF-8 UTF-8
fr_FR.UTF-8 UTF-8
```
Génération du fichier
```bash
$ locale-gen
```
Configuration des langues par defaut
```bash
$ vim /etc/locale.conf
LANG="fr_FR.UTF-8"
LC_COLLATE="fr_FR.UTF-8"
```
Exporter le langage actuel pour création dans initramfs
```bash
$ export LANG=fr_FR.UTF-8
```
Console, fonts, clavier azerty
```bash
$ vim /etc/vconsole.conf
KEYMAP=fr-pc
FONT=
FONT_MAP=
```

Assigne le fuseau horaire
```bash
$ ln -sf /usr/share/zoneinfo/Europe/Paris /etc/localtime 
```


```bash
$ hwclock --systohc
```

Editer mkinitcpio
```bash
$ vim /etc/mkinitcpio.conf
```

```text	
	HOOKS=(base systemd autodetect keyboard sd-vconsole modconf block sd-encrypt sd-lvm2 btrfs filesystems)
	Si VM virtIO MODULES=(virtio virtio_blk virtio_pci virtio_net)
```

Générer initramfs
```bash
$ mkinitcpio -p linux-zen
```

Mot de passe super-administrateur root
```bash
$ passwd
```

Installation de paquets supplémentaires:
```bash
$ pacman - S networkmanager network-manager-applet dialog wpa_supplicant reflector linux-zen-headers avahi xdg-user-dirs xdg-utils gvfs nfs-utils inetutils dnsutils cups hplip bash-completion openssh rsync acpi acpi_call tlp ipset ufw sof-firmware nss-mdns acpid ntfs-3g terminus-font nano man-db man-pages zip p7zip unzip tar htop tmux wget pciutils lshw syslog-ng ntp 
```

Configuration de NTP:
```bash
$ vim /etc/ntp.conf
```

```text
server 0.fr.pool.ntp.org iburst
server 1.fr.pool.ntp.org iburst
server 2.fr.pool.ntp.org iburst
server 3.fr.pool.ntp.org iburst
```

Driver carte graphique, openGL, touchpad
```bash
$ pacman -S xf86-video-intel xf86-input-libinput mesa
```

Installation de QEMU/KVM pour la virtualisation
```bash
$ pacman -S virt-manager qemu qemu-arch-extra edk2-ovmf bridge-utils dnsmasq vde2 openbsd-netcat
```

### Configuration de systemd-boot

```bash
$ bootctl --esp=/boot install
```

Configuration générale du chargeur

```bash
$ vim /boot/loader/loader.conf
```

```text
default arch.conf
editor no
timeout 4
console-mode max
```

Récupérez le champs UUID= de la partition LUKS

```bash
$ blkid | grep /dev/sda2
```

Configuration d’une entrée du menu de démarrage.

```bash
$ vim /boot/loader/entries/arch.conf
```

```text
title Arch Linux
linux /vmlinuz-linux-zen
initrd <cpu>-ucode.img
initrd /initramfs-linux-zen.img
options rd.luks.uuid=<UUID> root=/dev/mapper/vg-arch rootflags=subvol=@ rw
```

### Activer les services systemD

```bash
$ systemctl enable NetworkManager
$ systemctl enable cups
$ systemctl enable sshd
$ systemctl enable avahi-daemon
$ systemctl enable tlp
$ systemctl enable reflector.timer
$ systemctl enable libvirtd
$ systemctl enable acpid
$ systemctl enable ufw
$ systemctl enable syslog-ng@default
$ systemctl enable ntpd
```

### Créer un utilisateur

```bash
$ useradd -mG storage,wheel,power -s /bin/bash trivial
$ passwd trivial
```

```bash
$ usermod -aG libvirt trivial
```

Ajout dans sudoers de l'utilisateur
```bash
$ echo "trivial ALL=(ALL) ALL" >> /etc/sudoers.d/trivial
```

Démonter et reboot
```bash
$ exit
$ umount -R /mnt
$ reboot
```

### Post-installation

Check ip adresse
```bash
$ ip a
```

Connexion au wifi/ethernet via Networkmanager TUI
```bash
$ nmtui
```

Synchronisation repository MAJ + reflector

Activer multilib et communauty:
```bash
$ sudo vim /etc/pacman.conf
```

```text
[community]
Include = /etc/pacman.d/mirrorlist

[multilib]
Include = /etc/pacman.d/mirrorlist
```

```bash
$ sudo reflector --verbose --country 'France' -l 50 -p https --sort rate --save /etc/pacman.d/mirrorlist

$ sudo pacman -Syu
```

Installation AUR Helper
```bash
$ mkdir sources 
$ cd sources 
$ git clone https://aur.archlinux.org/yay.git 
$ cd yay 
$ makepkg -si 
```

Installation de timeshift et zramd
```bash
$ yay -S timeshift-bin zramd
```

```bash
$ sudo systemctl enable zramd.service
$ sudo systemctl start zramd.service
```

Vérification que la swap est active:
```bash
$ lsblk -l
```


### Configuration de hyprland 

Post-installation:

Prérequis avoir `base-devel`, `git` et `wget`

Listing des packages et dépendances:
```bash
$ yay -S hyprland waybar-hyprland eww-wayland mako swaybg \
         kitty fish starship z fzf mclfy neovim broot \
         pipewire wireplumber \
         cliphist grimblast-git ffmpeg wf-recorder viewnior \
         polkit-kde-agent xdg-desktop-portal-hyprland-git \
         qt5-wayland qt6-wayland \
         wlogout swaylock-effects ly \
         webcord weechat fractal \
         cmus spotify-tui vlc ytfzf-git mpv haxor-news \
         cmatrix neofetch \
         ripgrep exa bat duf thefuck aria2 ack transfer.sh \
         lazygit hub ctop dockly httpie \
         xiringuito neoss mtr \
         howdoi tldr navi rebound \
         python python-pip python-virtualenv \
         firefox obsidian mousepad \
         adobe-source-han-sans-otc-fonts ttf-droid ttf-dejavu noto-fonts noto-fonts-emoji nerd-fonts-meta \
         gtk-cyberpunk-neon-theme-git \
         fcitx-im \
         udiskie \
         cointop libqalculate rclone asciinema figlet cpufetch gifski \
```

Installation de youtube-dl:
```bash
$ pip install yt-dlp
```

Installation de terminal velocity
```bash
$ pip install terminal_velocity

```

Installation IPTV:
```bash
$ sudo wget https://raw.githubusercontent.com/shahin8r/iptv/master/iptv -qO /usr/local/bin/iptv && sudo chmod +x /usr/local/bin/iptv

### Run playlist:

$ iptv https://raw.githubusercontent.com/Free-TV/IPTV/master/playlist.m3u8
```

Configurer Tordl:
```bash
$ git clone https://github.com/X0R0X/cli-torrent-dl.git
$ cd ~/cli-torrent-dl
$ ./setup.sh

# configurer client torrent (deluge)
$ nano ~/.config/torrentdl/config.json

```
Autostart authentification agent:
```bash
$ exec-once=/usr/lib/polkit-kde-authentication-agent-1
```

Activer le service au démarrage ly:
```bash
$ sudo systemctl enable ly.service
```

Configurer fish comme shell par défault:
```bash
$ echo /bin/fish | sudo tee -a /etc/shells
$ chsh -s /bin/fish
```

Editer fichier de configuration:
```bash
$ nvim ~/.config/hypr/hyprland.conf
```

Lancer automatiquement le montage USB, etc:
```text
exec-once = udiskie &
```
Clavier configuration ajouter:
```text
device:nom-clavier {
    kb_layout=fr,us
}
```

Commande pour switcher entre les claviers:
```bash
$ hyprctl switchxkblayout nom-clavier fr
```


NOTA: Pour activer la prise en charge Pinyin, utiliser fcitx.

**Codec Multimédia**

Nous allons installer l’ensemble des greffons gstreamer qui est le framework utilisé par de nombreux environnements de bureau pour gérer le multimedia.
```bash
$ sudo pacman -S gst-plugins-{base,good,bad,ugly} gst-libav
```

Extension essentiel sur Firefox:

* DuckDuckGo Privacy Essentials
* Smart HTTPS
* Disconnect
* U-Block Origin
* Privacy Badger

```
$ reboot
```

### Configuration des applications

#### Application pour développeur et designer

```bash
$ sudo pacman -S keepass gimp vlc filezilla inkscape deluge deluge-gtk galculator veracrypt kazam calibre
```

Embedded (microcontroller, AVR, etc...) - Pour utiliser Arduino et PlatformIO, installer et configurer:

* arduino-cli
* arduino-ide-bin (AUR)
* platformio (AUR)


Documentation des langages
```bash
$ yay -S zeal
```
NOTA: Problème de lenteur de compilation de qt5-webkit

Installation des outils de développeurs C/C++, Clang, Ruby
```bash
$ sudo pacman -S llvm clang nodejs npm ctags
```
RVM Ruby
```bash
$ sudo gpg --keyserver keyserver.ubuntu.com --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

$ \curl -sSL https://get.rvm.io | bash -s stable --ruby --gems=pry

### Verifier l'installation dans le terminal 
$ source /etc/profile.d/rvm.sh

### Install Gems
$ gem install <gems>

### Integration avec fish

$ curl -L --create-dirs -o ~/.config/fish/functions/rvm.fish https://raw.github.com/lunks/fish-nuggets/master/functions/rvm.fish

$ echo "rvm default" >> ~/.config/fish/config.fish

```

Install Wat, outil communautaire documentation:
```bash
$ npm install -g wat
```


Installation de Jedi autocompletion pour python
```bash
$ pip install jedi
```

Editeur de texte VSCodium
```bash
$ yay - S vscodium-bin
```

Installation de Java Eclipse
```bash
$ sudo pacman -S jdk-openjdk
$ yay -S eclipse-java
```

Outil de mind mapping (java)
```bash
$ yay -S freemind
```

**Configuration de Neovim**

Installation du gestionnaire de plugin "vim-plug" cf: [https://github.com/junegunn/vim-plug](https://github.com/junegunn/vim-plug)
```bash
$ sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```


init.vim
```text
" Neovim configuration file init.vim
" author: Anthony J.R Le Goff legoff.ant@gmail.com
" date: 16th april 2022

:set number
:set autoindent
:set tabstop=4
:set shiftwidth=4
:set smarttab
:set softtabstop=4
":set mouse=a

call plug#begin() 

Plug 'tpope/vim-fugitive'
Plug 'tpope/vim-surround'
Plug 'scrooloose/nerdtree'
Plug 'scrooloose/syntastic'
Plug 'vim-airline/vim-airline'
Plug 'tomasr/molokai'
Plug 'raimondi/delimitmate'
Plug 'kien/ctrlp.vim'
Plug 'ryanoasis/vim-devicons'
Plug 'majutsushi/tagbar'
Plug 'neoclide/coc.nvim', {'branch': 'release'}

set encoding=UTF-8

call plug#end()

:set statusline+=%#warningmsg#
:set statusline+=%{SyntasticStatuslineFlag()}
:set statusline+=%*

:let g:syntastic_always_populate_loc_list = 1
:let g:syntastic_auto_loc_list = 1
:let g:syntastic_check_on_open = 1
:let g:syntastic_check_on_wq = 0

nnoremap <C-f> :NERDTreeFocus<CR>
nnoremap <C-n> :NERDTree<CR>
nnoremap <C-t> :NERDTreeToggle<CR>

nmap <C-r> :TagbarToggle<CR>
nmap <C-p> :CtrlP<CR>

:colorscheme molokai

let g:NERDTreeDirArrowExpandable="+"
let g:NERDTreeDirArrowCollapsible="~"

" air-line
let g:airline_powerline_fonts = 1


" :CocInstall coc-python
" :CocInstall coc-clangd
```

#### Outils de Hacking, pentesting, bug bounty, CTF

Installation de dépot BlackArch >> [https://blackarch.org/](https://blackarch.org/)

```bash
$ curl -O https://blackarch.org/strap.sh
$ curl https://blackarch.org/checksums/strap
$ sha1sum strap.sh # doit etre egal a 5ea40d49ecd14c2e024deecf90605426db97ea0c (valeur du fichier strap)
$ sudo chmod +x strap.sh
$ sudo ./strap.sh
```

Mise à jour des paquets:
```bash
sudo pacman -Syyu
```

Vous pouvez installer tous les outils Blackarch via cette commande (recommandé):
```bash
$ sudo pacman -S blackarch
```
SINON Installer les outils un par un:

Installation des outils basics
```bash
$ sudo pacman -S nmap impacket wireshark-qt tcpdump hashcat john proxychains-ng exploitdb httpie metasploit armitage bind-tools radare2 sqlmap wpscan xclip beef set ufonet ettercap w3af merlin-server

```
L'installation d'OpenVAS est un peu plus complexe, voir la page: [https://wiki.archlinux.org/title/OpenVAS](https://wiki.archlinux.org/title/OpenVAS)

Configuration WordLists
```bash
$ mkdir -p /usr/share/wordlists
$ wget -q https://github.com/danielmiessler/SecLists/raw/master/Passwords/Leaked-Databases/rockyou.txt.tar.gz -O /usr/share/wordlists/rockyou.txt.tar.gz
$ wget -q https://github.com/danielmiessler/SecLists/raw/master/Discovery/Web-Content/common.txt -O /usr/share/wordlists/common.txt
```

#### Outils pour écrivain et chercheur
```bash
$ sudo pacman -S ghostwriter pdfjs pandoc texmaker manuskript libreoffice-still libreoffice-still-fr hunspell hunspell-fr
```

Extension Grammalecte et gestion de bibliographie
```bash
$ yay -S zotero libreoffice-extension-grammalecte-fr
```

#### Calcul numérique et scientifique (remplace Matlab)

```bash
$ python -m pip install jupyter scipy numpy matplotlib pandas ipython
```

Calcul Formel
```bash
$ sudo pacman -S sagemath
```

### Sauvegarde

#### Installation du client SAMBA

```bash
$ sudo pacman -S smbclient gvfs-smb
```
Redémarrer le PC pour prendre en compte la découverte du réseau local.

GUI: Ensuite rechercher votre serveur dans thunar en tapant:
```text
smb://192.168.X.X
```

Terminal: Monter le serveur SMB:

List SMB shares folders
```bash
$ smbclient -L //myServerIpAdress
```

Créer le point de montage:

```bash
sudo mkdir -p /media/NAS
```

Commande de montage
```bash
$  mount -t smbfs -W workgroup //user:password@IPSERVER/shares /media/NAS
```

OU

```bash
$ gio mount smb://<server>/<share>
```

Autres méthodes [8 ways to mount smbfs samba file system in linux](https://www.linuxnix.com/8-ways-to-mount-smbfs-samba-file-system-in-linux/)

Penser à éditer `fstab' pour ajouter le serveur SMB en permanence. Ex:
```bash
$ vim /etc/fstab
//192.168.0.1/share1 /media/NAS smbfs rw,user,username=trivial,password=xylBJRS8 0 0
```

```bash
$  sudo mount -a
```

Pour mettre en place les sauvegardes, le plus simple est d'utiliser deja-dup qui est une interface graphique de duplicity. La sauvegarde est chiffré et incrémental sur une période d'une semaine. Il existe d'autre méthode de sauvegarde tel que avec Borg-backup ou bien rync.
```bash
$ sudo pacman -S deja-dup
```

### Par-feu ufw

Activation des logs (très utile pour la suite) :
```bash
$ sudo ufw logging on
```

Rejet par défaut des connexions entrantes :
```bash
$ sudo ufw default deny incoming
```

Autorisation des connexions sortantes :
```bash
$ sudo ufw default allow outgoing
```

Recherchement des règles du pare-feu pour finir :
```bash
$ sudo ufw reload
```

### Services Cloud

Vous trouverez plusieurs services de cloud gratuit tels que qcloud, Google drive, Dropbox. Nous allons installer MEGA qui est plus sécurisé ques les autres offres de cloud, le service de l'entrepreneur Kim Dotcom a évolué sur les principes d'anonymat et de vie privée sur les données qui sont stocké sur son serveur depuis l'affaire de megaupload.

Aller sur le site [https://mega.io/desktop](https://mega.io/desktop)

Sélectionner Arch Linux et télécharger l'application.

Pour installer sélectionner le package via:
```bash
$ sudo pacman -U <package>
```

### Service VPN Proton

Configurer un VPN. Installer le metapackage sur AUR:
```bash
$ yay -S protonvpn
```

CLI (Command Line Interface)

Login:
```bash
$ protonvpn-cli login <your_protonmail>
```

Connect to the VPN:
```bash
$ protonvpn-cli connect
```

Pour créer un compte protonVPN: [https://protonvpn.com/free-vpn/linux/](https://protonvpn.com/free-vpn/linux/)

Pour voir le status de la connexion:
```bash
$ protonvpn-cli status
```

Vérifier que votre adresse IP pointe sur le VPN: [https://www.whatismyip.com/fr/](https://www.whatismyip.com/fr/)

## 2.4 Outils CLI de hackers

Pour améliorer leur productivité les hackers et programmeurs passent par l'intermédiaire du terminal mais également pour optimiser l'utilisation des ressources. Voici une liste d'outil CLI pour un environnement moderne sous UNIX-like.  

### Environnement  

*   [kitty](https://sw.kovidgoyal.net/kitty/) - Terminal émulateur, rapide, riche et fonctionne sur le GPU  
    
*   [fish](https://fishshell.com/) - Shell en natif auto-suggestion, coloration syntaxique et complétion de commande  
    
*   [starship.rs](https://starship.rs/) - Minimal prompt customizable  
    

### Boost Productivité  

*   [broot](https://dystroy.org/broot/) - Gestionnaire de fichier basé sur tree  
    
*   [z](https://github.com/rupa/z) - Navigation rapide dans le directory  
    
*   [mcFly](https://github.com/cantino/mcfly) - Recherche dans l'historique de commande avec des réseaux neuronaux  
    
*   [fzf](https://github.com/junegunn/fzf) - Fuzzy Finder, recherche de fichier, binaire, processus, git commits, lancer des programmes  
    

### Utilitaires  

*   [thefuck](https://github.com/nvbn/thefuck) - Corriger et fixer des erreurs, typos de la commande précédente  
    
*   [exa](https://github.com/ogham/exa) - Moderne replacement pour ls  
    
*   [bat](https://github.com/sharkdp/bat)\- cat clone avec coloration syntaxique et git integration  
    
*   [duf](https://github.com/muesli/duf) - Disque monitoring  
    
*   [aria2](https://aria2.github.io/) - Outil de téléchargement supportant HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink  
    
*   [ripgrep](https://github.com/BurntSushi/ripgrep) - Recherche récursive dans le directory à base de pattern de regex  
    
*   [ack3](https://github.com/beyondgrep/ack3) - grep-like optimisé pour la recherche dans le code source  
    
*   [htop](https://htop.dev/) - Interactive monitoring des ressources, gestion des processus  
    
*   [transfer.sh](https://transfer.sh/) - Rapide et facile, outil de partage de fichier  
    
*   [pandoc](https://pandoc.org) - Convertisseur universel de document  
    

### Divertissement  

*   [cmus](https://cmus.github.io/) - C\* Music player  
    
*   [mpv](https://mpv.io/) - Media player  
    
*   [spotify-tui](https://github.com/Rigellute/spotify-tui) - Spotify TUI client  
    
*   [ytfzf](https://github.com/pystardust/ytfzf) - Recherche et regarder des vidéos sur Youtube  
    
*   [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Télécharger de l'audio et des vidéos sur Youtube + d'autres sites  
    
*   [IPTV](https://github.com/shahin8r/iptv) - Simple iptv player avec fuzzy finder  
    
*   [tordl](https://github.com/X0R0X/cli-torrent-dl) - Utilitaire pour rechercher et télécharger des liens torrents  
    

### Social Media  

*   [haxor](https://github.com/donnemartin/haxor-news) - Naviguer dans le site d'information Hacker News  
    
*   [Weechat](https://weechat.org/) - Client de discussion sur IRC  
    

### Développement  

*   [neovim](https://neovim.io/) - Editeur de texte hyperextensible, script lua basé sur Vim  
    
*   [lazygit](https://github.com/jesseduffield/lazygit) - Commande Git TUI  
    
*   [hub](https://hub.github.com/) - Extension ligne de commande Git intégrant Github  
    
*   [ctop](https://github.com/bcicen/ctop) - Interface de monitoring de container Docker  
    
*   [dockly](https://github.com/lirantal/dockly) - Management des containers Dockers et services  
    
*   [HTTPie](https://github.com/httpie/httpie) - HTTP Client pour les API  
    
*   [terminal velocity](https://vhp.github.io/terminal_velocity/) - Rapide prise de note  
    
*   [rvm](https://rvm.io/) - Install, manage, multiple environnement en Ruby  
    

### Réseau  

*   [xiringuito](https://github.com/ivanilves/xiringuito) - SSH + VPN connexion  
    
*   [neoss](https://github.com/PabloLec/neoss) - User-friendly détails et statistiques de sockets TUI  
    
*   [wireshark-cli](https://archlinux.org/packages/?name=wireshark-cli) - Analyseur de packet réseau  
    
*   [proxychains](https://github.com/haad/proxychains) - Force TCP connection avec un proxy utilisant TOR, SOCK, HTTP  
    
*   [ufw](https://wiki.archlinux.org/title/Uncomplicated_Firewall) - Programme pour manager un par-feu netfilter  
    
*   [mtr](https://github.com/traviscross/mtr) - Outil de diagnostique réseau  
    
*   [protonvpn-cli](https://protonvpn.com/support/linux-vpn-tool/) - ProtonVPN Client  
    
*   [nmtui](https://wiki.archlinux.org/title/NetworkManager) - TUI Client pour Network Manager pour configurer le réseau  
    

### Assistance, apprentissage et documentation  

*   [explainshell](https://www.explainshell.com/) - Explication détaillée d'une ligne de commande  
    
*   [Regex101](https://regex101.com/) - Construit, test et debug des expressions régulières  
    
*   [tldr](https://tldr.sh/) - Gestion communautaire de man pages  
    
*   [howdoi](https://github.com/gleitz/howdoi) - Réponse instantannée à propos du code  
    
*   [wat](https://github.com/dthree/wat) - Construction communautaire de docs et cheatsheet, tous langages et frameworks  
    
*   [navi](https://github.com/denisidoro/navi) - Outil interactif cheatsheet  
    
*   [rebound](https://github.com/shobrook/rebound) - Recherche dans stack overflow quand une erreur ou une exception est levé dans le code à la compilation  
    
*   [chatGPT-cli](https://github.com/0xacx/chatGPT-shell-cli) - Utiliser chatGPT via l'API d'OpenAI  
    

### Autres  

*   [cointop](https://github.com/cointop-sh/cointop) - Surveiller le marché des cryptomonnaies  
    
*   [Qalculate](https://github.com/Qalculate/libqalculate) - Maths calculateur, calcul symbolique, matrice, équation  
    
*   [rclone](https://rclone.org/) - Sauvegarde chiffrée à distance (cloud service, NAS, etc)  
    
*   [asciinema](https://asciinema.org/) - Enregistrement de session terminal  
    
*   [cmatrix](https://github.com/matriex/cmatrix) - Un terminal façon Matrix  
    
*   [figlet](http://www.figlet.org/) - Generateur de bannière ASCII Art  
    
*   [neofetch](https://github.com/dylanaraps/neofetch) - Information sur le système  
    
*   [cpufetch](https://github.com/Dr-Noob/cpufetch) - Recherche les informations de l'architecture du CPU  
    
*   [duckly](https://duckly.com/) - Partage de terminal  
    
*   [gifski](https://gif.ski/) - Encodage de gifs

## 2.5 Le monde enchanté du "ricing"

Je suis un partisan que l'outil informatique doit être un espace pour les créatifs qui veulent faire de l'art numérique ou coder leur propre outils. Des systèmes d'exploitations comme Windows ou MacOS ne sont pas customisable, par leur nature fermé de prendre l'utilisateur pour des arriérés et voler leur travail, l'environnement est prédéfini par les ingénieurs et ne laisse aucune possibilité d'accès au code source par leur nature propriétaire. Ce qui fait que le pecnot moyen n'a pas son mot à dire s'il trouve une fonction débile et voudrait l'améliorer.  

De ce fait on aurait besoin d'accès aux fichiers de configuration de l'environnement utilisateur, ce que l'on appel .dotfiles et l'utilisateur pourrait les modifier en trackant les changements via du control de version avec Git et les partager avec la communauté.  

Il faut donc un contrôle sur sa machine et comprendre comment est assembler les différents composants du système d'exploitation, que cela soit dans des buts de customisation tels qu'en cyberdefense et blue team, optimisation de la productivité et art numérique.  

Par sa nature GNU/Linux est le choix principal mais une distribution sort du lot pour fabriquer un système sur mesure: Arch Linux. La communauté à largement dépasser Gentoo dans les distributions minimal et simpliste.  

Le temple de la customisation auparavant dans les années 2000-10 était le site de [deviant-art](https://www.deviantart.com/). Puis est arrivé Reddit et [r/unixporn](https://www.reddit.com/r/unixporn/) qui permet de suivre l'état de l'art des "ricing" ou +50% des utilisateurs sont sous Arch Linux.  

Généralement la communauté est des programmeurs et codeurs en optimisant leur utilisation du terminal pour la productivité, réduire l'utilisation de la souris et utiliser des raccourcis clavier pour gérer leur environnement avec des [Tiling Windows Manager](https://fr.wikipedia.org/wiki/Gestionnaire_de_fen%C3%AAtres_par_pavage). Ils finissent à poster egalement des memes sur [r/linuxmasterrace](https://www.reddit.com/r/linuxmasterrace/wiki/index/) et crier sur les toits "I Use Arch BTW".  

Dans cette optique je vais vous présenter ma configuration nommé "broutage de chaton" pour p0wn à tout les coups et humilier votre entourage par votre maîtrise de l'informatique en invoquant "Pedobear" en mode fanatique.  

### Prérequis  

Il faudra faire l'installation d'Arch Linux en manuel sans l'utilisation du script archinstall en intégrant:  

*   Chiffrement: dm-crypt / LUKS  
    
*   Système de fichier pour les snapshots du système: BTRFS  
    
*   UEFI Secure Boot (signé)  
    
*   swap zram  
    

Je conseil l'utilisation du combo [arch-secure-boot](https://github.com/maximbaz/arch-secure-boot) + [snap-pac](https://github.com/wesbarnett/snap-pac) dans les bonnes pratiques de sécurité du système et de restauration. Si vous n'utilisez pas le secure boot, autant utiliser un bootloader léger tel que systemd-boot.  

### Affichage Server  

il est nécessaire pour démarrer une interface utilisateur graphique GUI. L'ancien se nomme X.org et commence à être dépasser dans l'optique nous allons utiliser son successeur: Wayland qui se veut plus facile à développer et extensif avec une facilité à maintenir et plus sur.  

### Affichage Driver  

Normalement vous n'aurez pas besoin d'intégrer des drivers spécifiques avec Intel et AMD car ceci est pris en charge par [Kernel Mode Setting KMS](https://wiki.archlinux.org/title/Kernel_mode_setting). Seulement NVIDIA qui reste propriétaire nécessite la configuration en manuel. NVIDIA et Linux toujours un peu en guerre.


### Compositor  

Le compositor est un élément essentiel qui permet l'affichage de fenêtre mais également la transparence et les animations, pour Wayland nous utilisons un Tiling Windows Manager: [hyprland](https://hyprland.org/). Il faudra utiliser une barre d'état tel que Waybar et ces extensions comme Eww pour les Widgets.  

### Gestionnaire d'affichage  

Nous allons utiliser une configuration minimaliste qui gère Wayland. Pour cela on utilise un TUI (Terminal UI) en utilisant [Ly](https://github.com/fairyglade/ly). Celui-ci gère votre authentification sur le système et lancement de l'environnement. Vous pouvez également utiliser [Lemurs](https://github.com/coastalwhite/lemurs).  

### Terminal Emulateur  

La tendance est à l'utilisation de [Kitty](https://sw.kovidgoyal.net/kitty/) qui est léger et rapide propulsé par le GPU. Il intègre en natif un gestionnaire de fenêtre ou l'on peut créer des tabs et splitter le terminal ce qui fait que l'on peut ce passer de tmux comme multiplexer. Vous pouvez le customiser avec le gestionnaire de plugins [Kittens](https://sw.kovidgoyal.net/kitty/kittens_intro/#kittens).  

\> Shell  

L'utilisation du shell [fish](https://fishshell.com/) est conseillé car il intègre en natif des fonctions tels que  

*   autosuggestions en ligne basées sur l'historique ;
*   complément de tabulation utilisant les données des pages de manuel ;  
    
*   mise en évidence de la syntaxe ;
*   support intuitif des caractères génériques ;
*   configuration basée sur le Web ;
*   une saine écriture de scripts.  
    
*   Un gestionnaire de plugins: [fisher](https://github.com/jorgebucaran/fisher)  
    

  

\> Prompt  

L'invité de commande du shell peut-être customisé pour intégrer des informations tels que les branches sur Git, version logiciel, runtime, icones et symboles, etc. Nous allons utiliser [starship.rs](https://starship.rs/) et vous pouvez explorer les [presets](https://starship.rs/presets/).  

\> Autres outils en ligne de commande  

*   [duf](https://github.com/muesli/duf) Free disque usage  
    
*   [ripgrep](https://github.com/BurntSushi/ripgrep) Recherche récursive de pattern de Regex dans un dossier  
    
*   [bat](https://github.com/sharkdp/bat) cat clone avec coloration syntaxique et Git intégration  
    
*   [tldr](https://tldr.sh) Terminal companion améliorant les man pages avec example de ligne de commande  
    
*   [cmus](https://github.com/cmus/cmus) CLI audio player  
    
*   [yt-dlp](https://github.com/yt-dlp/yt-dlp) Outil de téléchargement de video sur Youtube, etc.  
    
*   [chatGPT-shell-cli](https://github.com/0xacx/chatGPT-shell-cli) Utiliser chatGPT via l'API d'OpenAi  

*   [ufw](https://wiki.archlinux.org/title/Uncomplicated_Firewall) Uncomplicated Firewall

*   [ssh](https://wiki.archlinux.org/title/Secure_Shell) Secure Shell est un protocole réseau chiffré pour ce connecter à distance sur un serveur. Voir scp et sftp
    

NOTA: pour partager un fichier / Pastebin utilisez la commande:  

```
$ cat FILE | curl -F 'sprunge=<-' http://sprunge.us`
```

### Apps Launcher  

Nous faisons tout dans un terminal sans utiliser un menu pour lancer des applications. Pour cela nous allons utiliser un outil de recherche de fichier et de binaire "fuzzy finder" tel que [fzf](https://github.com/junegunn/fzf) comme extension du shell.  

### Information système  

Pour gérer les processus et visualiser l'utilisation des ressources [htop](https://htop.dev/) reste un outil simple en CLI. Pour visualiser la configuration de l'environnement: [neofetch](https://github.com/dylanaraps/neofetch)  

### Gestionnaire de fichier  

Pour gérer ces fichiers et dossiers en CLI on utilise une extension de l'outil tree qui ce nomme [broot](https://dystroy.org/broot/).  

### Editeur de fichier  

On optimise l'utilisation du terminal pour éditer du texte et du code en particulier pour du travail à distance sur un serveur en administrateur mais également en utilisant peu de ressource système sur la charge CPU / RAM. La tendance est l'utilisation du successeur de Vim nommé [Neovim](https://neovim.io/) parmi les développeurs. On peut transformer [Neovim](https://neovim.io/) en EDI en intégrant des plugins tels que:  

*   CoC  
    
*   Telescope  
    
*   Barbar  
    
*   Vim-fugitive  
    
*   NerdTree  
    
*   Vim-surround  
    
*   Tagbar  
    
*   Delimitmate  
    
*   Vim-airline  
    
*   Vim-devicons  
    
*   Vim-ai  
    

### Fonts  

On note l'utilisation de:  

*   adobe-source-han-sans-otc-fonts (sinogramme asiatique et l'utilisation de [fcitx](https://github.com/fcitx/fcitx))  
    
*   noto-fonts  
    
*   noto-fonts-emoji  
    
*   Nerd-fonts  
    

### IRC  

Client IRC pour tchater en CLI: [weechat](https://weechat.org/). D'autres se tournerons vers Matrix et Discord considéré comme plus moderne même si la communauté FOSS et les hackers sont toujours sur IRC.  

### Themes et Icones  

Il existe des classiques tels que Catppuccin, Gruvbox ou encore Neon aux effets cyberpunk. Un repo de la communauté sur hyprland est disponible sur Github: [theme-repo](https://github.com/hyprland-community/theme-repo)  

### AUR Helper  

Pour l'utilisation de AUR, les paquets logiciels de la communauté, j'ai ma préférence pour [yay](https://github.com/Jguer/yay) qui a remplacé le projet obsolète de yaourt en complément de pacman.  

### Cloud distant et sauvegarde  

Vous pouvez utiliser l'outil [rclone](https://rclone.org/) en CLI qui permet d'accéder à un cloud distant (AWS S3, GDrive, NAS, etc) et de faire des sauvegardes chiffrés. Même si vous faites des snapshots du système, ayez une sauvegarde locale et à distance en particulier vos documents /home. D'autres options sont possible tel que le traditionnel Rsync mais aussi Borg ou Duplicity.  

References:  

*   dotfiles [https://wiki.archlinux.org/title/Dotfiles](https://wiki.archlinux.org/title/Dotfiles)  
    
*   Configuration for Arch Linux, Hyprland, kitty, kakoune, zsh and more + scripted installation guide [https://github.com/maximbaz/dotfiles](https://github.com/maximbaz/dotfiles)  
    
*   My journey of ricing Arch Linux [https://peterpf.dev/posts/ricing-arch-linux/](https://peterpf.dev/posts/ricing-arch-linux/)  
    
*   Awesome hyprland [https://github.com/hyprland-community/awesome-hyprland](https://github.com/hyprland-community/awesome-hyprland)  
    
*   Curation d'outils fish [awsm.fish](https://github.com/jorgebucaran/awsm.fish)

# 3. Administration système
---

## 3.1 Ressources SysAdmin

Dans cette article nous allons nous pencher sur le métier d'administrateur système (sysAdmin) sous Linux. Je vais utiliser ce topic pour noter les ressources sur le métier.

Quelques livres pour introduire le sujet à lire et avoir dans sa bibliothèque:

* UNIX and Linux System Administration Handbook, 5th Edition, 2017
* Practice of System and Network Administration, The Volume 1
* The Linux Philosophy for SysAdmins

### Intro SysAdmin
Une série de vidéo sur Youtube pour ce lancer dans l'administration système Linux, de niveau débutant à SysAdmin: The Linux Basics Course: [Beginner to SysAdmin, Step by Step](https://www.youtube.com/watch?v=bju_FdCo42w&list=PLtK75qxsQaMLZSo7KL-PmiRarU7hrpnwK) suivi d'un très bon cours pour savoir configurer un serveur: [Linux Server Course - System Configuration and Opération](https://www.youtube.com/watch?v=WMy3OzvBWc0). 

### Avoir son propre serveur
Pour aller plus loin, déployer un [serveur domestique DIY](https://fr.linuxteaching.com/article/how_to_build_a_server_at_home) chez vous, pour prototyper, apprendre des services, créer vos virtuals Labs pour tester des configurations. Ne dépensez pas plus de 1000€ pour un serveur en neuf, [lien vers le configurateur PC](https://www.ldlc.com/configurateur-pc/):

```
########################################################
Config Server mini-ITX Ryzen CPU 32GO RAM 4x2TO HDD RAID
########################################################
Par ldlc.com

- ASRock A520M-ITX/ac 119€95
- AMD Ryzen 5 5500 Wraith Stealth (3.6 GHz / 4.2 GHz) 157€96
- Fractal Design Node 304 Noir 119€95
- Corsair Vengeance LPX Series Low Profile 32 Go (2x 16 Go) DDR4 3200 MHz CL16 159€95
- 4 x Seagate IronWolf 2 To 395€80
- be quiet! Straight Power 11 450W 80PLUS Gold  107€95
- 2 x Corsair Câbles SATA Gainés Droits/Coudés 30 cm (coloris bleu) 29€90
- Advance GTA 230 (AZERTY Français) 19€94 

total: 1111€

```

### Certifications
Pour vous faire reconnaître sur le marché du travail, passez des certifications, elles permettent de juger de vos connaissances, quelques une des plus demandés:

* Linux Essentials 
* RHCSA - Red Hat Certified System Administrator
* RHCE - Red Hat Certified Engineer
* LPIC 1 - Linux Administrator
* LPIC 2 - Linux Engineer
* LPIC 3 - Linux Enterprise Professional Certification
* LFCS - Linux Foundation Certified System Administrator
* compTIA Linux+

[Plus d'information sur les certifications](https://hackr.io/blog/best-linux-certifications)

### Programmation

Pour automatiser les tâches d'administrations il faut savoir programmer en bash, python voir du perl. Pour du scripting. Livre recommandé:

Bash & scripting:

* The Linux Command Line, 2nd Edition
* Linux® Command Line and Shell Scripting Bible, Third Edition

Python:

* Automate the Boring Stuff with Python
* Python for Unix and Linux System Administration 1st Edition 

### E-Learning

Quelques liens de cours d'administrateur système:

* [Essentials of Linux System Administration (LFS201)](https://training.linuxfoundation.org/training/essentials-of-linux-system-administration/)
* [Linux Administration Bootcamp: Go from Beginner to Advanced](https://www.udemy.com/course/linux-administration-bootcamp/)

### Organisation

League of Professional System Administrators (LOPSA):

[https://lopsa.org/](https://lopsa.org/)

### Sites références

En français, le site de François Goffinet sur l'administration Linux:

* [https://linux.goffinet.org/](https://linux.goffinet.org/)

Le wiki r/sysadmin de la communauté Reddit:

* [https://www.reddit.com/r/sysadmin/wiki/index/](https://www.reddit.com/r/sysadmin/wiki/index/)


La documentation Ubuntu pour serveur:

* [https://help.ubuntu.com/community/Servers](https://help.ubuntu.com/community/Servers)
* [https://ubuntu.com/server/docs](https://ubuntu.com/server/docs)

L'administration sous Debian:

* [Guide de référence Debian](https://www.debian.org/doc/manuals/debian-reference/)
* [The Debian Administrator's Handbook](https://debian-handbook.info/browse/stable/)
* [Guide de sécurité du Debian 3.19](https://www.debian.org/doc/manuals/securing-debian-manual/index.fr.html)

[Meta Serveur Fault](https://meta.serverfault.com/) est un site de questions et réponses pour administrateur système et réseau.

[TLDP The Linux Documentation Project](https://tldp.org/index.html)

### Outils

10 outils Linux à connaître en tant que Sysadmin

* [https://geekflare.com/fr/linux-tools-for-sysadmin/](https://geekflare.com/fr/linux-tools-for-sysadmin/)

10 Must Have Tools for Linux System Administrators

* [https://www.makeuseof.com/best-tools-for-linux-system-administrators/](https://www.makeuseof.com/best-tools-for-linux-system-administrators/)

What’s your favorite automation tool?

* [https://www.redhat.com/sysadmin/favorite-automation-tool](https://www.redhat.com/sysadmin/favorite-automation-tool)

30 Linux System Monitoring Tools Every SysAdmin Should Know

* [https://www.cyberciti.biz/tips/top-linux-monitoring-tools.html](https://www.cyberciti.biz/tips/top-linux-monitoring-tools.html)

Some useful tools for Linux sysAdmin

* [https://ostechnix.com/some-useful-tools-for-linux-system-admins/](https://ostechnix.com/some-useful-tools-for-linux-system-admins/)

### Roadmap

* [https://roadmap.sh/devops](https://roadmap.sh/devops)
* [https://github.com/infinite-education/linux-admin-roadmap](https://github.com/infinite-education/linux-admin-roadmap)
* [http://www.nrstickley.com/system-admin-roadmap/](http://www.nrstickley.com/system-admin-roadmap/)

### List Awesome

sysadmin-reading-list

* [https://github.com/unixorn/sysadmin-reading-list#online-communities](https://github.com/unixorn/sysadmin-reading-list#online-communities)

Awesome SysAdmin

* [https://github.com/kahun/awesome-sysadmin](https://github.com/kahun/awesome-sysadmin)

## 3.2 Proxmox Homelab

n va parler un peu de serveur. Notre monde fonctionne actuellement sous l'apartheid informatique dans le sens que les utilisateurs Windows et MacOS sous logiciels propriétaires ne connaissent rien en serveur, alors que les libristes, hackers et utilisateurs de Linux sont des experts, c'est dans leur seconde nature. Tout simplement car l'infrastructure d'internet fonctionne entièrement sous le logiciel libre et open source. Le Top 1 million des sites mondiaux fonctionnent sous un serveur web Linux à 96,3% mais également plus de 90% des infrastructures en cloud computing. [Stats Linux](https://truelist.co/blog/linux-statistics/).  

Clairement Windows server est marginal, peu de service et vulnérable, et quand on se lance dans l'apprentissage des serveurs, c'est du pure suicide, certain sont des Microsoft fanboys en particulier pour de l'utilisation avec Azure. De nombreux serveurs ont une stack de base sous Debian LAMP (Linux Apache MySQL PHP), c'est old school mais toujours d'actualité chez les "tradis" pour le développement de services web.  

Débuter sur serveur ne demande pas un grand investissement, il est possible de commencer sur un [Raspberry Pi Zero W à 18€](https://www.kubii.fr/pi-zero-w/1851-raspberry-pi-zero-w-3272496006997.html) fonctionne avec un Debian lite (RaspberryPi OS). Il y a beaucoup de documentation pour les apprenants. [Quelques idées de projets](https://raspberrytips.fr/projets-raspberry-pi-zero-2w/). Personnellement je préfère le modèle [MangoPi MQ Pro à 30€](https://fr.aliexpress.com/item/1005004157984532.html) sur architecture RISC-V en processeur. Windows server ne fonctionne pas sur nano-ordinateur et système embarqué, vous êtes prévenu c'est de la daube, problème de compatibilité matériel, mais également d'utilisation des ressources sur des configurations minimalistes.  

### L'auto-hébergement  

Si vous voulez monter en compétence chez soi sur serveur, vous faites de l'auto-hébergement en particulier dans le cadre pour contrôler vos données que cela soit personnel ou entreprise et déployer des services. Cela demande quelques compétences en réseau informatique et administration système et tester des technologies localement. Un web entrepreneur a raison de monter en compétence sur serveur pour préparer des services d'entreprises et gérer les données localement, en réalité l'entrepreneur est garant des données et donc du patrimoine informationnel de son entreprise et de la gestion du système d'information (SI). Il faut planifier en amont des sauvegardes et possibilités de migration des données et services quand l'entreprise monte en puissance, ce que l'on appel du [scaling](https://www.leslivresblancs.fr/dossier/tout-comprendre-de-la-scalabilite-du-scaling-et-de-la-scale). D'ou que l'on utilise la technologie de virtualisation sur serveur.  

### Proxmox  

L'un des produits open source largement plébiscité est [Proxmox VE](https://www.proxmox.com/en/) pour de la virtualisation sur serveur avec comme hyperviseur KVM et des containers LXC. C'est un standard actuellement dans la construction de Homelab mais également pour des TPE ou associations. L'interface d'administration des machines virtuelles (VM) est intuitive, mais également pour utiliser des technologies comme les snapshots ou le RAID avec le système de fichier ZFS. Proxmox est une distro Linux Debian avec une surcouche de management de VM et d'interface d'administration.  

Le matériel nécessaire est en fonction de ces propres besoins. Vous pouvez commencer sur du pré-construit comme un Intel NUC et seulement 4GB de ram à 150€, voir des Lenovo Thinkcentre en mini-PC. Une VM fait généralement à minima 512Mo de RAM pour un serveur.  

Pour un Homelab performant, il est nécessaire de monter soi-même sa configuration et mettre entre 1000 à 2000€, avec du matériel dédié pour serveur tel qu'un processeur Xeon ou des disques durs pour NAS comme la série Iron Wolf. J'ai ma préférence pour l'utilisation du format mini-ITX en carte-mère et un boitier adapté avec 4 à 6 emplacement de disques durs comme le "[fractal design node 304](https://www.fractal-design.com/products/cases/node/node-304/black/)" qui permet de réduire l'encombrement. Vous trouverez sur [ce guide pour NAS](https://forums.serverbuilds.net/t/guide-nas-killer-4-0-fast-quiet-power-efficient-and-flexible-starting-at-125/667), des configurations matériels détaillées d'Homelab.  

Proxmox permet d'utiliser la technologie PCI Passthrough pour utiliser une carte graphique et déployer une machine virtuelle dédiée à de l'utilisation de GPU intensive comme du Cloud Gaming. Il est possible de ce connecter à distance depuis votre PC sur votre réseau local à une VM de Cloud Gaming avec une environnement isolé et pré-configuré, c'est pratique si votre PC ne permet pas d'utiliser une carte graphique ou installer des produits, jeux. Seulement faudra une configuration matériel puissante que cela soit en processeur, ram et alimentation. Cela me permet d'invoquer une session à distance sous Arch Linux via Remmina en me connectant au serveur.  

La configuration de mon propre serveur Proxmox à titre indicatif:  

```Text

###########################################################
Config Server mini-ITX CPU Ryzen 5  64GO RAM 4x2TO HDD RAID
###########################################################
Par ldlc.com

- Carte mère: ASRock A520M-ITX/ac 119€95
- CPU: AMD Ryzen 5 5500 Wraith Stealth 6 cores (3.6 GHz / 4.2 GHz) 157€96
- Boitier: Fractal Design Node 304 Noir 119€95
- RAM: Corsair Vengeance LPX Series Low Profile 64 Go (2x 32 Go) DDR4 3200 MHz CL16 256€95
- HDD: 4 x Seagate IronWolf 2 To 395€80
- Alimentation: be quiet! Straight Power 11 450W 80PLUS Gold  107€95
- Ventirad: Noctua NH-L9a-AM4 59€
- Cable: 2 x Corsair Câbles SATA Gainés Droits/Coudés 30 cm (coloris bleu) 29€90
- Clavier: Advance GTA 230 (AZERTY Français) 19€94
- GPU: Zotac NVIDIA GTX 1650 OC 4GB 180€ 

total: 1440€
```

### Configuration  

Quand vous devez configurer la première fois le serveur, il faut mettre en place un OS "bare metal" en installant l'iso de Proxmox via USB. Il faut un écran, clavier et souris. On doit choisir les volumes, mettre en place le RAID, les paramètres d'administration et réseau. Qui ne serve qu'une fois, ou en cas de maintenance critique et d'accès réseau à distance coupé. Une fois le serveur configuré, on ce connecte à distance sur le réseau local depuis son PC de travail. [Installer Proxmox et lancer sa première VM](https://www.it-connect.fr/comment-installer-proxmox-ve-7-0-et-creer-sa-premiere-vm/).  

### Services Homelab  

Il est possible de déployer énormément de services ou de les créer. Il y a une pléthore de programme et apps open source pour de l'auto-hébergement. Vous trouverez une [liste Awesome "self-hosted"](https://github.com/awesome-selfhosted/awesome-selfhosted). Dans l'exemple d'une association, il est possible de déployer un ERP pour la comptabilité: Dolibarr + outils de collaboration et de gestion de document: Nextcloud + un site statique (Jekyll en Ruby) + service de mailing list (Sympa) pour la communication.  

Après dans les outils plébiscités on retrouve:  

*   Prometheus  
    
*   Terraform  
    
*   Kubernetes  
    
*   Docker  
    
*   Portainer  
    
*   Plex  
    
*   Ansible  
    
*   Pi-Hole  
    
*   Webmin  
    

Le mieux est de se renseigner sur internet, il y a des articles de blogs et vidéos Youtube sur le type d'utilisation d'un HomeLab avec retour d'expérience. [HomeLab Services Tour Late 2021 - What am I Self-Hosting in my HomeLab?](https://www.youtube.com/watch?v=IE5y2_S8S8U)  


## 3.3 Sécurisation de serveur Nginx

Configuration:

* OS: Debian 11
* Auto-update security
* Web server: Nginx
* par-feu: ufw
* securité: fail2ban, rkhunter, clé RSA SSH Only-Login, logwatch
* SSL Enable avec Let's Encrypt auto-renew
* Template: Simple.css


Create a static website on Nginx:

* [https://jgefroh.medium.com/a-guide-to-using-nginx-for-static-websites-d96a9d034940](https://jgefroh.medium.com/a-guide-to-using-nginx-for-static-websites-d96a9d034940)

Proteger son serveur VPS:

* [https://www.remipoignon.fr/securiser-son-serveur-linux/](https://www.remipoignon.fr/securiser-son-serveur-linux/)

Static site template:

* Simple.css [https://github.com/kevquirk/simple.css](https://github.com/kevquirk/simple.css)

Liste pour utiliser un générateur de site statique (blog, docs, etc...):

* [https://jamstack.org/generators/](https://jamstack.org/generators/)

Partage de fichier à la racine (index) du web server comme repository:

* Apaxy: [https://oupala.github.io/apaxy/](https://oupala.github.io/apaxy/)
* h5ai: [https://larsjung.de/h5ai/](https://larsjung.de/h5ai/)
* Directory Lister: [https://www.directorylister.com/](https://www.directorylister.com/)

NOTA: Hacker web design style Brutalist:

* What Is Brutalism in Web Design? [https://elementor.com/blog/brutalism-in-web-design/](https://elementor.com/blog/brutalism-in-web-design/)

--------------------
**LIST COMMAND ON SERVER** 

Install editor text & bash completion:
```
$ apt install sudo nano vim bash-completion
```

Configure the hostname:
```text
$ nano /etc/hosts

127.0.0.1       localhost.qasari.net   localhost
37.187.181.111  qasari.net     qasari
```

The following lines are desirable for IPv6 capable hosts
```text
::1     localhost ip6-localhost ip6-loopback
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters
```

Edit hostname:
```
$ nano /etc/hostname

qasari
```

```
$ reboot now
```

Check if hostname is correct:
```
$ hostname
$ hostname -f
```

Update debian installation:
```text
$ nano /etc/apt/sources.list 

# enable contrib non-free

deb http://deb.debian.org/debian bullseye main contrib non-free
deb-src http://deb.debian.org/debian bullseye main contrib non-free

deb http://deb.debian.org/debian-security bullseye/updates main contrib non-free
deb-src http://deb.debian.org/debian-security bullseye/updates main contrib non-free

deb http://deb.debian.org/debian bullseye-updates main contrib non-free
deb-src http://deb.debian.org/debian bullseye-updates main contrib non-free
```

```
$ sudo apt-get update && apt-get upgrade
```

Synchro the system clock:
```
$ apt install ntp
$ timedatectl set-ntp true
```

Ajout d'une utilisateur:
```
$ sudo adduser toto
$ sudo usermod -a -G sudo toto
$ su toto
$ passwd
```

Enlever un utilisateur:
```
$ sudo deluser debian
```

**IMPORTANT NOTE DE SECURITY**

Utiliser une clé SSH sur pour l'authentification sur le serveur: [https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-debian-11](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-debian-11)

Generate paire de clé RSA 4046
```
$ ssh-keygen -b 4096
```
copy la clé public sur le serveur distant
```text
$ ssh-copy-id toto@37.187.181.111
```

Configuration de SSH:
```text
$ nano /etc/ssh/sshd_config

port 2382
PermitRootLogin no
PasswordAuthentication no
```

```
$ reboot now
```

On ce reconnecte via la clé SSH
```text
$ ssh -p 2382 toto@37.187.181.111
```

Configurer le firewall:

setup ufw:

* [https://linuxconfig.org/ubuntu-20-04-open-http-port-80-and-https-port-443-with-ufw](https://linuxconfig.org/ubuntu-20-04-open-http-port-80-and-https-port-443-with-ufw)

```text
$ sudo apt install ufw

$ sudo ufw default deny incoming
$ sudo ufw default allow outgoing

$ sudo ufw allow 2382
$ sudo ufw allow http
$ sudo ufw allow https

$ sudo ufw enable
$ sudo ufw status
```

Configurer fail2ban:
```
$ sudo apt install fail2ban
```

```text
$ sudo cp /etc/fail2ban/fail2ban.conf /etc/fail2ban/fail2ban.local
$ sudo cp /etc/fail2ban/jail.conf /etc/fail2ban/jail.local
```

```text
$ sudo nano /etc/fail2ban/jail.local

[sshd]
enabled = true
port = 2382
filter = sshd
logpath = /var/log/auth.log
maxretry = 3
findtime = 300
bantime = 3600
ignoreip = 127.0.0.1
destemail = test@gmail.com
```


Depuis une dernière version de fail2ban, pour recevoir les mails de notification, il faut indiquer votre mail dans les fichiers :
```text
	/etc/fail2ban/action.d/sendmail-common.conf
	/etc/fail2ban/action.d/mail.conf
	/etc/fail2ban/action.d/mail-whois.conf
```

```
$ sudo systemctl enable fail2ban
$ sudo systemctl start fail2ban
```

```
$ sudo fail2ban-client status
```

Configure Rkhunter:
```
$ sudo apt install rkhunter
```

```text
$ sudo nano /etc/default/rkhunter

# Pour effectuer une vérification chaque jour
CRON_DAILY_RUN="yes"
REPORT_EMAIL="test@gmail.com"
```

Open /etc/rkhunter.conf. Uncomment (remove the # to the left) and change the following three variables:
```text
MIRRORS_MODE=1 ---> MIRRORS_MODE=0

UPDATE_MIRRORS=0 ---> UPDATE_MIRRORS=1

WEB_CMD="/bin/false" ---> WEB_CMD=""
```

Confirm config file:
```
sudo rkhunter -C
```

Update database:
```
$ sudo rkhunter --update
```
Check the local system:
```
$ sudo rkhunter --check
```

Configure logwatch:
```text
$ sudo apt install logwatch
$ nano /usr/share/logwatch/default.conf/logwatch.conf
MailTo = test@gmail.com
```

```
$ sudo logwatch status
```

test manuellement:
```text
$ sudo logwatch --detail Low --mailto email@address --service http --range today
```

Configurer les mises à jours de sécurité automatique:
```
$ sudo apt install unattended-upgrades
```

```
$ sudo systemctl enable unattended-upgrades
$ sudo systemctl start unattended-upgrades
```

Configuration file:
```
$ sudo nano /etc/apt/apt.conf.d/50unattended-upgrades
```

In our example, remove // from the “security” line if it’s there, "origin=Debian,codename=${distro_codename},label=Debian-Security";

Enabling automatic upgrades:
```text
$ sudo nano /etc/apt/apt.conf.d/20auto-upgrades

APT::Periodic::Update-Package-Lists "1";
APT::Periodic::Unattended-Upgrade "1";
APT::Periodic::AutocleanInterval "7";
```

Testing the configuration:

```
$ sudo unattended-upgrades --dry-run --debug
```
Installer Nginx:
```
$ sudo apt install nginx
$ mkdir /var/www/qasari.net
```

Transférer vos fichiers local vers le serveur:
```text
$  scp -P 2382 -r ~/qasari.net/* toto@37.187.181.111:/var/www/qasari.net
```

Ne pas oublier de changer le détenteur du groupe:
```text
$ sudo chown -R $USER:$USER /var/www
```


Configure Nginx to serve the website
```text

$ sudo nano /etc/nginx/sites-available/qasari.net
server {
	listen 80 default_server;
	listen [::]:80 default_server;  

	root /var/www/qasari.net;  
	index index.html;  
	
	server_name qasari.net www.qasari.net;  
	location / {
		try_files $uri $uri/ =404;
		}
}

```
Link site enable:
```text
$ ln -s /etc/nginx/sites-available/qasari.net /etc/nginx/sites-enabled/qasari.net
```

```
$ sudo systemctl restart nginx
```


Configuration SSL avec let's encrypt:
```
$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:certbot/certbot
$ sudo apt-get update
$ sudo apt-get install python3-certbot-nginx
$ sudo certbot --nginx certonly
```

Enable auto-renewal for certificates:
```text

$ sudo crontab -e

17 7 * * * certbot renew --post-hook "systemctl reload nginx"
```

Tell Nginx use SSL for website inside server conf file:

```text
server {
   listen 443 default_server;
   listen [::]:443 default_server;
   #... all other content


   # ...previous content here
   ssl on;
   ssl_certificate /etc/letsencrypt/live/qasari.net/fullchain.pem;
   ssl_certificate_key /etc/letsencrypt/live/qasari.net/privkey.pem;
}
```

Restart web server et reboot:
```
$ sudo systemctl restart nginx
$ reboot now
```

# 4. Réseaux
---

## 4.1 Basics réseaux

### Concept de réseau

Un réseau est un ensemble d'objets interconnectés. Il permet de faire circuler des éléments entre chacun de ces objets selon des règles bien définies.

Selon le type d'objet on parle parfois:

* Réseau de transport: ensemble d'infrastructures et de disposition permettant de transporter des personnes et des biens entre des zones géographiques.

* Réseau téléphonique: Infrastructure permettant de faire circuler la voix entre plusieurs postes téléphoniques

* Réseau de neurones: Ensemble de cellules interconnectées entre elles, également une technologie de machine learning en intelligence artificielle.

* Réseau de malfaiteurs: Ensemble d'escrocs qui sont en contact entres eux. Un escroc généralement en cache un autre.

* Réseau informatique: Ensemble d'ordinateurs reliés entre eux grâce à des lignes physiques et échangeant des informations sous forme de donnée numérique.

Le réseau utilise différents supports physiques de transmission, tel que pour le transfert de données, sous forme d'impulsions électriques, de lumière ou d'ondes electromagnétiques. Et du type de support: cuivres, cable coaxial, ou fibre optique...

### Intérêt d'un réseau

Il y a un intérêt à relier des machines entre elles afin de pouvoir échanger de l'information:

* Le partage de ressource (fichier, applications, matériels)
* La communication entre personnes ( courrier électronique, discussion (Discord, IRC), voIP)
* La communication entre processus (entre des machines industrielles)
* La garantie de l'unicité de l'information ( base de données)
* Les jeux-vidéos en lignes multijoueurs tel que les MMO.

On a standardiser généralement sous l'appelation groupware, tel que les agendas électroniques pour communiquer plus efficacement.

Aujourd'hui on parle du développement des réseaux étendus WAN déployés à l'échelle du pays, voir à l'échelle mondiale pour des entreprises et multi-nationales.

### Topologie

L'arrangement physique du réseau sous forme spatiale s'appel la topologie. On distingue généralement:

* En bus
* En étoile
* En anneau
* En arbre
* En maillée

La topologie logique représente la façon dont les données transitent dans les lignes de télécommunication tel que ethernet, token Ring et FDDI.

Plus de détail sur: [https://cisco.goffinet.org/ccna/fondamentaux/topologies-reseau/](https://cisco.goffinet.org/ccna/fondamentaux/topologies-reseau/)

**Qu'est-ce qu'un nœud en informatique ?**

Un nœud est un périphérique physique au milieu de nombreux périphériques sachant recevoir, envoyer et transférer des informations. L’ordinateur est le nœud le plus fréquent et est souvent désigné par le terme nœud Internet ou nœud informatique.

« Nœud » est la dénomination donnée à la machine et au programme dans les réseaux pairs à pairs. À l’inverse de l’architecture client-serveur, l’architecture réseau organisée en nœud est symétrique. Chaque nœud a la même aptitude pour acquérir, émettre ou calculer, que les autres nœuds de son réseau.

Les modems, les concentrateurs, les commutateurs, les serveurs, les ponts et les imprimantes sont aussi des nœuds. Il en est de même pour tous les périphériques se connectant via WI-FI ou Ethernet. Par exemple, une imprimante et trois ordinateurs reliés en réseau correspondent à quatre nœuds au total. Ce genre de réseau informatique doit posséder une forme de reconnaissance (adresse IP ou adresse Mac) pour pouvoir être identifié par d’autres périphériques réseau. Sans cette identification, un nœud ne fonctionne plus en tant que tel.

De la même manière, une grappe de serveurs informatiques est composée de nœuds de calculs, de nœuds frontaux et de nœuds de stockage. On peut aussi rencontrer des nœuds consacrés au monitoring. Les nœuds sont assemblés entre eux par de nombreux réseaux. Cette technique de grappe de serveurs permet une gestion intégrale et d’aller au-delà des limitations que l’on pourrait rencontrer avec un seul ordinateur : cela accroît la disponibilité, assiste la montée en charge, permet une classification de la charge, aide à la gestion des ressources (mémoire vive, disque dur, bande passante réseau, processeur). L’utilisation des nœuds en grappe de serveur est de plus en plus usitée par les scientifiques, pour lesquels la nécessité en calculs à haute performance devient de plus en plus courante.

### Architecture réseau

On distingue deux modes de fonctionnement:

* **Peer-to-peer** ou il n'y a pas d'ordinateur central et chaque ordinateur joue un rôle similaire
* **Client-serveur** ou un ordinateur (serveur) fourni des services réseau aux ordinateurs clients, tel que afficher une page web

**Qu'est-ce que le P2P ?** 

Le pair-à-pair, peer-to-peer ou P2P (les trois termes désignent la même chose), définit un modèle de réseau informatique d'égal à égal entre ordinateurs, qui distribuent et reçoivent des données ou des fichiers. Dans ce type de réseau, comparable au réseau client-serveur, chaque client devient lui-même un serveur. Le P2P facilite et accélère les échanges entre plusieurs ordinateurs au sein d'un réseau. 

**Quelles sont les utilisations du peer-to-peer ?**

L'une des utilisations les plus fréquentes du P2P est le partage de fichiers. Un client qui possède un fichier (comme un film, par exemple, ou un document quelconque) le met à disposition d'autres clients via une plateforme de téléchargement (il devient alors serveur). Il peut simultanément aussi télécharger d'autres fichiers partagés par d'autres clients (serveurs). Les bouts de fichiers téléchargés sont immédiatement partagés avec d'autres ordinateurs, jusqu'à ce que le fichier soit complet. Cette technique augmente la rapidité de téléchargement et diminue la charge sur le serveur central. 

La pratique s'est notamment répandue avec les applications telles que Emule, BitTorrent ou encore MTorrent, souvent à des fins de partage illégal de fichiers multimédias comme des films ou des albums de musique. Deux techniques de peer-to-peer existent. La première, centralisée, laisse un ou plusieurs serveurs diriger chaque ordinateur vers ceux qui possèdent le fichier qu'il recherche. La seconde, décentralisée ne connaît pas de serveur fixe. Chaque ordinateur fait office de mini serveur, ce qui répartit la responsabilité, notamment dans le cas de partage illégal de documents protégés. L'une des particularités de ce type de réseau est d'offrir un relatif anonymat aux utilisateurs.

Désormais, le bitcoin et la blockchain reposent sur du P2P et ont remis le concept au goût du jour.

**Définition du modèle client-serveur**

Le modèle client-serveur, aussi appelé « protocole client-serveur », est un mode de transaction qui permet la répartition des tâches au sein d’un réseau.

Le terme de serveur englobe d’une part le matériel qui met les ressources nécessaires à disposition d’autres ordinateurs ou applications, d’autre part le logiciel informatique qui se charge de la communication avec les clients. Le serveur accepte les demandes (ou requêtes) du client, les traite et fournit la réponse demandée. Un client se présente aussi sous différentes formes : soit un ordinateur, soit un logiciel qui communique avec le serveur. Le client envoie ses requêtes et reçoit les réponses du serveur. L’interaction entre le serveur et le client caractérise le modèle client-serveur.

**Quelles sont les caractéristiques du protocole client-serveur ?**

L’environnement client-serveur possède quelques caractéristiques propres. Il existe par exemple une répartition claire des tâches entre clients et serveurs. Le serveur est responsable de la fourniture des services, il exécute les requêtes demandées et fournit la réponse attendue. Dans la transaction, le client est la partie utilisatrice qui demande les services mis à disposition et reçoit la réponse du serveur.

Dans le modèle client-serveur, plusieurs clients utilisent un même serveur. Le serveur traite donc les requêtes de différents clients. Pour cela, il met à disposition un service de manière permanente et passive. Un client envoie des demandes actives de services au serveur et initie ainsi ses tâches.

Dans cette architecture, un ordinateur physique peut être à la fois client et serveur. Le fait qu’il envoie ou reçoive les requêtes de services et de ressources détermine son rôle dans le réseau.

Les protocoles définissent les règles selon lesquelles la communication entre les clients et les serveurs se font. Différents protocoles réseau pour l’échange de données sont utilisés selon les tâches. De plus, en fonction du domaine d’application, il existe différents types de réseaux

### Protocoles

L'intérêt des protocoles. Lors des communications entre ordinateurs et routeurs ou entre routeurs entre eux, il faut que :

* les informations soient acheminées aux bonnes destinations ;
* les informations ne soient pas modifiées par rapport à l’original (pas de perte de données) ;
* la confidentialité soit respectée ;
* cela se fasse rapidement.

Pour arriver à tout cela, on met en place des protocoles, c’est-à-dire des normes, pour entamer et finir une communication entre deux machines distantes, en n’oubliant pas que le modèle utilisé est toujours celui du client-serveur.

**Principe général d’un protocole**

Pour simplifier, un programme d’un ordinateur A veut communiquer avec un programme d’un ordinateur B.

L’ordinateur A va pour cela passer par un programme plus spécialisé, qui va lui-même dialoguer avec un programme spécialisé de l’ordinateur B en passant par un protocole. Chaque programme de ce protocole va sous-traiter des tâches pour ne traiter que des tâches élémentaires.

On classe les protocoles en couches hiérarchiques en fonction du niveau de sophistication des tâches que chaque protocole accomplit.

**Quels protocoles fonctionnent sur la couche réseau ?**

Comme décrit ci-dessus, IP est un protocole de la couche réseau responsable du routage. Mais ce n'est pas le seul protocole de la couche réseau.

IPsec : Internet Protocol Security (IPsec) établit des connexions IP chiffrées et authentifiées sur un réseau privé virtuel (VPN). Techniquement, IPsec n'est pas un protocole, mais plutôt un ensemble de protocoles comprenant le protocole de sécurité d'encapsulation (ESP), l'en-tête d'authentification (AH) et les associations de sécurité (SA).

ICMP : Le protocole de message de contrôle Internet (ICMP) signale les erreurs et fournit des mises à jour d'état. Par exemple, si un routeur n'est pas en mesure de livrer un paquet, il renvoie un message ICMP à la source du paquet.

IGMP : Le protocole de gestion des groupes Internet (IGMP) établit des connexions réseau de type un à plusieurs. IGMP aide à mettre en place la multidiffusion, ce qui signifie que plusieurs ordinateurs peuvent recevoir des paquets de données dirigés vers une adresse IP.

**Quels autres protocoles sont utilisés sur Internet ?**

Voici quelques-uns des protocoles les plus importants à connaître :

TCP : Comme décrit ci-dessus, TCP est un protocole de couche de transport qui assure une livraison fiable des données. TCP est destiné à être utilisé avec IP, et les deux protocoles sont souvent référencés ensemble sous le nom de TCP/IP.

HTTP : Le protocole de transfert hypertexte (HTTP) est la base du World Wide Web, l'Internet avec lequel la plupart des utilisateurs interagissent. Il est utilisé pour transférer des données entre des périphériques. HTTP appartient à la couche application (couche 7), car il met les données dans un format que les applications (par exemple, un navigateur) peuvent utiliser directement, sans autre interprétation. Les couches inférieures du modèle OSI sont gérées par le système d'exploitation d'un ordinateur, et non par les applications.

HTTPS : Le problème avec HTTP est qu'il n'est pas chiffré - Tout attaquant qui intercepte un message HTTP peut le lire. HTTPS (HTTP Secure) corrige cela en chiffrant les messages HTTP.

TLS/SSL : Transport Layer Security (TLS) est le protocole que HTTPS utilise pour le chiffrement. TLS s'appelait auparavant Secure Sockets Layer (SSL).

UDP : Le protocole UDP (User Datagram Protocol) est une alternative plus rapide mais moins fiable au TCP au niveau de la couche transport. Il est souvent utilisé dans des services tels que le streaming vidéo et le gaming, où la livraison rapide des données est primordiale.

**Quels sont les protocoles utilisés par les routeurs ?**

Les routeurs de réseau utilisent certains protocoles pour découvrir les chemins de réseau les plus efficaces vers d'autres routeurs. Ces protocoles ne sont pas utilisés pour transférer des données utilisateur. Les principaux protocoles de routage réseau sont les suivants :

BGP : Le protocole BGP (Border Gateway Protocol) est un protocole de couche application que les réseaux utilisent pour diffuser les adresses IP qu'ils contrôlent. Ces informations permettent aux routeurs de décider par quels réseaux les paquets de données doivent passer pour atteindre leur destination.

EIGRP : Le protocole EIGRP (Enhanced Interior Gateway Routing Protocol) identifie les distances entre les routeurs. EIGRP met automatiquement à jour l'enregistrement des meilleures routes de chaque routeur (appelé table de routage) et diffuse ces mises à jour aux autres routeurs du réseau.

OSPF : Le protocole Open Shortest Path First (OSPF) calcule les itinéraires réseau les plus efficaces en fonction de divers facteurs, notamment la distance et la bande passante.

RIP : Le Routing Information Protocol (RIP) est un ancien protocole de routage qui identifie les distances entre les routeurs. RIP est un protocole de couche d'application.

### Adresse IP

**Qu'est-ce qu'une adresse IP ?**

Une adresse IP permet d’identifier chaque équipement connecté à un réseau informatique utilisant le protocole IP fourni par l'ICANN pour les adresses publics. Elle permet à l’équipement de communiquer sur le réseau auquel il est connecté.

Exemples :

* Un PC connecté en Wi-Fi sur la Box de votre domicile
* Une Smart TV connectée en câble sur la Box de votre domicile
* Un smartphone connecté en Wi-Fi chez McDo’
* Un serveur connecté à un réseau d’entreprise
* Etc.

Sans cette adresse IP, et même si le câble RJ45 est connecté ou que la carte réseau Wi-Fi est connectée à votre réseau sans-fil, vous ne pourrez pas communiquer avec les autres appareils du réseau qui eux, ont une adresse IP valide.

**Adresses IPv4 et IPv6**

Il y a deux versions d’adresses IP utilisées à ce jour : adresses IPv4 (version 4) et IPv6 (version 6). La v4 reste la plus utilisée alors que la v6 devrait, un jour, la remplacer.

*Adresse IPv4*

* Notation décimale avec 4 valeurs comprises entre 0 et 255, séparées par des points : 192.168.1.10
* Longueur de 32 bits c’est-à-dire 4 octets, soit 4 milliards d'adresses.

*Adresse IPv6*

* Notation hexadécimale avec 8 valeurs séparées par « : »
* Exemple : 1987:0c02:0000:84c2:0000:0000:cf2a:9077
* Longueur de 128 bits c’est-à-dire 16 octets

### Classes

Historiquement, chaque adresse IP appartient à une classe qui correspond à une plage d’adresse IP. Il y a 5 classes différentes : À, B, C, D et E. En fonction des classes, les adresses IP de la plage ont un usage spécifique et qui peut être différent d'une classe à l'autre.

* La classe A de l’adresse IP 10.0.0.0 à 126.255.255.255
* La classe B de l’adresse IP 128.0.0.0 à 191.255.255.255
* La classe C de l’adresse IP 192.0.0.0 à 223.255.255.255
* La classe D de l’adresse IP 224.0.0.0 à 239.255.255.255
* La classe E de l’adresse IP 240.0.0.0 à 255.255.255.255

Il y a notamment les adresses IP privées et publiques. Les adresses IP privées sont les adresses IP que l’on peut utiliser pour les équipements sur un réseau local (le réseau à la maison ou en entreprise). Une adresse IP privée ne peut pas être utilisée sur Internet, pour un site Web par exemple, car elles ne sont pas routées sur Internet.

Les adresses IP publiques, à l’inverse, sont utilisées exclusivement sur Internet : votre Box Internet, un site Web, etc. Une adresse IP publique est unique dans le monde contrairement à une adresse IP privée !

À la maison, votre PC a une adresse IP privée de configurée sur sa carte réseau et quand il sort sur Internet, le NAT intervient : il utilise l'adresse IP publique de la box pour accéder à Internet. Grâce à ce mécanisme de NAT, le réseau local privé est masqué d'Internet (et protégé) et plusieurs équipements d'un même réseau peuvent utiliser une même adresse IP publique. De ce fait, on optimise la consommation d'adresse IPv4, notamment.

**Les adresses IP privées**

Les adresses IP privées représentent toutes les adresses IP de classe A, B et C que l’on peut utiliser dans un réseau local (LAN) c'est-à-dire dans le réseau de votre entreprise ou dans le réseau domestique. De plus, les adresses IP privées ne peuvent pas être utilisées sur internet (car elles ne peuvent pas être routées sur internet), les hôtes qui les utilisent sont visibles uniquement dans votre réseau local. Les classes A, B et C comprennent chacune une plage d’adresses IP privées à l’intérieur de la plage globale.

* Les adresses privées de la classe A : 10.0.0.0 à 10.255.255.255
* Les adresses privées de la classe B : 172.16.0.0 à 172.31.255.255
* Les adresses privées de la classe C : 192.168.0.0 à 192.168.255.255

**Les exceptions**

* Le réseau 127.0.0.0 est réservé pour les tests de boucle locale avec notamment l’adresse IP 127.0.0.1 qui est l’adresse « localhost » c'est-à-dire de boucle locale de votre PC.
* Le réseau 0.0.0.0 est lui aussi réservé (et utilisé notamment pour définir une route par défaut sur un routeur).

L'adresse de diffusion(broadcast) qui est la dernière adresse disponible du réseau. Elle permet de transmettre des données à l’ensemble des hôtes d’un réseau. Pour cela, un hôte peut envoyer un seul paquet adressé à l’adresse de diffusion du réseau, par exemple 192.168.10.255

L'adresse de diffusion générale : 255.255.255.255 ; pour diffuser sur un réseau dont on ne connaît pas l’identifiant.

### DHCP

*DHCP est le terme anglais pour Dynamic Host Configuration Protocol. Il constitue une règle de procédure d’attribution de l’adresse IP, dont le fonctionnement reste inchangé pour chaque dispositif ou chaque réseau. Ce protocole permet également de suivre l’évolution de l’ensemble des adresses IP du réseau et sur tous les sous-réseaux qui ont besoin d’une adresse IP.*

**Le fonctionnement du DHCP**

En général, les serveurs qui assurent le protocole DHCP sont gérés par des routeurs sur les réseaux en LAN. Sur de larges réseaux, le DHCP est assuré par des ordinateurs spéciaux. Le paramétrage DHCP comprend surtout la définition du champ de fonctionnement du serveur DHCP. Ce serveur attribue automatiquement des adresses IP et paramètre mécaniquement les autres données du réseau.
Le routeur joue le rôle de serveur DHCP pour la majorité des particuliers et des PME. Au sein des grands systèmes, un serveur spécialisé est requis pour remplir cette fonction.

Quand un dispositif sous tension est branché à un réseau avec un serveur DHCP, celui-ci envoie une requête DHCP au serveur, dénommée DHCPDISCOVER. Lorsque le message DISCOVER arrive au serveur DHCP, ce dernier garde une certaine adresse IP utilisable par le périphérique, puis la communique à son client par un signal DHCPOFFER.

Lorsque le client propose d’utiliser l’adresse IP retenue, le périphérique envoie un message DHCPREQUEST pour l’autoriser par le service DHCP. Puis le serveur transmet un ACK afin de valider que le dispositif accepte l’adresse IP précise. Il fixe ensuite la longueur de temps pendant que le dispositif utilise ladite adresse avant de recevoir une nouvelle adresse.

S’il décide que le périphérique concerné est incapable de fournir l’adresse IP, celui-ci transmet un NACK. Le réglage du DHCP est essentiel. Une mauvaise conception peut causer des interruptions majeures du réseau et entraîner des ralentissements lors de la recherche d’une solution au problème.

**Comment configurer un DHCP**

Pour configurer un DHCP, il faut d’abord définir son réseau d’utilisation pour que l’adresse IP fixe le serveur DHCP. À noter qu’aucune adresse IP dynamique du serveur ne peut être utilisée. Il faut également prendre du temps pour définir les réglages propres de l’adresse IP DHCP. En même temps, cela vous aidera à spécifier la rapidité du réseau, la passerelle par défaut et le masque sous réseau.
Vous devrez ensuite passer en revue la configuration de votre fournisseur de services DHCP. Il est important de commencer par choisir une adresse IP sortante et une adresse IP entrant parmi la série d’adresses IP susceptibles d’être affectées aux DHCP. Ce réglage du serveur DHCP implique aussi de spécifier le masque sous réseau permettant de subdiviser les adresses IP.

Il faut ensuite spécifier la longueur de location. Celle-ci est la période durant laquelle l’adresse IP est assignée à un hôte, après quoi elle retourne à la base d’adresses IP dans le serveur pour une attribution à d’autres appareils.

Pour achever le processus relatif à la préparation du serveur DHCP, il faut indiquer la passerelle par défaut. Vous devez indiquer le serveur DNS principal et secondaire correspondant au service DHCP. Le processus précise les réglages dans les conditions de fonctionnement du service DHCP. En cas de mauvaise configuration, il est possible que le service DHCP fonctionne de manière incorrecte.

**À quel moment une adresse IP statique est-elle utile?**

Une adresse IP variable et dynamique ne devrait jamais être utilisée sur les dispositifs statiques nécessitant un contrôle continu. Même si ces dispositifs se trouvent essentiellement dans un réseau, il est difficile de leur assigner des adresses IP variables.
Ce genre de paramétrage est même inutile. Il est possible de contourner ce problème en évitant de recourir au DHCP, en leur donnant au contraire une adresse IP statique.

Le même principe est valable s’il y a une nécessité en permanence d’un point d’accès à distance sur une machine avec une adresse ip. Si DHCP est activé, l’ordinateur obtiendra une autre adresse IP. L’adresse pour l’ordinateur ne restera pas alors longtemps valide. En utilisant un programme d’accès à distance dépendante d’une adresse IP, il faut désactiver le DHCP.

**Les autres particularités du DHCP**

Les serveurs DHCP permettent de créer une série d’adresses IP utilisées pour servir des appareils possédant une adresse. Ce pool d’adresses constitue la seule solution pour un périphérique de bénéficier de connexions réseau valides.
Ceci est une raison supplémentaire de l’utilité du DHCP. Il autorise la connexion de multiples dispositifs à l’intérieur du réseau pour une certaine durée sans avoir à recourir à un pool d’adresse.

Le protocole DHCP assigne plusieurs adresses IP à durée déterminée d’utilisation (période de location). Toutefois, utiliser les commandes telles que « ipconfig », pour rechercher l’adresse IP de l’ordinateur, permet d’obtenir différents résultats au fil du temps.

Le fait que le DHCP serve à attribuer une adresse IP dynamique à un client donné ne veut pas dire que des adresses IP statiques sont impossibles à être utilisées au même moment. Un amalgame de périphériques recevant d’adresses dynamiques et des périphériques ayant reçu une adresse IP manuellement peut coexister sur un seul réseau.

Les fournisseurs d’accès Internet se servent du DHCP pour l’attribution de leurs adresses IP, en parallèle avec le protocole TCP IP qui gère la communication réseau des ordinateurs. Vous le constaterez au moment de la détermination de l’adresse IP publique. Celle-ci évoluera sans doute progressivement, sauf si le réseau local dispose lui-même d’une adresse IP fixe, généralement limitée aux sociétés disposant des services internet publics.

### Ports

L'adresse IP sert donc à identifier de façon unique un ordinateur sur le réseau tandis que le numéro de port indique l'application à laquelle les données sont destinées. Un **socket** est une combinaison d'adresse IP + Port). C'est une fonction de multiplexage que le processus qui consiste à faire transiter diverses informations vers des applications tierces.

Les ports sont codés sur 16 bits soit 65 536 possibilités. Les ports 0 à 1023 sont des ports reconnus généralement réservés à des processus systèmes, ou démons. Du port 1024 à 49151 sont des ports enregistrés et les ports dynamiques ou privées sont le reste. 

Liste de ports courants:

* 21 FTP
* 25 SMTP
* 53 DNS
* 63 Whois
* 80 HTTP
* 443 HTTPS
* 445 SMB
* 110 POP3
* 119 NNTP


### TCP/IP

**Définition du mot TCP/IP**

Le protocole TCP/IP (Transmission Control Protocol/Internet Protocol) réunit les deux protocoles TCP et IP. Il s'agit donc d'une suite de protocoles associée au domaine d'Internet pour lequel elle facilite le transfert de données.

Présenté simplement, le protocole TCP/IP est un standard de communication entre deux processus. Il détermine et fixe les règles inhérentes à l'émission et à la réception de données sur un réseau. L'association des deux protocoles permet d'apporter des garanties de fiabilité dans le transfert des données. Avec le TCP/IP, vous êtes certain(e) que les informations envoyées arriveront bel et bien au bon destinataire.

Côté fonctionnement, la suite TCP/IP se base en partie sur l'adressage IP. Elle est capable de fractionner les informations échangées en paquets pour que les grosses données puissent être acceptées par les IP, et de contrôler les éventuelles erreurs de transmissions des données.

**Modèle TCP/IP**

Le modèle TCP/IP est fondé sur quatre couches qui enveloppent les messages originaux avant qu’ils soient placés sur le support physique sous forme d’ondes représentant les données de la communication.

Chaque couche assure une fonction de maintenance et de service de la communication. TCP/IP ne se préoccupe pas du contenu (les propos tenus par les utilisateurs dans les messages); il se contente d’assurer des fonctions qui facilitent les communications, le partage et la diffusion des informations.

**Modèle TCP/IP à quatre couches**

[Couche Application]

* Elle est la couche de communication qui s’interface avec les utilisateurs.
* Exemples de protocoles applicatifs : HTTP, DNS, DHCP, FTP, …
* Elle s’exécute sur les machines hôtes.

[Couche Transport : TCP]

* Elle est responsable du dialogue entre les hôtes terminaux d’une communication.
* Les applications utiliseront TCP pour un transport fiable et UDP sans ce service.
* Les routeurs NAT et les pare-feux opèrent un filtrage au niveau de la couche transport.

[Couche Internet : IP]

* Elle permet de déterminer les meilleurs chemins à travers les réseaux en fonction des adresses IPv4 ou IPv6 à portée globale.
* Les routeurs transfèrent le trafic IP qui ne leur est pas destiné.

[Couche Accès au réseau : LAN/WAN]

* TCP/IP ne s’occupe pas de la couche Accès Réseau
* Elle organise le flux binaire et identifie physiquement les hôtes
* Elle place le flux binaire sur les supports physiques
* Les commutateurs, cartes réseau, connecteurs, câbles, etc. font partie de cette couche

Au sens du modèle TCP/IP la couche Accès Réseau est vide, car la pile des protocoles Internet (TCP/IP) est censée “inter-opérer” avec les différentes technologies qui offrent un accès au réseau.

Plus on monte dans les couches, plus on quitte les aspects matériels, plus on se rapproche de problématiques logicielles.

**Encapsulation**

Pour transmettre du contenu d’un ordinateur à un autre, l’utilisateur va utiliser un programme qui construit un message enveloppé par un en-tête applicatif, HTTP par exemple. Le message subit une première encapsulation.

Le logiciel va utiliser un protocole de couche transport correspondant pour établir la communication avec l’hôte distant en ajoutant un en-tête TCP ou UDP.

Ensuite, l’ordinateur va ajouter un en-tête de couche Internet, IPv4 ou IPv6 qui servira à la livraison des informations auprès de l’hôte destinataire. L’en-tête contient les adresses d’origine et de destination des hôtes.

Enfin, ces informations seront encapsulées au niveau de la couche Accès qui s’occupera de livrer physiquement le message.

Résumer à travers une image de [l'encapsulation](https://d33wubrfki0l68.cloudfront.net/4dbe0395af2361407063ec83404215a71d4064ab/63083/assets/images/ccna/c3bcaae0-df48-4475-a52f-8c925fd3e77a.png)

**Couche Application**

Dans notre exemple, notre utilisateur ouvre sa page Web favorite et elle s’affiche immédiatement. Mais en réalité, avant d’obtenir ce résultat, il demande à lire une ressource (un fichier) située ailleurs, quelque part dans le réseau, sur www.test.tf. Dans le meilleur des cas, la plupart du temps, une page lui sera envoyée en retour et s’affichera dans son navigateur.

Il s’agit ici du premier message utile envoyé par l’utilisateur. Pour ce type d’usage ou d’application, il existe un protocole de couche application qui est largement disponible, à savoir par exemple HTTP1. On pourrait résumer ce premier message par : “Serveur HTTP www.test.tf, donne-moi ta page /index.html”.

On trouvera un grand nombre de protocoles de couche application, chacun offrant un type de service avec des caractéristiques propres. Ils sont développés dans le but d’offrir un service de communication qui soit au plus proche des utilisateurs (logiciels). Quelques exemples de commandes de couche application :

* Commandes HTTP : “donne-moi une page Web”, “Voici la page”, “donne-moi l’image”, “Voici l’image”.
* Commande SIP : “Tente d’établir une communication vocale ou vidéo à destination de tel numéro de téléphone, de tel courriel”, “J’émets une sonnerie”, “j’ouvre la ligne”
* Commande SMTP : “livre ce message à user@test.tf”
* Commande RTP : “transmets telle capsule vidéo ou audio”
* Commandes DNS : “quelles sont les adresses IP de www.test.tf”, “voici l’adresse IPv4 de www.test.tf”
* Commandes DHCP : “Donne-moi une adresse IP”, “Voici des paramètres optionnels”

**Couche Transport**

Cette commande de couche application est alors enveloppée, “encapsulée” dit-on dans le jargon, par un protocole de couche Transport comme TCP. TCP apporte un service fiable pour que les utilisateurs puissent utiliser cette application Web. C’est justement TCP qui crée l’intuition d’une connexion directe entre les deux ordinateurs connectés, entre l’utilisateur et le serveur Web qui rend les pages à l’autre bout du monde.

Un canal de communication entre un “port” d’origine et un “port” de destination est établi entre les deux machines interlocutrices au préalable de l’envoi de la commande HTTP.

Si TCP fournit le canal de transmission entre les deux ordinateurs, il offre aussi une maintenance “connectée” de la communication. Il l’initie, la maintient avec des fonctionnalités telles que le contrôle de flux et la reprise sur erreur, et enfin il termine cette communication. On parle alors de protocole “orienté connexion”.

**Couche Internet**

Pour que ces deux ordinateurs se reconnaissent de manière certaine, ils ont besoin d’autres identifiants que le seul nom de la destination ou les ports utilisés à l’origine et à la destination. À cet effet, une nouvelle encapsulation ajoute des informations de couche Internet, comme l’adresse IP d’origine (source) et l’adresse IP de destination. Elles identifient les hôtes de la communication d’un point de vue logique et global. C’est grâce à ces adresses que les données peuvent parvenir jusqu’au serveur de pages Web www.test.tf et que le trafic de retour est possible.

Des périphériques spécifiques qui interconnectent les lignes physiques se chargent de transmettre ces paquets d’informations jusqu’à la destination. Entre les deux ordinateurs, les paquets peuvent traverser plusieurs d’entre eux. Des routeurs relaient les paquets d’un point d’origine à un point d’extrémité de l’interréseau en fonction de l’adresse IP de destination.

**Socket TCP/IP**

À partir d’un couple de type adresse_IP:port_TCP de la source et de la destination, soit des sockets dans le jargon, littéralement des “prises”, on crée une sorte de tunnel sur ces connexions; on parlera alors de “session” TCP. TCP offre un mode connecté qui initie un dialogue, le maintient et puis le ferme entre les deux ordinateurs. Le canal logique qui permet d’acheminer les messages utiles (couche application) est ainsi créé. Donc en réalité, une connexion TCP aura été établie avant l’envoi de la requête HTTP.

Le serveur Web www.test.tf est un ordinateur dans le réseau dont le logiciel de service Web (Apache2 en l’occurrence) a mis le port TCP 80 de l’une de ses interfaces à l’écoute. Le port 80 est le port par défaut pour offrir un service Web en HTTP (TCP80). L’ordinateur qui émet la requête soit le client utilise un port aléatoire dans des valeurs élevées. Chaque protocole de couche application dispose d’un port par défaut (qu’il est utile de connaître), il est toujours possible de mettre à l’écoute un service sur un port non conventionnel.

Si on est attentif à la capture, on constate que du trafic DNS (Application) supporté par UDP (couche transport) a demandé la résolution du nom en IPv4 (A Record) et en IPv6 (AAAA Record). UDP (User Datagram Protocol) est utilisé pour une communication de type “Raw”, à livraison brute, au contraire du service offert par TCP.

**Couche Accès Réseau**

Faut-il encore que ces données puissent être physiquement transmises. Une nouvelle capsule place des informations de couche Accès Réseau. Par exemple, dans notre cas, des informations propres à la technologie Wi-Fi ou à la technologie Ethernet encapsulent le paquet IPv4. Ces dernières, indépendantes des protocoles TCP/IP permettent aux utilisateurs de placer physiquement toutes ces données sur un réseau local. Le réseau local prendra en charge le transfert de ces informations jusqu’à la bonne destination.

On peut trouver dans cette couche de nombreuses fonctions qui assurent le transport physique : identification, livraison, contrôle du support, aspects physiques, connecteurs, entre beaucoup d’autres. En cela, cette couche se distingue des fonctions logiques et globales de TCP/IP. On retiendra aussi le rôle important que jouent les commutateurs Ethernet, “switches” dans le jargon, qui prennent leurs décisions de transfert sur base des adresses MAC codées dans cette couche.

Cette couche “basse” est aussi désignée comme étant le rassemblement de la couche Liaison de données (L2) et de la couche physique (L1) en référence au modèle OSI. On y place donc des protocoles autres que ceux de la pile TCP/IP : des protocoles IEEE 802 ou des normes ratifiées par l’ANSI, l’EIA/TIA ou encore l’ITU qui en fait disposent de leur propre modélisation jusqu’à la mise en ondes sur un support physique.


### TCP Three-way handshake

Selon le protocole de communication TCP, une connexion entre deux hôtes s'établit en trois étapes : c'est le three-way handshake. À la connexion, on définit les numéros de séquence que l'on utilisera pour le transfert de données TCP.

Comme son nom l'indique, le three-way handshake se déroule en trois étapes :

* SYN : Le client qui désire établir une connexion avec un serveur va envoyer un premier paquet SYN (synchronized) au serveur. Le numéro de séquence de ce paquet est un nombre aléatoire A.
* SYN-ACK : Le serveur va répondre au client à l'aide d'un paquet SYN-ACK (synchronize, acknowledge). Le numéro du ACK est égal au numéro de séquence du paquet précédent (SYN) incrémenté de un (A + 1) tandis que le numéro de séquence du paquet SYN-ACK est un nombre aléatoire B.
* ACK : Pour terminer, le client va envoyer un paquet ACK au serveur qui va servir d'accusé de réception. Le numéro de séquence de ce paquet est augmenté de 1 par rapport au dernier qu'il a envoyé (soit A + 1), et le numéro du ACK est égal au numéro de séquence du paquet précédent (SYN-ACK) incrémenté de un (B + 1).

Une fois le three-way handshake effectué, le client et le serveur ont reçu un acquittement de la connexion. Les étapes 1 et 2 définissent le numéro de séquence pour la communication du client au serveur et les étapes 2 et 3 définissent le numéro de séquence pour la communication dans l'autre sens. Une communication full-duplex est maintenant établie entre le client et le serveur.

### UDP

La communication entre les systèmes de réseaux domestiques et d’entreprises locaux, et les réseaux publics, comme Internet, repose par défaut sur la suite des protocoles Internet. Le composant le plus célèbre de cette pile de protocoles est incontestablement l’Internet Protocol (IP), qui est non seulement responsable de l’adressage et de la fragmentation des paquets de données, mais qui définit également la façon dont sont décrites les informations sur la source et la destination. La transmission des données est toutefois habituellement assurée par le protocole de transport orienté connexion TCP (« Transmission Control Protocol »), ce qui explique pourquoi les réseaux sont souvent qualifiés de réseaux TCP/IP. Si le TCP garantit une sécurité, il s’accompagne également d’un retard de la transmission. C’est pourquoi David Patrick Reed a présenté en 1980 son concept de User Datagram Protocol (UDP) comme une alternative plus simple et plus rapide au protocole standard.

**L’UDP, qu’est-ce que c’est ?**

Le User Datagram Protocol, abrégé en UDP, est un protocole permettant l’envoi sans connexion de datagrammes dans des réseaux basés sur le protocole IP. Afin d’atteindre les services souhaités sur les hôtes de destination, le protocole utilise des ports qui constituent un élément essentiel de l’entête UDP. À l’instar de nombreux autres protocoles de réseau, l’UDP fait partie de la suite des protocoles Internet. Il intervient au niveau de la couche transport et joue ainsi le rôle d’intermédiaire entre la couche réseau et la couche application.

> Le protocole UDP constitue une alternative directe au très répandu TCP, les deux protocoles se distinguant en particulier sur un point : tandis que la transmission via TCP a lieu uniquement après un handshaking en trois temps obligatoire (authentification mutuelle de l’expéditeur et du destinataire comprenant l’établissement de la connexion), l’UDP renonce à de telles procédures afin de maintenir la durée de la transmission à un minimum.

En utilisant le User Datagram Protocol, une application peut donc envoyer très rapidement des informations, étant donné qu’aucune connexion au destinataire n’est établie et qu’aucune réponse ne doit être attendue. En revanche, il n’y a aucune garantie que les paquets arrivent entiers et dans le même ordre que celui dans lequel ils ont été envoyés. Par ailleurs, le protocole n’offre aucune protection contre les manipulations ou accès de tiers. Les paquets erronés peuvent toutefois être identifiés à l’aide d’une somme de contrôle facultative (obligatoire avec IPv6).

L’UDP (User Datagram Protocol) est un protocole sans connexion de la suite des protocoles Internet qui travaille au niveau de la couche transport et qui a été défini en 1980 dans la RFC (Request for Comments) 768. En tant qu’alternative au TCP fonctionnant de façon plus simple et quasiment sans retard, l’UDP est utilisé pour la transmission rapide de paquets de données dans des réseaux IP. Les domaines d’application typiques de l’UDP sont donc les requêtes DNS, les connexions VPN et le streaming audio et vidéo, ou des besoins de temps-réels.

**Aperçu des propriétés de l’UDP**

Afin de comprendre dans le détail comment la transmission des paquets est effectuée avec ce protocole, il est judicieux de se pencher plus précisément sur les caractéristiques du User Datagram Protocol déjà mentionnées.

* L’UDP est sans connexion : le transport des données via le protocole UDP se démarque par le fait qu’il a lieu sans connexion existante entre l’expéditeur et le destinataire. Les paquets concernés sont ensuite envoyés à l’adresse IP privilégiée en indiquant le port de destination, sans que l’ordinateur auquel cette adresse est attribuée n’ait à envoyer une réponse. Si des paquets doivent être renvoyés à l’expéditeur, l’entête UDP peut également contenir le port source.
* Ports utilisés par l’UDP : à l’instar du TCP, l’UDP a recours à des ports afin de remettre les paquets aux bons protocoles ultérieurs ou aux applications souhaitées sur le système de destination. Comme le modèle éprouvé, les ports sont définis à l’aide d’une numérotation, dont les numéros compris entre 0 et 1023 sont attribués à des services fixes.
* L’UDP permet une communication rapide, sans délai : ce protocole de transport est adapté à une transmission rapide des données, car il n’établit pas de connexion. Ceci résulte également du fait que la perte de paquets individuels impacte uniquement la qualité de la transmission. En cas de connexion TCP, il est en revanche procédé automatiquement à une nouvelle demande des paquets perdus, ce qui bloque l’intégralité du processus de transmission.
* L’UDP n’offre aucune garantie quant à la sécurité et à l’authenticité des données : le fait de renoncer à l’authentification mutuelle de l’expéditeur et du destinataire permet au protocole UDP d’assurer une vitesse de transmission exceptionnelle. Toutefois, le protocole ne peut garantir l’intégrité et la sécurité des paquets de données. L’ordre dans lequel les paquets ont été envoyés n’est pas non plus garanti. C’est pourquoi les services faisant appel à l'UDP doivent mettre à disposition des mesures de correction et de protection propres.

**En résumé**

La principale propriété du User Datagram Protocol est sa capacité à transporter les paquets de données sans connexion établie. Les avantages résultant de cette transmission en termes de vitesse sont contrebalancés par une forte vulnérabilité face aux manipulations, une perte de paquets non corrigée et un classement arbitraire des paquets. De ce fait, les applications UDP doivent pouvoir travailler correctement avec des paquets de données manquants et non classés et/ou inclure des mécanismes de correction et de sécurité propres.

### Modèle OSI

**Modèle OSI : définition**

Le modèle OSI (Open Systems Interconnection) est un cadre conceptuel qui définit comment les systèmes réseau communiquent et envoient des données d'un expéditeur à un destinataire.

Le modèle est utilisé pour décrire chaque composant de la communication de données pour pouvoir établir des règles et des normes pour les applications et l'infrastructure du réseau.

Le modèle OSI contient sept couches qui s'empilent conceptuellement de bas en haut. Ces couches sont les suivantes :

* Physique
* Liaison des données
* Réseau
* Transport
* Session
* Présentation
* Application

**Les sept couches du modèle OSI**

OSI est décomposé en couches.

Chaque couche a une fonction spécifique et communique et travaille avec les couches inférieure et supérieure.

Le modèle OSI est conceptuel, mais sa conception permet une communication à la fois physique et virtuelle sur un réseau. Nous allons commencer par la couche 7, qui est la couche la plus élevée de la pile.

* [Couche 7 – La couche d'application]

La couche 7 est connue de la plupart des gens car elle communique directement avec l'utilisateur.

Une application qui s'exécute sur un appareil peut communiquer avec d'autres couches OSI, mais l'interface fonctionne sur la couche 7.

Par exemple, un client de messagerie qui transfère des messages entre le client et le serveur fonctionne sur la couche 7. Lorsqu'un message est reçu sur le logiciel client, c'est la couche application qui le présente à l'utilisateur.

Les protocoles d'application comprennent le SMTP (Simple Mail Transfer Protocol) et le HTTP, qui est le protocole de communication entre les navigateurs et les serveurs Web.

* [Couche 6 – La couche de présentation]

Nous avons mentionné que la couche application affiche les informations aux utilisateurs, mais la couche présentation du modèle OSI est celle qui prépare les données pour qu'elles puissent être affichées à l'utilisateur.

Il est courant que deux applications différentes utilisent l’encodage.

Par exemple, la communication avec un serveur Web via HTTPS utilise des informations chiffrées. La couche de présentation est responsable de l’encodage et du décodage des informations afin qu'elles puissent être affichées en clair.

La couche de présentation est également responsable de la compression et de la décompression des données lorsqu'elles passent d'un appareil à un autre.

* [Couche 5 – La couche session]

Pour communiquer entre deux appareils, une application doit d'abord créer une session, qui est unique à l'utilisateur et l'identifie sur le serveur distant.

La session doit être ouverte suffisamment longtemps pour que les données soient transférées, mais elle doit être fermée une fois le transfert terminé. Lorsque de gros volumes de données sont transférés, la session est chargée de s'assurer que le fichier est transféré dans son intégralité et que la retransmission est établie si les données sont incomplètes.

Par exemple, si 10 Mo de données sont transférés et que seuls 5 Mo sont complets, la couche session s'assure que seuls 5 Mo sont retransmis. Ce transfert rend la communication sur un réseau plus efficace au lieu de gaspiller des ressources et de retransférer l'intégralité du fichier.

* [Couche 4 – La couche de transport]

La couche transport est chargée de prendre les données et de les décomposer en petits morceaux.

Lorsque des données sont transférées sur un réseau, elles ne sont pas transférées en un seul paquet.

Pour rendre les transferts plus efficaces et plus rapides, la couche transport divise les données en segments plus petits. Ces petits segments contiennent des informations d'en-tête qui peuvent être réassemblées sur le périphérique cible.

Les données segmentées sont également dotées d'un contrôle d'erreur qui indique à la couche session de rétablir une connexion si les paquets ne sont pas entièrement transférés au destinataire cible.

* [Couche 3 – La couche réseau]

La couche réseau est chargée de décomposer les données sur l'appareil de l'expéditeur et de les réassembler sur l'appareil du destinataire lorsque la transmission s'effectue sur deux réseaux différents.

Lorsque l'on communique au sein d'un même réseau, la couche réseau est inutile, mais la plupart des utilisateurs se connectent à d'autres réseaux, tels que les réseaux dans le cloud.

Lorsque les données traversent différents réseaux, la couche réseau est chargée de créer de petits paquets de données acheminés vers leur destination, puis reconstruits sur l'appareil du destinataire.

* [Couche 2 – La couche de liaison de données]

La couche réseau facilite la communication entre différents réseaux, mais la couche liaison de données est responsable du transfert des informations sur le même réseau.

La couche liaison de données transforme les paquets reçus de la couche réseau en trames. Tout comme la couche réseau, la couche liaison de données est responsable du contrôle des erreurs et du flux pour garantir la réussite de la transmission.

* [Couche 1 – La couche physique]

Comme son nom l'indique, la couche physique est responsable de l'équipement qui facilite le transfert des données, comme les câbles et les routeurs installés sur le réseau.

Cette couche est l'un des aspects de la transmission réseau où les normes sont essentielles. Sans normes, la transmission entre les appareils de différents fabricants est impossible.

Résumez en une image du [modèle OSI](https://fr.wikipedia.org/wiki/Mod%C3%A8le_OSI#/media/Fichier:OSI_Model_v1.svg)


## 4.2 Sous-masque CIDR

**Qu'est-ce qu'un sous-réseau ?**

Un sous-réseau est un réseau à l'intérieur d'un réseau. Les sous-réseaux rendent les réseaux plus efficaces. Grâce au subnetting, le trafic réseau peut parcourir une distance plus courte sans passer par des routeurs inutiles pour arriver à destination.

maginons qu'Alice veuille envoyer une lettre à Bob, qui vit dans la ville d'à côté. Pour que la lettre parvienne à Bob le plus rapidement possible, elle doit être livrée directement du bureau de poste d'Alice au bureau de poste de la ville où habite Bob, puis être remise à Bob. Si la lettre est d'abord envoyée à un centre de tri postal situé à des centaines de kilomètres, la lettre d'Alice mettra beaucoup plus de temps à parvenir à Bob.

Tout comme le service postal, les réseaux sont plus efficaces lorsque les messages voyagent aussi directement que possible. Lorsqu'un réseau reçoit des paquets de données d'un autre réseau, il trie et achemine ces paquets par sous-réseau afin que les paquets ne suivent pas un itinéraire inefficace pour arriver à leur destination.

**Pourquoi le subnetting est-il nécessaire ?**

Comme l'illustre l'exemple précédent, la structure des adresses IP sont fait qu'il est relativement simple pour les routeurs Internet de trouver le bon réseau pour y acheminer les données. Cependant, dans un réseau de classe A (par exemple), il pourrait y avoir des millions d'appareils connectés, et il peut falloir un certain pour que les données trouvent le bon appareil. C'est C'est pour cette raison que l'on a recours au subnetting  : il réduit l'adresse IP à l'utilisation dans une gamme d'appareils.

Les adresses IP indiquant uniquement les adresses du réseau et de l'appareil, elles ne peuvent pas indiquer à quel sous-réseau un paquet IP doit être envoyé. Les routeurs au sein d'un réseau utilisent ce qu'on appelle un masque de sous-réseau pour trier les données en sous-réseaux.

**Qu'est-ce qu'un masque de sous-réseau ?**

Un masque de sous-réseau est semblable à une adresse IP, mais il est destiné à un usage uniquement interne au sein d'un réseau. Les routeurs utilisent des masques de sous-réseau pour acheminer les paquets de données au bon endroit. Les masques de sous-réseau ne sont pas indiqués dans les paquets de données qui circulent sur Internet : ces paquets indiquent seulement l'adresse IP de destination, qu'un routeur fera correspondre à un sous-réseau.

Supposons que Bob réponde à la lettre d'Alice, mais qu'il envoie sa réponse à l'adresse du lieu de travail d'Alice plutôt qu'à son domicile. L'entreprise où travaille d'Alice est assez grande et comprend de nombreux services différents. Pour que les employés reçoivent leur correspondance rapidement, l'équipe administrative trie le courrier par service plutôt que par employé. Après avoir reçu la lettre de Bob, ils regardent dans quel service travaille Alice et voient qu'il s'agit du service clients. Ils envoient la lettre au service clients au lieu de la transmettre directement à Alice, et le service clients la lui remet.

Dans cet exemple, Alice représente l'adresse IP et le service clients le masque de sous-réseau. Après avoir déterminé dans quel service travaille Alice, la lettre de Bob a été rapidement classée dans le bon groupe de destinataires potentiels. Sans cette étape, les responsables administratifs auraient passé du temps à chercher laborieusement l'emplacement exact du bureau d'Alice, qui peut se trouver n'importe où dans l'entreprise.

Prenons un exemple concret : supposons qu'un paquet IP soit envoyé l'adresse IP 192.0.2.15. Cette adresse IP est un réseau de classe C, le réseau est donc identifié par 192.0.2 (ou plus précisément par 192.0.2.0/24). Les routeurs transmettent le paquet à un hôte du réseau indiqué par 192.0.2.

Une fois que le paquet atteint ce réseau, un routeur au sein du réseau consulte sa table de routage. Il réalise quelques opérations mathématiques binaires en utilisant son masque de sous-réseau 255.255.255.0, voit l'adresse de l'appareil 15 (le reste de l'adresse IP indique le réseau), et calcule dans quel sous-réseau le paquet doit aller. Il transmet le paquet au routeur ou au commutateur responsable de la livraison des paquets au sein de ce sous-réseau, et le paquet arrive à l'adresse IP 192.0.2.15 (en savoir plus sur les routeurs et les commutateurs).

Comme je le disais, notre adresse IP est découpée en deux parties : la partie réseau et la partie hôte. La question c'est, comment est positionnée cette limite entre les deux blocs ? Cette limite entre la partie réseau et la partie hôte est déterminée par le masque de sous-réseau. Le masque de sous-réseau va permettre de découper un réseau en plusieurs sous-réseaux.

Le masque de sous-réseau peut s'écrire de deux façons différentes :

* Notation décimale : 255.255.255.0, 255.0.0.0, 255.255.248.0, etc.

* Notation CIDR (Classless Inter Domain Routing) : /8, /16, /22, /24, etc.

La notation CIDR est la norme aujourd'hui et sachez qu'elle commence à /0 pour 0.0.0.0 et se termine à /32 pour 255.255.255.255.

Le fait de maîtriser les masques de sous-réseau va permettre d'optimiser son réseau, de comprendre comment il est organisé et de prévoir les évolutions futures.

### Calcul de l'adresse réseau

Pour faire du [calcul de l'adresse IP d'un réseau et le nombre d'hôtes disponible](https://neptunet.fr/calcul-ip/).

Image pour résumer le [nombre d'hôte en fonction du CIDR](http://tech.queryhome.com/?qa=blob&qa_blobid=2160450046065448055)

Outils: 

* IP Calculator [https://jodies.de/ipcalc](https://jodies.de/ipcalc)
* IP Subnet Calculator [https://www.calculator.net/ip-subnet-calculator.html](https://www.calculator.net/ip-subnet-calculator.html)

## 4.3 Passerelle (gateway)

En informatique, une passerelle (en anglais, gateway) est un dispositif permettant de relier deux réseaux informatiques différents, comme par exemple un réseau local et l'Internet. Ainsi, plusieurs ordinateurs ou l'ensemble du réseau local peuvent accéder à l'Internet par l'intermédiaire de la passerelle. Le plus souvent, elle sert aussi de pare-feu, ce qui permet de contrôler tous les transferts de données entre le local et l'extérieur.

Elle ne doit pas être confondue avec un pont (couche 2) ou un routeur (couche 3).

**Routeur**

Son travail est de limiter les domaines de diffusion et de déterminer le prochain noeud du réseau auquel un paquet de données doit être envoyé, afin que ce dernier atteigne sa destination finale. Ce processus nommé routage intervient à la couche 3 (couche réseau) du modèle OSI. Il permet de changer de support et protocole et de ce fait change les trames (adresses)

**Passerelle**

Une passerelle (en anglais, gateway) est un dispositif permettant de relier deux réseaux informatiques différents. Ainsi, plusieurs équipements peuvent accéder à l'autre réseau par l'intermédiaire de la passerelle. Ce processus intervient à partir de la couche 4 (couche transport) du modèle OSI et peut modifier la trame jusqu'à la couche 6.

Cette différence est très importante quand on inter-connecte des réseaux de nature différente. Une passerelle permet de faire communiquer des réseaux hétérogènes. Cette notion est très importante en réseaux de terrain.

Cependant, le terme passerelle (sans autre précision) est couramment employé comme exact synonyme du terme routeur[1], par exemple dans le routage on parle de passerelle par défaut (default gateway) ou dans Interior Gateway Protocol, Border Gateway Protocol alors qu'il ne s'agit clairement que de routage au niveau IP, il est donc utile de préciser que l'on parle de passerelle applicative par exemple pour éviter toute ambiguïté.

Commande afficher la passerelle par défaut:
```bash
$ route -N
```


## 4.4 Analyse de réseaux

### CLI outils

ip
ping
whois
nslookup
host
dig
netstat
ss
nc
route
traceroute
nmap
ssh
curl
mtr
iftop

### Sniffers réseaux

### TCPDUMP

### Wireshark

### GNS3

Comme en développement d’applications, l’architecture de systèmes et réseaux, même simple, nécessite de réaliser des tests avant le lancement en production. Cette bonne pratique est indispensable pour vous éviter de nombreuses erreurs en production qui viendraient gâcher le quotidien de vos collaborateurs !

Pour cela, je vous propose de maîtriser les bases du simulateur [GNS3](https://gns3.com/) (Graphical Network Simulator). Cet outil simple et intuitif vous permettra de créer vos réseaux, les tester, les installer et paramétrer des switchs, des routeurs, et même des serveurs.  Le simulateur GNS3 vous permet en effet de connecter  également votre hyperviseur de machines virtuelles depuis Vmware ou virtualbox. En bref, vous pourrez architecturer vos réseaux simples et complexes, et les simuler virtuellement, comme si vous y étiez !

[Maitrisez les fonctionnalités de base de GNS3 - OpenClassRooms](https://openclassrooms.com/fr/courses/2581701-simulez-des-architectures-reseaux-avec-gns3/4823151-maitrisez-les-fonctionnalites-de-base-de-gns3)

## 4.5 Par-feu

## 4.6 WIFI

## 4.7 ARP

## 4.8 DNS

## 4.9 SMB

## 4.10 FTP

## 4.11 SMTP

## 4.12 SNMP

## 4.13 HTTP

## 4.14 SCADA / ICS

## 4.15 Proxy

## 4.16 VPN

## 4.17 TOR

# 5. Cyberdefense
---

## 5.1 Méthodologie pour sécuriser son ordinateur

On arrive à la fin d'un âge avec la prolifération des attaques informatiques ou l'utilisateur n'était qu'un consommateur ou celui-ci doit maintenant reprendre le contrôle de sa machine. Pour ce protéger, il n'y a pas beaucoup de méthode à appliquer à part celle-ci:  

```
A armes égales, et donc une militarisation du cyberespace.  
```

Vous ne pouvez pas protéger de l'information et votre organisation, car beaucoup d'entreprise font faillite après une attaque informatique, et être productif sur votre poste de travail sans penser comme un hacker. Même si les hackers le savent très bien la faille est principalement humaine et l'ingénierie sociale reste l'art de duper son adversaire pour l'exploiter. C'est aussi vaincre par votre niveau de connaissance des pratiques de sécurité sur les systèmes et le renseignement sur le terrain tel que la veille.  

On voit qu'au niveau de la prolifération des méthodologies d'attaques, les hackers cybercriminels recherchent à monnayer des secrets. Entrée sur des bases de donnée, récupérer des informations de clients, mot de passe, d'informations bancaires, des portes-feuilles de cryptomonnaies. Les infostealers sont par exemple en pleine expansion. On est loin des APT (Advanced Persistant Threat) tel que le célèbre Stuxnet pour endommager des structures qui reste rare tel que sur les SCADA dans l'industrie pour rendre inopérant une cible. La technique également qui fait parler d'elle le ransomware pour faire chanter les organisations de payer une rançon en bloquant l'accès à ces documents numériques, sous peine de destruction depuis l'épidemie de l'attaque Wannacry (2017) et la vulnérabilité Eternal Blue. Internet à basculé après l'attaque par botnet Mirai (2016) ciblant l'internet des objets. Microsoft a vu tout son système d'authentification mis à l'épreuve avec Mimikatz (2012).  

Présentons donc une méthodologie pour ce protéger des hackers et éduquer au numérique, ce que l'on apprend pas à l'école, nos politiques veulent surveiller la population, que le flic puisse enquêté sur votre ordinateur pour trouver vos photos pedopornographiques, ou vos activités illégales, ils sont totalement obsédés par l'accès aux systèmes informatiques par les services de renseignement.  

### Ne faite confiance qu'à l'open source  

La règle est de rendre le code source ouvert pour auditer permettant sa maintenance et son amélioration. Un système propriétaire permet d'intégrer des backdoors pour espionner qui est une atteinte à la vie privée, ainsi que de la télémetrie pour exploiter vos données. Les gouvernements favorisent l'utilisation des systèmes propriétaires pour cette raison sur l'ingénierie logiciel. Donc oublié MacOS et Windows, passé à GNU/Linux. La NSA a tenté de backdoorer le noyau Linux, sans succès.  

### Réduire la surface d'attaque  

N'allez pas vers des systèmes qui sont infecté par des virus et malwares, + 96% des malwares sont sur Windows. Linux n'est touché qu'à hauteur de 1% par les ransomwares. Ce qui est mainstream est plus vulnérable. Le système d'exploitation le plus sécurisé au monde est un UNIX libre: openBSD. Préférer le minimalisme, n'installer que le strict nécessaire sur le système tel que des distributions sur mesure comme Arch Linux ou Gentoo. Linux est vulnérable, et Debian en 20 ans à générer un nombre important de CVE qui sont patché régulièrement, un code open source permet à n'importe qui de chercher des vulnérabilités. Alléger votre bootloader et activer le secure boot de l'UEFI pour empêcher au démarrage du code inconnu comme l'attaque ["Evil Maid"](https://www.schneier.com/blog/archives/2009/10/evil_maid_attac.html). Réduiser votre utilisation d'application avec une interface graphique GUI et utiliser des serveurs d'affichage plus sur tel que Wayland. Vous serez plus productif et sécurisé en utilisant le terminal en CLI.  

### Le chiffrement  

Le système doit être protégé par le chiffrement avec des outils tel que dm-crypt/ LUKS pour protéger vos documents sensibles et information de connexion, voir de porte-feuille de cryptomonnaie. La connexion réseau doit également être chiffré via SSL et TLS en forçant HTTPS, pour éviter des attaques de type MITM, souvent le VPN est préconisé. Quand vous chercher à à vous connecter à des mirrors et repository sous Arch Linux en utilisant reflector forçé la connexion HTTPS. Préconiser l'utilisation de clé de chiffrement pour vous connecter en remote sur un serveur distant. Vous devez savoir utiliser GPG mais également de créer des containers Veracrypt en applicant la sécurité par l'obscurité. Ayez des notions sur le hashage, les mots de passe ne doivent pas exister en clair dans une base de donnée.  

### Contrôle d'accès  

Les programmes malveillants cherchent à escalader les privilèges pour prendre le contrôle de la machine. Le système doit protéger les actions de modification tel que le compte administrateur avec un mot de passe comme root sous Linux. Ainsi vous devez avoir des mots de passe différent en fonction du niveau de privilège sur le système en cas de compromission:  

*   1 mot de passe pour la partition chiffrée + 16 caractères  
    
*   1 mot de passe pour le compte administrateur root + 12 caractères  
    
*   1 mot de passe sur chaques sites webs différents et dynamique + 8 caractères  
    

Vous devez utiliser un gestionnaire de mot de passe comme Keepass et garder la base de donnée en local sur votre machine. Ne jamais faire confiance au cloud et un tiers-parti en intermédiaire ou les données sont stocké à distance. Votre mot de passe doit être résistant à des attaques par dictionnaire et brute force.  

### Utilisez un gestionnaire de paquet  

Vous devez avoir une source de confiance pour les logiciels sur des dépots distants que vous installez et vérifiez qu'ils ne sont pas corrompu tel que la signature GPG du mainteneur. D'ou l'utilisation de GNU/Linux, comme pacman, rpm, apt, emerge, etc.  

### Auditer le système  

Les vulnérabilités CVE sont régulièrement mise à jours, la dernière en date "Dirty Pipe" sur le noyau Linux à fait parler d'elle, vous devez auditer le système avec des outils tel que Lynis et appliquer des contres-mesures d' "hardening" en particulier sur le noyau Linux comme AppArmor, SELinux, Grsecurity et LKRG. Il faut faire une recherche de rootkit régulièrement avec chkrootkit mais également de malware, il y en a sur Linux en utilisant Yara avec des règles prédifinis comme le repo ["Protections Artifacts"](https://github.com/elastic/protections-artifacts) d'Elastic Security.  

### Rolling Release pour mettre à jours le système  

Patcher le système dès que les paquets logiciels sont disponible en intégrant la rolling release. C'est la particularité des distributions GNU/Linux basé sur Arch Linux, tel que Manjaro, Archcraft, etc.  

### Monitoring  

Vous pouvez détecter des comportements anormaux sur votre système en faisant du monitoring sur les ressources en particulier les processus et l'outil htop, mais également sur le réseau car les programmes malveillants cherchent à communiquer avec l'extérieur pour extraire de l'information et l'utilisation de port (ssh, samba, http, etc) et l'outil ss ou netstat. Il est possible d'analyser les paquets avec l'outil tcpdump.  

### Logs  

Un programme malveillant doit être furtif et les hackers effacer leur trace sur la cible. Pourtant ils peuvent laisser des empreintes sur les accès sur le système en vérifiant les logs. Windows n'a toujours pas compris ça et Linux intègre un système de logs avancé tel que sur les services avec systemd et journalctl voir l'outil syslog-ng.  

### Configurer un par-feu

Utilisez des outils comme ufw qui reste simple à configurer, vous n'avez pas besoin d'apprendre des outils compliqué comme iptable ou pfsense.

### Sauvegarde et restauration  

De nos jours les systèmes les plus avancés intègrent un système de sauvegarde automatisé périodique en cas de compromission. La technique utilisé en particulier est les snapshots qu'il est possible de créer avec des systèmes de fichier comme BTRFS et des outils comme Snapper + snap-pac sur Arch Linux pour sauvegarder à chaque mise à jour en cas que vous casser le système pour le restaurer. Il faut coupler à une sauvegarde de l'environnement utilisateur tels que les .dotfiles et les documents en utilisant des outils pour chiffrer des sauvegardes dans le cloud ou sur un NAS. Il y a Duplicity, Borg, Bacula mais également Rsync ou Rclone. En règle général il faut une sauvegarde locale + distante. En cas de perquisition ou de vol à votre domicile, vos données doivent être disponible à distance.  

### Conclusion  

En terme de pratique de sécurité sur les ordinateurs, Windows c'est le moyen-âge et MacOS par son caractère propriétaire n'est pas une source de confiance pour l'audit du code. Quand on connait rien à l'informatique et que l'on ne veut pas trop s'en occuper, je conseil le chromebook qui est un Gentoo allegé mais vous êtes dépendant des GAFAM comme Google et ces services. Les pratiques de cybersécurité sont un héritage des administrateurs systèmes de serveur et donc l'utilisation de GNU/Linux sur le marché quand on cherche à maintenir une disponibilité de l'outil de production et des services.

## 5.2 Complément sécuriser son ordinateur

En 2013, avant l'affaire Snowden, je me suis lancé en tant que consultant indépendant sans réseau dans le milieu à 24 ans pour devenir expert en cyberdefense. Je suis un cipherpunk, c'est à dire je fais la promotion de l'utilisation de la cryptographie pour la défense de la vie privée, contre le vol de donnée, le secret industriel, la protection des sources. Je recherchais à être une aide au dirigeant plus particulièrement.

Je vais donc expliquer ici quelques principes de cyberdéfense, on va construire un sous-marin pour naviguer en furtif, qui sont ma valeur ajouté sur le marché du travail. Mes recherches sont utiles dans l'armement, l'industrie, le journalisme mais egalement dans l'hacktivisme, la cybercriminalité, le terrorisme ou les réseaux mafieux. Il ne faut pas ce voilé la face. 

* Installer un système d'exploitation en vérifiant l'[intégrité de l'image ISO](https://linuxhint.com/md5_sha1_sha256_checksum_iso/) tel qu'il est possible sous Linux grâce à l'empreinte checksums MD5, sha1, sha256

* Ne faites confiance qu'à Linux car le code source est ouvert et donc auditable. Les Etats et la sécurité intérieur pour des besoins d'enquête et de fichage de la population ont des portes dérobées dans les produits Microsoft Windows et Appel macOS qui sont des sources propriétaires. Le code malveillant peu y être injecté. Il y a une volonté de rendre vulnérable le système. Le noyau Linux a été plusieurs fois approché par la NSA pour intégré une porte dérobée, ils rêvent complètement. 

* Préférer des systèmes minimalistes comme Arch Linux, Gentoo, ou vous installer/compiler depuis les sources vous même les paquets nécessaires. Eviter d'installer quelque chose que vous ne comprenez pas. 

* [Chiffrer votre disque dur](https://wiki.archlinux.org/title/Data-at-rest_encryption). Je m'attarde pas sur l'etat de l'art et les discussions s'il faut chiffrer /boot /tmp et la /swap. Cela enflamme souvent internet en fonction des failles et vulnérabilités.

* Utiliser des dépôts logiciels avec une signature PGP qui permet d'avoir des sources de confiance. Chiffrer votre connexion internet en HTTPS pour récupérer les mirroirs des repository. Cela évite les attaques APT mais egalement l'installation de keylogger ou de trojan. J'utilise Arch Linux et le gestionnaire de paquet [pacman/signing](https://wiki.archlinux.org/title/Pacman/Package_signing) qui gère en natif. [Reflector](https://wiki.archlinux.org/title/Reflector) force la connexions en HTTPS vers les sources. 

* Installer un par-feu tel que `ufw` et son interface graphique `gufw` Apprenez à configurer des règles

* Vérifier les logs dans `/var/log` et installer `syslog-ng`

* Installer un analyseur de rootkit `rkhunter`

* Monitorer le système pour analyser des programmes ou script qui utilise du CPU, mémoire ou du réseau avec `htop` `iostat` `ss`

* Faite de la sécurité par l'obscurité en créant des containers avec [Veracrypt](https://www.veracrypt.fr/en/Home.html) pour déposer vos documents TOP secret

* Politique de gestion de mot de passe avec `Keepass`, permet de générer des mots de passe fort

* Installer un VPN gratuit comme protonVPN, utiliser le service mail sécurisé.

* Utiliser des services cloud sécurisés tel que MEGA.

* Augmenter votre vie privée avec le navigateur [librewolf](https://librewolf.net/), un fork de Firefox voir utilisé tor browser.

* Soyez furtif sur internet derrière des noeuds tor et plusieurs proxy avec `proxychains` pour vos activités sensible. Vérifier que la connexion à un site est en HTTPS en particulier les banques et utiliser un VPN si nécessaire.

* Faite une veille des vulnérabilités et CVE. Via [https://www.cert.ssi.gouv.fr/](https://www.cert.ssi.gouv.fr/)

* Mettez à jour votre système, préférez la rolling release comme Arch Linux qui publie les mises à jours de paquet en continue sur son site. Dès qu'un paquet est patcher pour une vulnérabilité faite la commande: `sudo pacman -Syu`

* Sauvegarder incrémentalement votre système. Configurer des snapshots avec un système de fichier BTRFS. Prévoyer un NAS (Synology) pour vos sauvegardes local sur le serveur samba synchronisé dans le cloud à distance grâce à la fonction hyperbackup de Synology. Redondance de la sécurité pour assurer une sureté de fonctionnement. Utiliser l'utilitaire `deja-dup` de duplicity qui est simple pour chiffrer ces sauvegardes. Il existe d'autres programmes plus complexe comme Borg Backup ou Bacula.

* Automatiser la ré-installation si le système est compromis avec des scripts et sauvegarder vos fichier [dotfiles](https://www.freecodecamp.org/news/dotfiles-what-is-a-dot-file-and-how-to-create-it-in-mac-and-linux/) tels que .zshrc , .vimrc , .gitconfig

* Garder une clé de System Rescue tel que l'image d'Arch Linux. Booter sur la clé puis: Ouvrir le container chiffré LUKS, Monter les disques, chrooter l'environnement et faite la réparation nécessaire.

Tout cette procédure, je forme à la cyberdefense, c'est des années d'utilisation, de test et d'expérience des meilleurs pratiques. Ce qui est maintenant avant-gardiste, le cipherpunk sera la norme après que la cyberguerre aura détruit le système actuel, depuis Snowden cela a empiré, tous les états veulent leurs hackers sponsorisés pour voler des données, c'est un foutoir infernal et c'est politique. La cyber-armée est une vaste fumisterie. Nos futurs générations apprendrons à créer leur propre système et le customiser, nous sommes des pionniers, des visionnaires pour d'autre. Le coup fatal sera portée par l'internet quantique, on attend avec impatience que les politiques acceptent d'abandonner la surveillance pour rendre inviolable les communications. Let's Encrypt est l'une des initiatives post-Snowden de chiffrer les connexions HTTPS gratuitement avec des certificat, aucun gouvernement n'a soutenu l'initiative, nos politiques sont déconnecté de la problématique, ainsi que l'élite pensante tel que le corps des Mines, étant un ancien mineur, on ne forme pas à Linux en école d'ingénieur. La plupart des experts en cyberdefense sont complètement à l'ouest recommandant toujours plus de logiciel propriétaire payant pour faire des fonctions de sécurité. Le déni complet car c'est un gros business la cybersécurité: Si le code source n'est pas ouvert, et qu'il faut une licence, c'est de la merde pour faire du profit.Je ne suis pas seul, il y a les cipherpunks, la communauté Arch Linux, la Quadrature du Net. 

Je finirais l'article cette article par les outils d'hardening sous Linux pour éviter de compromettre un système. voir un IDS comme Snort que vous devez connaitre en cyberdefense.

* Bastille Linux [http://bastille-linux.sourceforge.net/](http://bastille-linux.sourceforge.net/)
* Lynis [https://cisofy.com/lynis/](https://cisofy.com/lynis/)
* nixarmor [https://github.com/emirozer/nixarmor](https://github.com/emirozer/nixarmor)
* Linux server hardening guide [https://github.com/imthenachoman/How-To-Secure-A-Linux-Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server)


## 5.3 Tips de furtivité

De nos jours tous le monde espionne, c'est à la portée du clic car chacun essaye de valoriser de la DATA. Le business sur les données, est le nouvel eldorado, 99% de l'information est en source ouverte sur internet. Traiter ces données demande du temps, alors on automatise la tâche avec des programmes informatiques, l'une des techniques les plus courantes est le web scraping (harvesting).  

Quand vous êtes hackers ou journaliste vous aller avoir une phase de RECON pour collecter des informations sur une entreprise, un individu. Si vous êtes chercheur en sécurité informatique vous pouvez trouver des vulnérabilités sur les serveurs ou les individus par une analyse du discours et des formes d'ingénierie sociale comme levier pour obtenir une escaladation de privilège.  

Vous allez prendre beaucoup de notes et croiser l'information, il vous faut donc des outils de Knowledge Management, j'utilise personnellement [Zim](https://zim-wiki.org/). Un wiki pour organiser l'information. Pas besoin d'outils sophistiqué, vous pouvez complémenter avec [freemind](https://freemind.fr.softonic.com/) pour créer des cartes heuristiques comme méthode de brainstorming. Ces données elles ont de la valeur, une entreprise concurrente serait intéresser de les obtenirs ou des organismes gouvernementaux plus particulièrement si votre travail touche à de l'armement.  

Il faut donc avoir des principes de FURTIVITE quand on collecte de l'information ou squatte un serveur qui ne vous appartient pas, vos activités de [footprinting](https://fr.wikipedia.org/wiki/Footprinting) peuvent alerter des organisations et accentuer la surveillance sur votre connexion internet. Comment y remédier?  

* Générer des DATA aléatoires. Votre FAI collecte des données de navigation et les revends à des entreprises pour faire de la publicité ciblée. Vous pouvez y remédier en générant des données aléatoires sur votre réseau avec Arduino et [APAN](https://projecthub.arduino.cc/cstram/apan-arduino-privacy-automatic-navigator-4e0245) pour 20 €. C'est la technique de la confusion.  

* Utiliser proxychains. Certains hackers se protègent derrière plus de 7 proxys avant de scanner et collecter de l'information sur une cible sensible. Il est configurer par défaut pour fonctionner avec TOR. C'est un outil réputé sous GNU/Linux.  

* Classique via un VPN + TOR. C'est la protection adéquate quand on veut anonymiser sa navigation dans le dark web, je vais pas rentrer dans le détail pourquoi il est nécessaire de coupler un VPN avec TOR mais il y a des fuites d'informations sur les noeuds d'entrée et sortie sur le réseau. Il y a de la littérature abondante sur les raisons de tels précautions. Vous devez prendre des précautions sur le choix du VPN pour réduire votre empreinte. protonVPN qui est gratuit est une solution configurable sous GNU/Linux à condition d'utiliser le bureau GNOME dont il est dépendant. J'ai réussi à faire fonctionner sous XFCE après quelques bidouilles.

## 5.4 Générer une paire de clé PGP

Tout utilisateur avancée de l'informatique protège son travail avec de la cryptographie et ces communications. C'est le domaine et le monde des cipherpunks. Globalement internet utilise de plus en plus la cryptographie pour:

* Sécuriser les transactions financières
* Protéger l'intégrité des données
* Rendre les communications privées
* Sécuriser l'authentification

Il faut donc avoir quelques notions pour l'utilisateur averti d'un outil essentiel : openPGP qui utilise la méthode [chiffrement asymétrique](https://fr.wikipedia.org/wiki/Cryptographie_asym%C3%A9trique). Le créateur de PGP(Pretty Good Privacy), 	Philip Zimmermann, a été violamment réprimandé par les gouvernements, à l'origine ceux-ci ne veulent pas que la population est accès la cryptographie. Zimmermann à violé le "Arms Export Control Act" des USA. La cryptologie est une arme de guerre.

Citation de Zimmermann: « If privacy is outlawed, only outlaws will have privacy », soit, en français : « Si la vie privée est mise hors la loi, seuls les hors-la-loi auront une vie privée. »

Comment utiliser PGP et le chiffrement asymétrique? Il faut savoir qu'une clé RSA peut être utilisé que cela soit pour openSSL ou openPGP / GnuPG.

Nous allons l'utiliser pour chiffrer nos messages sur un email et servir d'authentification sécurisé tel que pour maintenir un logiciel et la signature du mainteneur dans les dépôts sous GNU/Linux.

* 1] Tout d'abord créer un email généraliste ou l'on peut utiliser PGP et intégrer des API. Un compte webmail Gmail est suffisant, ne vous inquietez pas si l'email est sur les serveurs de Google, ils n'ont pas accès aux emails chiffrés. 

* 2] Utiliser un outil pour générer des clés PGP public et privée. Mettez un mot de passe, taille de la clé 4096 bits, et algorithme RSA. Pas de temps d'expiration tel que sur [https://pgptool.org/](https://pgptool.org/), vous pouvez également utiliser l'utilitaire [GnuPG](https://www.linuxfordevices.com/tutorials/linux/generate-pgp-keys-gnupg). Récuperez les fichiers, rappel votre clé privée est personnel et ne se partage pas, elle doit être protégée sur une partition chiffrée.


* 3] Utilisez un outil qui gère la signature PGP pour les emails. Vous pouvez utiliser le client Thunderbird avec Enigmail. Mais egalement un webmail Gmail avec [Mailvelope](https://www.malekal.com/utiliser-pgp-sur-gmail-pour-le-chiffrement-de-mail/).


* 4] Rendre votre clé public accessible pour authentifier votre signature. Il y a des serveurs généralistes qui collecte les clés, en particulier sur GNU/Linux pour la signature des dépôts. Ainsi transféré votre clé sur le serveur d'Ubuntu en copiant votre clé public. Aller sur [https://keyserver.ubuntu.com/](https://keyserver.ubuntu.com/). Il y a également le serveur du MIT [https://pgp.mit.edu/](https://pgp.mit.edu/) mais également sur [https://keys.openpgp.org/](https://keys.openpgp.org/). Les serveurs sont synchronisés entre eux.


* 5] Partager le lien de votre clé public pour pouvoir l'utiliser. Comment est formaté un lien public vers une clé PGP?


C'est sous la forme: `nom + mail + signature` exemple pour ma propre clé: [Anthony Le Goff legoff.ant@gmail.com 0x6F3B7C4C](https://keyserver.ubuntu.com/pks/lookup?search=0x6F3B7C4C&fingerprint=on&op=index)


Bienvenue dans le monde des cipherpunks.

## 5.5 Authentification serveur distant clé SSH (methode Github)

Créer un repository ou réutiliser un autre.

### Vérifier l’existence de clés ssh sur le PC 

Lancer la commande `ls -al ~/.ssh` pour lister les clés.

Vérifier le dossier s’il existe des clés ssh publique nommé:
* id_rsa.pub 
* id_ecdsa.pub
* id_ed25519.pub

### Générer la paire de clés ssh

Ouvrir un terminal

Lancer la commande:
```bash
$ ssh-keygen -t ed25519 -C "your_email@example.com"
```

### Ajouter un clé ssh au compte github

Faite un `cat` sur le chemin de votre clé public dans le dossier `~/.ssh/` et copiez le.
Ajoutez la clé sur le compte github à (https://github.com/settings/keys)

### test la connexion ssh sur le serveur de github

ouvrir un terminal
```bash
$ ssh -T git@github.com
# Attempts to ssh to GitHub
```
Il y aura une information de reconnaissance de signature de clé public

### Switch de https a ssh en remote

Aller dans le dossier de travail du projet git.
Configurer l’URL de remote par ssh 
```bash
git remote set-url origin git@github.com:username/your-repository.git
# puis vérifier que cela a bien été pris en compte
git remote -v
```

commiter un fichier puis pusher le code. l’identifiant et le mot de passe ne sera pas demandé 

# 6. Sauvegarde
---

## 6.1 Mise en place de sauvegarde

Il est important à toutes utilisation avancée de l'informatique de faire des sauvegardes et d'automatiser cela. Je vais expliquer ma méthode la plus simple pour sécuriser ces sauvegardes de document de travail ou entreprise.

Pour cela vous allez devoir investir un peu sur votre réseau informatique dans une NAS. Un NAS est un serveur de fichier, il sert en particulier pour faire des sauvegardes locales et distantes.

Je vous demande pas d'investir cher, le matos:

* [NAS Synology DS223J à 234€](https://www.ldlc.com/fiche/PB00559191.html)
* [2 x HDD 1TO NAS Seagate Iron Wolf à 69€](https://www.ldlc.com/fiche/PB00214990.html)

Il va falloir paramtrer votre réseau local pour accéder au NAS et monter le disque via le protocole Samba (SMB). Pour faciliter la tâche je conseil d'utiliser des explorateurs fichiers tel que Thunar qui intègre des outils. Sinon On passe en ligne de commande:

#### Installation du client SAMBA

```bash
$ sudo pacman -S smbclient gvfs-smb
```
Redémarrer le PC pour prendre en compte la découverte du réseau local.

GUI: Ensuite rechercher votre serveur dans thunar en tapant:
```text
smb://192.168.X.X
```

Terminal: Monter le serveur SMB:

List SMB shares folders
```bash
$ smbclient -L //myServerIpAdress
```

Créer le point de montage:

```bash
sudo mkdir -p /media/NAS
```

Commande de montage
```bash
$  mount -t smbfs -W workgroup //user:password@IPSERVER/shares /media/NAS
```

OU

```bash
$ gio mount smb://<server>/<share>
```

Autres méthodes [8 ways to mount smbfs samba file system in linux](https://www.linuxnix.com/8-ways-to-mount-smbfs-samba-file-system-in-linux/)

Penser à éditer `fstab' pour ajouter le serveur SMB en permanence. Ex:
```bash
$ vim /etc/fstab
//192.168.0.1/share1 /media/NAS smbfs rw,user,username=trivial,password=xylBJRS8 0 0
```

```bash
$  sudo mount -a
```

#### Deja-Dup

Ensuite vous aller devoir utiliser un client pour faire vos sauvegardes incrémentales et les chiffrer. J'utilise Deja-Dup qui est un front-end pour duplicity. Il suffit de mettre votre volume SMB dans les paramètres.Deja-Dup est simple d'utilisation, et idéal pour la tâche. Il sauvegarde automatiquement toutes les semaines vers le NAS. 

#### Sauvegarde vers le cloud

Il est très utile de faire une sauvegarde distante hors de votre maison, pour plusieurs raisons, en cas de perquisition, ou vol de donnée voir d'incendie. Pour cela Synology intègre un outil qui s'appel [hyperbackup C2](https://www.synology.com/fr-fr/dsm/feature/hyper_backup) pour une offre à 60€/an. Qui vaut largement le coût.

#### Autres outils

Vous pouvez vous renseigner vers d'autres outils tel que Bacula, Borg backup ou encore Rclone qui sont également de bon outils mais parfois complexe à utiliser.

## 6.2 Snapshot BTRFS

Il est intéressant au cas ou le système plante sur une mise à jour ou une malveillance dans le système d'avoir des points de restauration via des snapshots que permet le système de fichier BTRFS.

Vous pouvez utiliser l'outil [Snapper](https://wiki.archlinux.org/title/Snapper) pour paramêtrer.

Egalement je peux conseiller de créer un petit script bash pour automatiser la tâche:

**On va donc automatiser nos sauvegardes de DATA tous les jours en utilisant un script shell et un plannificateur de tâche cron en cas de plantage du système.**

#### On commence par vérifier nos subvolumes btrfs
```bash
$ sudo btrfs subvolume list /

ID 256 gen 7527 top level 5 path @
ID 257 gen 7528 top level 5 path @home
ID 258 gen 9 top level 5 path @_snapshot
ID 259 gen 17 top level 256 path var/lib/portables
ID 260 gen 18 top level 256 path var/lib/machines
```

#### On va créer notre dossier de scripts utilisateurs et le script bash
```bash
$ mkdir ~/scripts
$ mkdir ~/scripts/logs
$ touch ~/scripts/logs/snap-logs

$ nvim btrfs-snapshot-backup.sh

#! /usr/bin/bash

# Dossier pour sauvegarder snapshot
SNAPDIR=/@_snapshot
export SNAPDIR

# Supprimer toutes les snapshots présentent sur le disque
sudo btrfs subvolume delete $SNAPDIR/home_*

# Prendre une snapshot
sudo btrfs subvolume snapshot -r /@home $SNAPDIR/home_$(date +%Y%m%d)

# Check si la snapshot a bien été créer, sinon exit et report
if [ $? -ne 0 ]
then
echo "Erreur pour créer la snapshot home_$(date +%Y%m%d)" >> ~/scripts/logs/snap-logs
exit 1
fi
```

#### Rendre executable le script bash
```bash
$ chmod u+x ~/scripts/btrfs-snapshot-backup.sh
```
#### On utilise un plannificateur de tâche "Cron" pour lancer le script tous les jours à 11:22
```bash
$ sudo crontab -e
$ sudo nvim /etc/crontab

22 11 * * * trivial /home/trivial/scripts/btrfs-snapshot-backup.sh
```

#### Ajoute les droits admins sur les scripts dans sudoers
```bash
$ sudo EDITOR=nvim visudo

trivial ALL=(ALL) NOPASSWD:	 /home/trivial/scripts/*
```

#### activation du service daemon au démarrage du système
```
$ sudo systemctl enable crond.service
$ sudo systemctl reload crond.service
```

NOTA: améliorer le script, on peut définir une sauvegarde des snaphots et supprimer les plus anciennes de plus d'une semaine.

# 7. Programmation
---

## 7.1 Apprendre le C++ sur MCU Arduino R3

Arduino utilise un langage épuré à base de C. Il y a très peu de fonction et donc plus facile pour l'apprentissage. Durant un certain temps il fallait utiliser le logiciel Arduino IDE 1.0 qui était très limité pour programmer la carte de prototype électronique. Après  c'est simplifié, suffit d'installer le logiciel et tout marche, ainsi que le port série vers UNO. C'est la version pour les grands débutants et les newbies. Je rappel le lien utile pour apprendre Arduino UNO en libre accès [Arduino : premiers pas en informatique embarquée \[PDF\]](https://eskimon.fr/extra/ebooks/arduino-premiers-pas-en-informatique-embarquee.pdf)  

On va passer à la méthode professionnel chez les développeurs et ingénieurs en systèmes embarqués et microcontrôleurs MCU en utilisant le workflow:  

*   **PlatformIO** is a cross-platform, cross-architecture, multiple framework, professional tool for embedded systems engineers and for software developers who write applications for embedded products.  
    
*   **(Neo)Vim** is a free and open-source, screen-based text editor program for use both from a command-line interface. Et donc d'utiliser des plugins tels que CoC (auto-completion), fugitive (integration de Git) etc.  
    
*   **Picocom** monitor the serial interface  
    

Ce qui permet une plus grande souplesse d'utilisation et de programmer en C++ avec des librairies customs via un éditeur de texte pour professionnel tel que Vim dans un terminal.  

### Installer PlatformIO CLI sur un environnement GNU/Linux (Arch Linux) en utilisant virtualenv en Python:  

```
$ sudo pacman -S python python-pip  
$ python -m pip install --user virtualenv
```
  

Puis installer le package platformio dans un dossier en activant l'environnement virtuel:  

```
$ mkdir -p ~/local
$ cd ~/local   
$ python -m venv platformio   
$ source platformio/bin/activate   
$ pip install platformio
```

NOTA: pour désactiver virtualenv: `$ deactivate`

Cela veut dire que les commandes de platformIO CLI sont disponible dans l'environnement virtuel dans le chemin PATH : `~/local/platformio/bin/pio`

### Rechercher le nom de la carte Arduino UNO R3:  
```
(platformio) $ platformio boards | grep uno
        uno                   atmega328p     16Mhz     31Kb    2Kb    Arduino Uno
```

### Créer un projet  

En l’occurrence on va appeler le projet 'blink' pour faire clignoter une LED sur Arduino pour vérifier que tout fonctionne.
```
$ mkdir ~/project/Blink
$ cd ~/project/Blink
$ pio project init --board uno --ide vim
```

générera un sous-dossier vide et un fichier projet (`platformio.ini`). Le format de `platformio.ini` est [fichier INI](https://en.wikipedia.org/wiki/INI_file).  

### Recherchez les noms des ports série:  

L'Arduino doit communiquer via une interface. Le micrologiciel intégré est téléchargé via le port série. La valeur par défaut est `/dev/ttyUSB0`, donc si vous connectez Arduino, la mise à jour échouera si elle est laissée telle quelle car le nom du port est différent. Par conséquent, il est nécessaire de vérifier le nom du port série et de le spécifier dans `platformio.ini`  

De plus il faut verifier les droits sur le port série, souvent on a pas les privilèges d'accès en écriture. Il faut ajouter l'utilisateur au groupe `uucp` sous Arch Linux(voir wiki Arduino):

```
$ sudo usermod -aG uucp username
```

Lister les ports de série:  
```
(platformio)$ platformio serialports list
        :   #réduction
        /dev/ttyACM0
        ----------
        Hardware ID: USB VID:PID=1a86:7523
        Description: QinHeng Electronics USB2.0-Serial
```

Dans cette exemple on utilise `/dev/ttyACM0` et donc il faut modifier `platformio.ini` avec Vim au paramêtre [upload_port](https://docs.platformio.org/en/latest/projectconf/sections/env/options/upload/upload_port.html)`  

### Ecrire la source

Le clignotement habituel de la LED et l'affichage en série. Mettez la source dans `./src`.  

```cpp

$ vim src/blink.cpp  


#include <Arduino.h>

void setup() {  
    pinMode( LED_BUILTIN, OUTPUT );  
    Serial.begin(9600);  
}  
   
void loop() {  
    Serial.println("Hello Arduino");

    digitalWrite( LED_BUILTIN, HIGH );    
    delay(333);                        
   
    digitalWrite( LED_BUILTIN, LOW );    
    delay(333);                        
}  
```

Dans le programme, il faut utiliser le header `Arduino.h` pour utiliser les librairies et fonctions de la carte. En C++ on utilise le mot clé void. Egalement j'utilise un print pour avoir un retour d'affichage de fonctionnement sur le monitoring du port série.  

### Essayer de compiler:  

La commande va télécharger le programme et flasher la carte UNO:  

```
$ pio run --target upload
```

Normalement la LED built-in devrait clignoter si tout fonctionne.

### Vim Quickfix Mode  

Pour intégrer avec Vim's quickfix mode un simple makefile suffit:  

```makefile

    .PHONY: all
    all: build
    
    
    .PHONY: build
    build:
        pio run
    
    .PHONY: upload
    upload:
        pio run --target upload
```

Ensuite vous pouvez automatiser la compilation en lançant la commande dans Vim `:make`

### Monitoring du port de série  

On va installer picocom pour le monitoring: 

```
$ sudo pacman -S picocom  
```

la commande pour monitorer  

```
$ picocom --baud 9600 --echo --noreset /dev/ttyUSB0
```

Qui devrait normalement retourner en affichage le print:

```
Hello Arduino
```
 
Plus d'information sur la doc officiel:` [https://docs.platformio.org/en/latest/index.html](https://docs.platformio.org/en/latest/index.html)

## 7.2 Préparation de projet avancée en C++

Ceci est un How-to pour créer un projet C++ et le faire dans les règles de l'art. On va utiliser les outils standards de la communauté FLOSS (Free Libre Open Source Software). Car j'éduque dans ce sens à l'ingénierie logicielle tout en apprenant des méthodes pour moi même. J'apprends et je partage les meilleurs pratiques dans mes recherches sur internet.

**Consigne du challenge:**

* Créer un jeu-video de 1978: SPACE INVADERS avec SFML en programmation orienté-objet.
* Adapter ce jeu avec l'OpenGL.

Vous allez me dire qu'es-ce que [SFML](https://www.sfml-dev.org/index-fr.php), c'est une librairie multimédias pour interfacer avec les composants du PC pour avoir de l’interactivité pour créer des applications de jeux-videos entre autre. La partie [OpenGL](https://www.opengl.org/) est le standard que l'on utilise pour de la haute performance graphique.

on aurait très bien pus s'arrêter là, mais on va développer notre projet avec des standards de l'ingénierie logicielle en gestion de projet pour prendre des bonnes habitudes. Je veux que vous soyez opérationnel en C++, alors on reprend les bases:

**Les outils**

* Editeur de texte: [Neovim](http://neovim.io/)
* Compilateur: [g++](https://gcc.gnu.org/)
* Documentation: [Doxygen](https://www.doxygen.nl/)
* Gérer la compilation du projet: [cmake](https://cmake.org/)
* Contrôle de version: [Git](https://git-scm.com/)
* Système d'exploitation: [Arch Linux](https://archlinux.org/)

Pour apprendre à coder en C++ on peut s'appuyer sur ces livres:

* Introduction to programming with C++ for Engineers
* Modern C++ for absolute beginners
* C++ Primer

Des sites références pour nous aider dans notre apprentissage:

* [Zeste du Savoir - Moderne C++](https://zestedesavoir.com/tutoriels/822/la-programmation-en-c-moderne/)
* [Learncpp](https://www.learncpp.com/)
* [Hackingcpp](https://hackingcpp.com/)

Ce que l'on va construire pour notre projet, un template avec une arborescence root "spaceinvaders":

```
.git
.gitignore
build/
docs/CMakeLists.txt , Doxyfile.in
src/CmakeLists.txt , *.cpp, *.hpp
CMakeLists.txt
README.md
LICENCE
```

**Paquets prérequis en particulier quelques librairies externes C++ utiles pour les développeurs et ingénieurs:**

```
sudo pacman -S base-devel neovim llvm clang git mesa glfw-x11 boost cmake doxygen eigen qt6-base sfml sdl2
```

* base-devel pour les outils de compilation GCC
* neovim votre éditeur de texte
* [llvm](https://llvm.org/) compilateur infrastructure
* clang C language family Frontend for LLVM
* git controle de version
* mesa open-source implementation of OpenGL
* [glfw-x11](https://www.glfw.org/) Free open source openGL portable framework
* [boost](https://www.boost.org/) Free portable C++ source library (dev headers)
* cmake cross-platform open-source make system
* doxygen Documentation system for C++
* [eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) C++ template lib for vector, matrix, linear algebra
* [sdl2](https://www.libsdl.org/) A library low-level access to a video framebuffer, audio output, mouse, keyboard
* [qt6-base](https://www.qt.io/product/qt6) A cross-platform application and UI Framework
* sfml A simple, fast, cross-platform, objet-oriented multimedia API

**Créer votre dossier** `sources` dans /home ou vous allez y mettre vos projets
```
$ mkdir ~/sources
```

### 1. Configurer Git

Nous allons d'abord configurer Git pour les nouveaux venus et apprendre le contrôle de version. Vous trouverez sur internet [des tutoriels](https://www.youtube.com/watch?v=lhiSnzrvG48) pour gérer votre code.

Dans un terminal >

**Votre identité**
```
$ git config --global user.name "Anthony Le Goff"
$ git config --global user.mail triviality-lga@protonmail.com
```

**Votre éditeur de texte**
```
$ git config --global core.editor nvim
```

**Votre nom de branche par défaut**
```
$ git config --global init.defaultBranch main
```

**Vérifier les paramètres**
```
$ git config --List
```

### 2. Générer des clés publiques SSH

Si vous le savez pas encore, l'authentification sous Github utilise maintenant SSH par défaut, il faut donc générer une paire de clé et l'ajouter dans Github pour ce connecter au dépôt distant.

```
$ cd ~/.ssh
$ ssh-keygen -o
```

Suivez la procédure et créer un mot de passe

Enfin pour récupérer la valeur de la clé publique généré à copiez sur Github:
```
cat ~/.ssh/id_rsa.pub
```

Copiez la clé sur un notepad en attendant.

### 3. Copiez la clé publique sur son compte Github

Créer un compte Github, si ce n'est déjà fait. Allez dans `settings/ssh and GPG keys/new SSH Key`. Collez la clé publique et valider.

### 4. Créer un repository

* Cliquez sur + en haut à droite puis "new repository".
* Dans repository name tapez: `spaceinvaders`. 
* Cochez: Add a README File
* Choisir add .gitignore template C++
* Choose a licence: GNU General Public Licence v3.0

Cliquez sur "Create repository" puis sur le bouton vert Code/ssh et copiez la ligne:
```
git@github.com:<monPseudo>/spaceinvaders.git
```

### 5. Cloner votre repository en local

Dans un terminal, allez dans votre dossier de travail projet `sources`:
```
cd ~/sources
```

puis cloner le repo git:
```
git clone git@github.com:<monPseudo>/spaceinvaders.git
```

Vous avez maintenant un nouveau dossier "spaceinvaders" avec quelques fichiers copiez depuis le dépôt distant Github.

### 6. Ignorer le dossier build sur le repo distant

Editer dans votre projet `spaceinvaders`:
```
nvim .gitignore
```

* Ajoutez au début `**/build/`
* Sauvegarder et quittez neovim


### 7. Configurer (Neo)Vim pour C++

Petit rappel pour les débutants. Pour ce familiariser avec Vim, lancer la commande dans un terminal `vimtutor`. Vous pouvez également apprendre à configurer Vim qui est un peu différent de Neovim avec le livre: [Vim pour les humains](https://vimebook.com/fr) en libre accès.

Une fois que vous êtes prêt avec Vim, apprenez de ces deux vidéos pour la suite:

1. [Setting up (Neo)vim for C++: A IDE like experience with coc!](https://www.youtube.com/watch?v=ViHgyApE9zM)
2. [Setting up (Neo)vim for C++: IDE like Files, CMake and GTest integrations!](https://www.youtube.com/watch?v=Y_UubM5eYAM)

N'oubliez pas de créer votre config file dans `~/.config/nvim/init.vim`

Mon propre init.vim pour information:
```bash
" Neovim configuration file init.vim
" author: Anthony J.R Le Goff 
" date: 16th april 2022

:set number
:set autoindent
:set tabstop=4
:set shiftwidth=4
:set smarttab
:set softtabstop=4
":set mouse=a

call plug#begin() 

Plug 'tpope/vim-fugitive'
Plug 'tpope/vim-surround'
Plug 'scrooloose/nerdtree'
Plug 'scrooloose/syntastic'
Plug 'vim-airline/vim-airline'
Plug 'tomasr/molokai'
Plug 'raimondi/delimitmate'
Plug 'kien/ctrlp.vim'
Plug 'ryanoasis/vim-devicons'
Plug 'majutsushi/tagbar'
Plug 'neoclide/coc.nvim', {'branch': 'release'}

set encoding=UTF-8

call plug#end()

:set statusline+=%#warningmsg#
:set statusline+=%{SyntasticStatuslineFlag()}
:set statusline+=%*

:let g:syntastic_always_populate_loc_list = 1
:let g:syntastic_auto_loc_list = 1
:let g:syntastic_check_on_open = 1
:let g:syntastic_check_on_wq = 0

nnoremap <C-f> :NERDTreeFocus<CR>
nnoremap <C-n> :NERDTree<CR>
nnoremap <C-t> :NERDTreeToggle<CR>

nmap <C-r> :TagbarToggle<CR>
nmap <C-p> :CtrlP<CR>

:colorscheme molokai

let g:NERDTreeDirArrowExpandable="+"
let g:NERDTreeDirArrowCollapsible="~"

" air-line
let g:airline_powerline_fonts = 1


" :CocInstall coc-python
" :CocInstall coc-clangd
" :CocInstall coc-java
```

### 8. Cmake + Doxygen

Pour vous familiarisez avec Cmake quelques ressources disponibles pour mieux comprendre les fichiers de configurations:

* (Video) [Simplified Cmake Tutorial](https://www.youtube.com/watch?v=mKZ-i-UfGgQ&t=25s)
* [Cours de Supelec sur Cmake](http://sirien.metz.supelec.fr/depot/SIR/TutorielCMake/index.html)

Nos fichiers de configurations pour notre projet:

spaceinvaders/CMakeLists.txt
```
cmake_minimum_required ( VERSION 3.10 )
set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
project(spaceinvaders version 1.0)
add_subdirectory(src)
add_subdirectory(docs)
```

spaceinvaders/src/CMakeLists.txt
```
# Dependance de librairie externe
find_package(SFML 2 REQUIRED network audio graphics window system)

add_executable(mainDemo main.cpp)
target_compile_options(mainDemo PUBLIC -Wall -Wextra)

# On install le binaire
install(PROGRAMS ${CMAKE_CURRENT_BINARY_DIR}/mainDemo
	DESTINATION bin
	RENAME ${CMAKE_PROJECT_NAME}-mainDemo)
	
# On construit le binaire avec SFML
target_include_directories(mainDemo PUBLIC ${SFML_INCLUDE_DIR})
target_link_librairies(mainDemo PUBLIC ${SFML_LIBRARIES} ${SFML_DEPENDENCIES})

# Librairie dynamique headers

add_library(mainDemo
	SHARED
	main.cpp)

install(TARGETS mainDemo
	DESTINATION lib)
	
file(
	GLOB
	headers
	*.hpp
)
```

**Préparation de la documentation**

On utilise le programme Doxygen pour générer le fichier de configuration dans le dossier `spaceinvaders/docs/`:
```
$ cd ~/sources/spaceinvaders
$ mkdir docs
$ cd docs
$ doxygen -g Doxyfile.in
```

On édite le fichier avec neovim pour le configurer avec cmake:
```
	  PROJECT_NAME           = ${CMAKE_PROJECT_NAME}
	  OUTPUT_DIRECTORY       = ${CMAKE_BINARY_DIR}/docs/
	  INPUT                  = ${CMAKE_SOURCE_DIR}/src
	  EXTRACT_ALL            = YES
```

spaceinvaders/docs/CMakeLists.txt
```
find_package(Doxygen)
if(NOT DOXYGEN_FOUND)
    message("Doxygen not found, I will not generate/install the documentation")
else()
   configure_file(Doxyfile.in Doxyfile)

   set(DOXYGEN_INPUT ${CMAKE_BINARY_DIR}/docs/Doxyfile.in)
   set(DOXYGEN_OUTPUT ${APIDOC_DIR}/html/index.html)

   add_custom_target(docs ALL
     COMMAND ${CMAKE_COMMAND} -E echo_append "Building API Documentation..."
     COMMAND ${DOXYGEN_EXECUTABLE} ${DOXYGEN_INPUT} > /dev/null
     COMMAND ${CMAKE_COMMAND} -E echo "Done."
     )

  install(DIRECTORY ${CMAKE_BINARY_DIR}/docs/html 
          DESTINATION share/doc/${CMAKE_PROJECT_NAME})

endif()
```

Pour la documentation, dans `docs` est généré un `index.html` avec les commentaires du code au format Doxygen depuis les fichiers sources. On peut ensuite envoyer sur un site online tels que [https://codedocs.xyz/](https://codedocs.xyz/) à partir de repository Github. Enfin renseignez-vous sur l'utilisation de Sphinx/breathe pour générer de la documentation également.

### 9. Compilation et installation

```
$ cd ~/sources/spaceinvaders
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./src/mainDemo
$ make install
```

### 10. Commiter votre code

Vous allez faire vos premiers commits de votre code. Il va falloir suivre des fichiers. Créer un `main.cpp` et `class.hpp` basics dans `src/` pour appeler une classe et faire un "hello world" pour tester si tout fonctionne.

**Suivi et Commit du code**

Dans votre dossier projet root `spaceinvaders` lancez les commandes:
```
$ git add . && git commit -m "commit init"
```

Pusher votre code sur Github
```
$ git push origin main
```

### 11. Pour aller plus loin

* Test unitaire avec [GTest](https://google.github.io/googletest/primer.html)
* Créer une archive `tar.gz`
* utilisez CPack/PkgBuild comme générateur de paquet pour Arch Linux

### Conclusion

Voila vous savez presque tout pour bien démarrer un projet avancée en C++ en développant un Space Invaders grâce à la librairie SFML en utilisant tous les outils nécessaire à une bonne organisation du projet. N'oubliez pas de commenter votre code! Après un mois on oublie souvent pourquoi on a créé une fonction, un algorithme ou une classe, donc soyez prévoyant en particulier sur des longs projets ou quand plusieurs personnes ce joint à vous pour du social coding. 

## 7.3 C++ Ecosystème

Ce sujet traite de l'éco-système C++ en allant aux outils à la communauté pour être plus productif dans le travail et devenir un développeur averti.

### Compileurs


**GCC g++**  

De facto le standard sous GNU/Linux:   

*   [https://gcc.gnu.org/](https://gcc.gnu.org/)  
    
*   sur Windows WinLibs: [https://winlibs.com/](https://winlibs.com/) et [WSL](https://docs.microsoft.com/fr-fr/windows/wsl/about)


**LLVM clang++**

Un compileur concurrent de GCC qui offre de meilleur performance  

*   [https://llvm.org/](https://llvm.org/)  
    


**Microsoft visual C++**  

Pour utiliser le C++ moderne il faut installer la dernière version du logiciel

*   [Documentation sur Microsoft C++, C, Assembleur](https://docs.microsoft.com/fr-fr/cpp/?view=msvc-170)
*   [https://visualstudio.microsoft.com/fr/free-developer-offers/](https://visualstudio.microsoft.com/fr/free-developer-offers/)  
    

  

### Compileurs online

Il est possible d'accéder sur internet à des compileurs en ligne

*   [https://godbolt.org/](https://godbolt.org/)  gcc, permet d'avoir une sortie en assembleur  
    
*   [https://coliru.stacked-crooked.com/](https://coliru.stacked-crooked.com/) gcc  
    
*   [https://wandbox.org/](https://wandbox.org/) inclus Boost, clang++, gcc  
    

### Debugging

**gdb**  

*   [https://www.sourceware.org/gdb/](https://www.sourceware.org/gdb/)  
    
*   [Intro to gdb](https://hackingcpp.com/cpp/tools/gdb_intro.html)
*   frontend DDD: [https://www.gnu.org/software/ddd/](https://www.gnu.org/software/ddd/)

**WinDBG**  

*   [Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)  
    

**x64dbg**

*   [https://x64dbg.com/](https://x64dbg.com/) Pour Windows, .DLL, .EXE etc...

### Code Analyseur

**ASAN(Adress SANITIZER)**  

*   [https://clang.llvm.org/docs/AddressSanitizer.html](https://clang.llvm.org/docs/AddressSanitizer.html)  
    
*   [Intro, détection de corruption mémoire](https://hackingcpp.com/cpp/tools/asan.html)

### Stand-alone outils d'analyse

**Valgrind**  

Valgrind est un outil de programmation libre pour déboguer, effectuer du profilage de code et mettre en évidence des fuites mémoires.  

*   [https://valgrind.org/](https://valgrind.org/)  
    
*   [Intro](https://hackingcpp.com/cpp/tools/valgrind.html)
*   [Quick Start](https://valgrind.org/docs/manual/quick-start.html)

### Profiling & Benchmarking

**GNU gprof**  

Gprof est un logiciel GNU Binary Utilities qui permet d'effectuer du profilage de code. Cela permet de détecter dans le code le temps d'éxécution qui demanderait à être ré-écrit.  

*   [https://sourceware.org/binutils/docs/gprof/](https://sourceware.org/binutils/docs/gprof/)  
    
*   [Tutorial](https://www.thegeekstuff.com/2012/08/gprof-tutorial/)

**Valgrind**  

*   cachegrind, callgrind
*   [https://valgrind.org/info/tools.html](https://valgrind.org/info/tools.html)  
    

**Perf**  

perf: Linux profiling with performance counters  

*   [https://perf.wiki.kernel.org/index.php/Main\_Page](https://perf.wiki.kernel.org/index.php/Main_Page)  
    
*   [Tutorial](https://perf.wiki.kernel.org/index.php/Tutorial)

### Documentation  

**Doxygen**  

Outil d'annotation et de création de documentation C++  

*   [https://www.doxygen.nl/index.html](https://www.doxygen.nl/index.html)  
    
*   [Documenter son code avec Doxygen](https://zestedesavoir.com/tutoriels/822/la-programmation-en-c-moderne/etre-un-developpeur/mais-ou-est-la-doc/#3-documenter-son-code-avec-doxygen)

### Benchmarking librairies / framework

**gperftools**  

Implementation du multi-threading pour malloc() haute performance  

*   [https://github.com/gperftools/gperftools/wiki](https://github.com/gperftools/gperftools/wiki)  
    
*   HEAP checker, CPU profiler

### Build Systems

**GNU Make**  

**Make** est un logiciel qui construit automatiquement des fichiers, souvent exécutables, ou des bibliothèques à partir d'éléments de base tels que du code source. Il utilise des fichiers appelés **makefile** qui spécifient comment construire les fichiers cibles  

S'utilise pour de petit projet, tous les développeurs devraient savoir faire un makefile.

*   [https://www.gnu.org/software/make/](https://www.gnu.org/software/make/)  
    
*   [Cheatsheet](https://devhints.io/makefile)
*   [Manuel](https://www.gnu.org/software/make/manual/make.html)

**CMake**   

_CMake_ est un outil permettant d'automatiser le processus de compilation et d'installation d'un logiciel.  

*   [https://cmake.org/](https://cmake.org/)  
    
*   Standard en C++
*   [A introduction to modern CMake](https://cliutils.gitlab.io/modern-cmake/)
*   [A template CMake project to get you started with C++ and tooling](https://github.com/cpp-best-practices/cpp_starter_project)  
    

### Test Unitaire

**Doctest**  

*   [https://github.com/doctest/doctest](https://github.com/doctest/doctest)  
    
*   [Tutorial](https://github.com/doctest/doctest/blob/master/doc/markdown/tutorial.md)

### Package management

**Conan**  

*   [https://conan.io/](https://conan.io/)  
    
*   Fonctionne avec CMake, MSbuild

### Source code management

**Git**  

*   Le standard dans l'industrie
*   [https://git-scm.com/](https://git-scm.com/)  
    

### Autres liens

*   [A curated list of awesome C++ (or C) frameworks, libraries, resources](https://github.com/fffaraz/awesome-cpp)  
    
*   [Toolchain ressource](https://www.toolchains.net/)

### Langage reference

**cppreference**

*   [https://en.cppreference.com/w/](https://en.cppreference.com/w/)  
    

### Best practices / Core guidelines

*   [https://github.com/cpp-best-practices/cppbestpractices/blob/master/00-Table\_of\_Contents.md](https://github.com/cpp-best-practices/cppbestpractices/blob/master/00-Table_of_Contents.md)  
    
*   [https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)  
    

### Social Media

**Reddit**  

*   C++ Communauté [https://www.reddit.com/r/cpp/](https://www.reddit.com/r/cpp/)  
    

**#include ＜C++＞**

*   Discord server [https://www.includecpp.org/discord/](https://www.includecpp.org/discord/)  
    

**Developpez.net**  

*   Forum [https://www.developpez.net/forums/f19/c-cpp/cpp/](https://www.developpez.net/forums/f19/c-cpp/cpp/)  
    

### Groupe d'utilisateur

**C++ francophone CPP-FRUG**  

*   [https://www.meetup.com/fr-FR/User-Group-Cpp-Francophone/](https://www.meetup.com/fr-FR/User-Group-Cpp-Francophone/)  
    
*   [http://cppfrug.org/](http://cppfrug.org/)

## 7.4 Bien débuter avec Ruby

On va faire rapidement un tour d'horizon de l'eco-système Ruby pour bien commencer à coder et apprendre le langage.

### Sites web

* **Sites principaux**
    * Site officiel du langage : [https://www.ruby-lang.org](https://www.ruby-lang.org)
    * Site de la documentation : [http://ruby-doc.org/](http://ruby-doc.org/)
* **Tester Ruby en ligne**
    * Console Ruby en ligne : [https://ruby.github.io/TryRuby/](https://ruby.github.io/TryRuby/)
* **Site d'actualités**
    * Ruby Inside, actualités et tutoriels (jusqu'à 2014): [http://www.rubyinside.com/](http://www.rubyinside.com/)
    * Ruby community IRC Channel: [https://ruby-community.com/pages/user_rules](https://ruby-community.com/pages/user_rules)
    * News, infos, aggregated Rubyland: [https://rubyland.news/titles](https://rubyland.news/titles)
* **Apprendre et progresser en Ruby**
    * Site de tutoriels Tutorials Point : [http://www.tutorialspoint.com/ruby/](http://www.tutorialspoint.com/ruby/)
    * Ruby Quicktips, des bouts de code utile : [http://rubyquicktips.com/](http://rubyquicktips.com/)
    * Geeks For Geeks for Ruby: [https://www.geeksforgeeks.org/ruby-programming-language/](https://www.geeksforgeeks.org/ruby-programming-language/)
* **Liste de bibliothèques pour Ruby**
    * Dépôt RubyGems : [https://rubygems.org/](https://rubygems.org/)
    * Dépôt The Ruby Toolbox : [https://www.ruby-toolbox.com/](https://www.ruby-toolbox.com/)
    * Ruby On Rails (RoR), le framework qui a fait connaître Ruby : [http://rubyonrails.org/](http://rubyonrails.org/)
    * Gosu, une bibliothèque pour faire des jeux 2D : [https://www.libgosu.org/](https://www.libgosu.org/)

### Principaux livres et ressources pour apprendre Ruby

* Une introduction à Ruby - Zeste de Savoir (français): [https://zestedesavoir.com/tutoriels/634/une-introduction-a-ruby/](https://zestedesavoir.com/tutoriels/634/une-introduction-a-ruby/)
* Learn Ruby The Hard Way: [https://learnrubythehardway.org/book/](https://learnrubythehardway.org/book/)
* Ruby Best Practices (PDF): [https://web.archive.org/web/20120108191027/https://majesticseacreature.com/rbp-book/pdfs/rbp_1-0.pdf](https://web.archive.org/web/20120108191027/https://majesticseacreature.com/rbp-book/pdfs/rbp_1-0.pdf)
* Ruby Hacking Guide: [https://ruby-hacking-guide.github.io/](https://ruby-hacking-guide.github.io/)
* Rubyfu (Black Hat Ruby): [https://rubyfu.net/](https://rubyfu.net/)
* I love Ruby: [https://i-love-ruby.gitlab.io/book.html](https://i-love-ruby.gitlab.io/book.html)
* The Well-Grounded Rubyist, 2nd ed (PDF): [https://archive.org/details/wellgroundedruby0000blac](https://archive.org/details/wellgroundedruby0000blac)
*  Eloquent Ruby (PDF): [https://www.programmer-books.com/eloquent-ruby-by-russ-olsen-pdf/](https://www.programmer-books.com/eloquent-ruby-by-russ-olsen-pdf/)

### Cheatsheet

* Ruby Standard Library: [https://docs.ruby-lang.org/en/master/standard_library_rdoc.html](https://docs.ruby-lang.org/en/master/standard_library_rdoc.html)
* Aide-mémoire Ruby: [https://xitog.github.io/dgx/informatique/ruby.html](https://xitog.github.io/dgx/informatique/ruby.html)
* My beloved Ruby Cheat Sheet: [https://dev.to/ericchapman/my-beloved-ruby-cheat-sheet-208o](https://dev.to/ericchapman/my-beloved-ruby-cheat-sheet-208o)

### Autres ressources

La documentation `ri`. Voir: [https://ruby.github.io/rdoc/RI_rdoc.html](https://ruby.github.io/rdoc/RI_rdoc.html) qui permet de documenter une fonction, class, methode, etc en ligne de commande. Pour l'utiliser installer l'interpreteur REPL `Pry` et lancer `help` pour plus d'info.

### Pour les SysAdmin

Ruby permet d'invoquer des commandes systèmes OS du shell et donc s'utilise comme un langage de scripting pour les tâches d'automatisation. Mais également c'est utile pour intéragir avec l'OS pour écrire des Apps. Utiliser également le module [FileUtils](https://ruby-doc.org/3.2.0/stdlibs/fileutils/FileUtils.html?ref=akshaykhot.com) pour copier, déplacer et supprimer des fichiers et dossiers. Pour cela utiliser la syntaxe:

```ruby

`ls docs`

%x{ ls docs }

exec 'ls'

system('ls', '-l', '.')

# PID
pid = spawn("tar xf ruby.tar.bz2")
Process.wait pid

IO.popen('ls') do |pipe|
  puts pipe.readlines
end
```

### Metasploit Modules
 
Ruby est très pratique pour les hackers et le framework Metasploit pour écrire ces propres exploits, c'est une fonction avancée nécessaire. Petit tour d'horizon:

* Metapsploit Unleashed - Building a module: [https://www.offsec.com/metasploit-unleashed/building-module/](https://www.offsec.com/metasploit-unleashed/building-module/)
* Metasploit docs - Writing an auxiliary module: [https://docs.metasploit.com/docs/development/developing-modules/guides/how-to-get-started-with-writing-an-auxiliary-module.html](https://docs.metasploit.com/docs/development/developing-modules/guides/how-to-get-started-with-writing-an-auxiliary-module.html)
* H 312: Writing a Custom Metasploit Module (25 pts): [https://bowneconsultingcontent.com/pub/EH/proj/H312.htm](https://bowneconsultingcontent.com/pub/EH/proj/H312.htm)

Template type pour écrire un module:

```ruby
require 'msf/core'

class MetasploitModule < Msf::Auxiliary

  include Msf::Auxiliary::Scanner

  def initialize(info = {})
    super(update_info(info,
      'Name'           => 'Module name',
      'Description'    => %q{
        Say something that the user might want to know.
      },
      'Author'         => [ 'Name' ],
      'License'        => MSF_LICENSE
    ))
  end

  def run
    # use `print_status` to print to the metasploit console, instead of `puts`
  end

end
```

## 7.5 Configurer un environnement de programmation en Ruby

Jaime bien et recommande d'apprendre la programmation en Ruby, pour plusieurs raison, c'est une alternative au Python, mais également pour le web development et le fameux framework "Ruby On Rails" et surtout en tant que hacker pour créer des modules sur Metasploit qui est codé en Ruby. C'est donc incontournable. Comme premier langage de scripting je recommande Ruby.

Qu'es-ce que l'on peut faire avec Ruby?

* DevOps
* Web servers
* Data processing
* Web crawling

Ruby est un excellent langage pour les SysAdmin comme scripting et automatiser les tâches. Les logiciels Puppet et Chef sont écrit en Ruby. Vous pouvez même faire de l'intelligence articielle en Ruby. Avec la gem ["ruby-fann"](https://github.com/libfann/fann) pour Fast Artificial Neural Network.

On va donc configurer un environnement basic pour la programmation en Ruby qui utilise:

* RVM packet manager
* Neovim et auto-completion
* Interpréteur avancé REPL Pry
* Debugger

#### A. Nous devons installer les pré-requis. Sous GNU/Linux dans un terminal:

```bash
$ sudo pacman -S base-devel tar gzip diffutils curl
```

En utilisant un packet manager en Ruby RVM
```bash
$ gpg --keyserver hkp://keys.gnupg.net --recv-keys \
  409B6B1796C275462A1703113804BB82D39DC0E3 \
  7D2BAF1CF37B13E2069D6956105BD0E739499BDB

$ \curl -sSL https://get.rvm.io | bash -s stable --auto-dotfiles

$ source ~/.rvm/scripts/rvm

$ rvm pkg install openssl

$ rvm install ruby --with-openssl-dir=$HOME/.rvm/usr

$ ruby -v
```

Modifier `zshrc` pour ajouter le PATH des gems en fonction de votre version ruby
```
export PATH=$PATH':/home/trivial/.local/share/gem/ruby/3.0.0/bin'
source ~/.rvm/scripts/rvm
```

#### B. Installer pry et debugger

```bash
$ gem install pry pry-byebug
```

Pour utiliser Pry
```bash
$ pry
help
```

#### C. Configurer Neovim

```bash
$ gem install solargraph
```

Une fois que vous avez installé Neovim, configurer le gestionnaire de plugin avec Coc

```txt
:CocInstall coc-solargraph coc-json
```

Configuration recommandé

```txt
:CocConfig
```
Editer le fichier
```
{
  "codeLens.enable": true,
  "solargraph.useBundler": false
}
```

Et vous devriez avoir la gestion et support en Ruby, tel que l'auto-completion.

#### D. Mon premier programme en Ruby

D'abord on configure l'environnement de travail, dossier root de nos fichiers sources en `.rb`.

```bash
$ mkdir src-rb
$ cd src-rb
```

Puis on initialise solargraph dans notre dossier de travail

```bash
solargraph config
```

Qui va générer un fichier de configuration dans notre projet `.solargraph.yml`

hello world
```bash
nvim hello.rb
```

```ruby
#!/usr/bin/ruby

puts "Hello World"
```

Pour lancer le script
```bash
$ ruby hello.rb
```

ou alors
```bash
$ sudo chmod +x hello.rb
$ ./hello.rb
```

Les meilleurs livres pour apprendre Ruby gratuitement (anglais) : [https://www.linuxlinks.com/recommended-free-books-learn-ruby/](https://www.linuxlinks.com/recommended-free-books-learn-ruby/)

Un introduction à Ruby - Zeste du Savoir: [https://zestedesavoir.com/tutoriels/634/une-introduction-a-ruby/](https://zestedesavoir.com/tutoriels/634/une-introduction-a-ruby/)