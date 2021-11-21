# Débuter en informatique selon la philosophie arch

Auteur: Anthony JR. Le Goff "Trivial"

Date: Novembre 2021

Licence:

Copyright (C)  2021  ANTHONY JR. LE GOFF.

Permission is granted to copy, distribute and/or modify this document
under the terms of the **GNU Free Documentation License, Version 1.3**
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "[GNU
Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.html)".

Contact email: triviality-lga@protonmail.com pour toutes questions relatives au livre, suggestion et correction.

## 1. Pourquoi ce livre?

On peut ce demander à quoi cela sert d'écrire. Je dirais pour transmettre du savoir. Mais on peut élaborer une pensée, et intellectualiser à l'écrit pour libérer des concepts et forcer à la réflexion. Ce livre n'est pas encore un livre pour débuter en informatique sans une réflexion globale d'un éco-système, son fonctionnement et son architecture en traduisant un cas pratique. C'est un cadre éducatif pour la vulgarisation de l'informatique.

Mon sentiment est de partager ce que j'ai appris et les bonnes pratiques techniques de l'utilisation du système sous GNU/Linux. Ce qui équivaut à des heures de travail à rechercher de la documentation, regrouper des sources d'information et analyser pour une implémentation. Ce livre est donc une synthèse de mes connaissances pour établir une forme de *handbook*. 

Ce  livre s'adresse à tous les curieux, qui ont entendu parler de *Linux* et voudrait apprendre l'informatique par la pratique. J'y fait une approche *hacker* que je vais m'éfforcer de définir. Ainsi ce livre ce veut d'être un indispensable pour débuter dans le hacking avec les meilleurs outils mis à la disposition. L'intérêt est de faciliter la mémorisation de nombreux concept informatique et d'accélérer la courbe d'apprentissage. A la fin de ce livre, l'utilisateur aura clé en main un système à jour selon les dernières technologies du marché pour:

* Faire de la recherche en sécurité informatique
* Développer et concevoir des applications de logiciel libre
* S'initier au *hack* dans son ensemble avec le matériel libre
* Collaborer, s'initier à des projets open source
* S'informer et collecter de l'information
* Protéger son système de l'intrusion, corruption de fichier et au droit à la vie privée

En clair donner les meilleurs outils pour appartenir à une communauté, rendre accessible l'informatique. Commencer par monter son système à la ligne de commande est formateur pour approfondir les concepts, puis les maitriser pour devenir maître de l'ordinateur. On n'apprend pas l'informatique en restant sur une interface graphique, c'est une aide qui occulte tous les principes sous-adjacent. 

L'idée vient du mot anglais *from scratch* ou une façon de dire à construire soi-même. Peut-être que vous avez eu des rumeurs d'utilisation de bureau ultra-personnalisable sous GNU/Linux mais que vous avez aucune idée comment vous y prendre même si l'idée de customiser le système selon vos besoins vous attire.

Ce livre appartient à la philosophie de la sous-culture libre. Il est donc accessible selon la licence défini. Le logiciel utilisé sous GNU/Linux pour son écriture est Ghostwriter pour l'édition en Markdown. C'est le format de transition facilicitant l'exportation en HTML mais également en PDF ou EPUB. Je recherche à publier une version en ligne via des outils open source tel que Gitbook.Ce livre ce veut intéractif avec des liens internet pour approfondir un sujet ou l'utilisation de référence d'ou le format utilisé. L'utilisation de Git devient un standard dans le milieu informatique que je vais développer. Dans ce sens je veux mettre à disposition mes écrits que cela soit pour la réflexion et la pratique de l'informatique dans la culture libre. C'est un travail qui devrait permettre de convertir de nouveaux aspirants *hacker* selon la tradition depuis les débuts de l'informatique et une philosophie de libre partage de l'information.

J'espère bien gagner en influence et réputation pour devenir une référence de formation aux outils de hacking du débutant en informatique. Cela me convient plus que faire de l'argent sur le livre, la connaissance doit être libre d'accès en particulier les outils de création informatique dans l'optique de produire du savoir, ajouter de la valeur et innover pour faire progrèsser la communauté. 

Publier le livre chez un éditeur commercial aurait été contre-productif car je restreins le savoir et limite la diffusion à un support. La plupart des pirates informatiques ne payent pas de livre, dans le milieu il existe des moyens de trouver des PDF ou de la documentation en ligne gratuitement et par des torrents.

L'important est d'avoir pleinement conscience des libertés numériques comme un droit dans un environnement dont l'on prend le contrôle de l'outil informatique. L'open data, sciences ouvertes, les algorithmes, la propriété intellectuelle, la neutralité du net, droit à l'oubli numérique sont des débats qui prolifèrent dans l'espace public et qui nous force à la réflexion de notre place parmis ces enjeux. Somme nous des acteurs ou de simples consommateurs. Les hackers ont une longue tradition de défense des [libertés numériques](https://framabook.org/libertes-numeriques/) par des mouvements underground de fond à travers le monde. Un utilisateur soucieux de ces libertés, prendra soin de vérifier chaques bric logiciel, du système d'exploitation à des applications que les gouvernements ou multinationales n'introduisent des moyens de contrôle et profit sur les données que vous produisez. Malgré le discours de lutte contre la cybercriminalité, de menace contre les Etats, la surveillance de masse reste une problématique intrusif dans la vie privée des individus pour la plupart n'ayant aucune compétence technique pour y remédier. Ce livre apporte son lot de solution.

 

## 2. Préambule libriste

Il m'était impossible de ne pas introduire l'objet de l'étude de l'informatique par un mouvement de fond tel que le logiciel libre. Steve Ballmer(ex PDG Microsoft) disait du logiciel libre que c'était un cancer pour la propriété intellectuelle. Ce que l'on entend par propriété intellectuelle est le brevet pour une invention. Ce qui permet de rémunérer les inventeurs et d'accéder à la paternité d'une nouvelle idée mise en concept à bus de faire du profit commercial.C'est donc une manière d'éviter de ce faire copier et donc voler son travail. Personne n'aime le plagiat, qui représente un travail médiocre en qualité. Dans ce sens l'arrivée des logiciels informatiques allaient remettre en cause les pratiques dominantes sur les oeuvres de l'esprit. En particulier l'étude et la redistribution du code source. Un logiciel disposant du code source peut-être copié à l'infini ne vous dépouillant pas de votre travail ayant vous même une copie du code source. L'étude du code source permet donc d'améliorer les fonctionnalités et d'en faire des dérivées *fork*, de l'adapter sur plusieurs matériels mais également d'en faire un travail d'audit de recherche de faille de sécurité qui pourrait compromettre son utilisation. Ces quelques principes sur une économie du partage n'est pas venu instinctivement car des pratiques pour s'enrichir sur le dos du modèle capitaliste vont apparaitre fin des années 70. Le code ouvert en particulier par l'utilisation des universitaires se fermera par l'arrivée commerciale pour le grand public du micro-ordinateur dont le système d'exploitation DOS. Quelques projets vont rentrer en résistance dont le projet GNU de Richard Stallman en mémoire de l'esprit hacker des premiers jours pour faire un dérivée de système d'exploitation UNIX qui serait libre. On peu dire que Richard Stallman est le premier libriste en définissant le logiciel libre. Une véritable [bataille du libre][1] va donc commencer marquant l'histoire de l'informatique.

![GNU Logo](./The_GNU_logo.png "GNU logo")

Dans ce cadre, la volonté de la communauté est avant tout chose de résoudre un problème technique que de répondre à une offre marchande et donc la protection par un brevet contre la concurrence. Pourtant il est nécessaire de considérer la paternité d'une innovation technologique en informatique et de prendre en compte les auteurs. Ce que va définir Richard Stallman dans son projet GNU est une license d'utilisation. Les libristes donc se définissent comme des enfants du projet GNU et la définition des quatres libertés fondammentales tel que:

* la liberté d'exécuter le programme, pour tous les usages ;
* la liberté d'étudier le fonctionnement du programme et de l'adapter à ses besoins ;
* la liberté de redistribuer des copies du programme (ce qui implique la possibilité aussi bien de donner que de vendre des copies) ;
* la liberté d'améliorer le programme et de distribuer ces améliorations au public, pour en faire profiter toute la communauté.

Ainsi la nécessité d'accès au code source est une condition de ces libertés. Et après tout quand on y réfléchis bien n'est ce pas pareil en biologie? Un être humain à la liberté d'être copié et de ce reproduire et son programme codé dans l'ADN est disponible. Aujourd'hui en génétique on peut modifier cet ADN pour l'améliorer ou réparer des caractéristiques. On peut penser au processus d'amélioration continue et de mutation d'un logiciel comme l'évolution du vivant. Avec des branches dans l'origine d'un arbre d'une espèce. Ainsi un logiciel pour le traitement de texte est une famille qui demande d'être adapté à un environnement de travail qui évolue et donc mise à jour dans le temps en ajoutant des caractéristiques. Certaines personnes vont ajouter des fonctionnalités exclusives pour en tirer parti d'un point de vue commerciale. Tel est le constat caché le code source complique le processus d'innovation car on restreint la distribution à quelques acteurs et donc on élève des privilèges. Cela me rappel des affaires tel que Coca-Cola qui garda jalousement secrète sa recette et donc garder un monopole. Hors c'est bien la lutte contre les monopoles dont il est question dans le logiciel libre. C'est une stratégie qui est contre-productive car sur du long terme vous ne pouvez pas empêcher la recherche, également cela engendre dans le principe de concurrence une mise en place d'espionnage pour découvrir les secrets de fabrication et de production. Si on veut réduire la malveillance un secret doit être partagé. On retrouve dans d'autres domaines des exemples de raté, tel que la fabrication de la bombe atomique. les USA n'ont jamais gardé le monopole, au contraire cela n'a fait qu'accélérer une course à l'armement. La question de la propriété intellectuelle n'est pas vite répondu, la découverte d'une solution technique engendre un phénomène d'adoption rapide à partir du moment qu'il répond à un besoin. Dans le cadre de la bombe atomique, c'est la question de puissance qui est remis en cause et donc l'impact politique. Mais cela peut-être un impact sur la création tel que des logiciels de CAO(conception assisté par ordinateur). Doit-on restreindre la possibilité de création à l'industrie et quelques licences universitaires? Comment fait-on pour que l'étudiant ce forme si celui-ci ne peut qu'utiliser les ordinateurs à l'université? Et si on donne un travail personnel à faire chez soi? Que de contrainte. Au-delà de ça c'est croire une utopie de civilisation que la recherche de solution technique ne se fait qu'à l'industrie dans le cadre d'un travail rémunérer. Hors, l'histoire des découvertes de ce monde en science est une affaire de passionné et pas seulement qu'en laboratoire. C'est ce que démontre le logiciel libre par le bénévolat et hors temps de travail, on peut produire une solution technique. Il pourrait être question de développement durable et d'accès à la technologie pour des pays en voie de développement. Pour accèder à ces marchés le coût pour se fournir en matériel informatique est bien trop élevé. Donc on regarde des solutions alternatives parfois gratuite pour remplacer les industriels et logiciels privateurs. La circulation de l'information doit être accélérée en tout point du globe et définir les bonnes pratiques pour que chacun puisse avoir accès aux outils de création, de production en particulier d'oeuvre de l'esprit et donc intellectuel.

C'est sous cette nécessité que ce livre se construit. Par adhésion au mouvement de la culture libre initié par des informaticiens pour aller plus loin que l'idéologie, c'est un projet de société et de civilisation et la croyance en une futur [économie de l'abondance][2] dont le logiciel libre est la première brique qui déposa un standard sur l'utilisation de ressource illimité. Elle doit être tout d'abord développé dans un paradigme de la pensée et de l'immatériel dont la révolution informatique à propager l'économie de la connaissance actuelle, vers la possibilité pour l'humanité d'élargir les horizons vers l'espace et le minage d'astéroide et de exoplanète permettant l'utilisation de la ressource matériel illimité réduisant les conflits sur les problèmatiques de rareté. Il faut être clair pour tout programme spatial, c'est tout d'abord du calcul de trajectoire de projectile que l'informatique nous permet et la production d'un capital immateriel pour développer un produit avec succès. Le logiciel libre est le cheval de Troie de l'ouverture vers l'espace car c'est un univers fait de robotique terrain de jeu de la cybernétique.Aujourd'hui du logiciel libre est embarqué dans les fusées SpaceX ou sur le rover Persévérance sur Mars. Le succès du logiciel libre à travers la FSF(Free-software foundation) a permis de voir des projets tel que:

* Linux (noyau de système d'exploitation)
* Apache (serveur web)
* Mozilla Firefox (navigateur internet)
* Gimp (logiciel de dessin)
* Git (outil de contôle de version)
* Perl (langage de programmation)

Largement adopté par les industriels de nos jours par les pratiques des développeurs car répondant une solution technique et un réel besoin. 99% top 1 million des websites fonctionnent sur un serveur GNU/Linux et 100% des top 500 supercalculateurs mondiaux ont adopté GNU/Linux. Il y a une véritable suprématie des logiciels libres quand il est question de performance et de réduire les coûts de fonctionnement. On peut également noté que les scientifiques du CERN tournent sous GNU/Linux et sont très actif dans le développement par la propagation de la [science ouverte][3]. Le logiciel libre est moteur dans la mise en oeuvre de pratique développé par l'économie du partage qui réduit de plus en plus la portée des documents classifiés chez les industriels dans une optique de collaboration entre des parties prenantes pour chasser en meute.

## 3. L'héritage d'UNIX

Revenons un peu sur la genèse du projet GNU, j'expliquai que ce livre est de vous permettre d'apprendre l'informatique et d'acquérir des libertés numériques. Nous allons donc faire une étude de cas à travers une distribution GNU/Linux. Il faudra donc connaitre GNU et Linux. Comme j'en parlais le projet GNU est une ré-écriture complète d'UNIX. UNIX est un système d'exploitation pour ordinateur, c'est à dire que c'est un logiciel qui permet la communication entre le matériel(hardware) physique tel que le clavier, l'écran, la souris, le processeur, etc... et des applications comme votre navigateur internet. GNU est une série de programmes, librairies et compilateurs pour l'utilisateur: c'est à dire un environnement complet de travail pour le développeur pour créer des logiciels. Vous trouverez à la page [GNU du wiki arch linux][4] la liste complète de projet GNU de nos jours. Au commencement, en 1985, on retrouvait en particulier:

* Bash, un shell pour écrire des lignes de commande
* glibc, *GNU C Librairy* Implémentation de la librairie standard en C
* Emacs, un éditeur de texte
* gcc, GNU Compiler Collection est un logiciel de compilation en C

UNIX a été écrit en langage C. Les systèmes d'exploitation sont écrit dans ce langage, il était donc nécessaire de créer un compilateur pour faire des fichiers binaires éxecutables. Le compilateur transforme du code que peut lire et écrire l'humain en langage C vers du code machine binaire à base de 0,1 des bits que peu lire le processeur et exécuter. Pour écrire du code, on utilise un éditeur de texte. Sous UNIX, l'éditeur est Vi. Il existe une petite guerre de religion entre les puristes qui utilisent Emacs et Vi puis son héritier Vim. Mais cela vous aller le découvrir. On utilise un shell pour lancer un programme tel que Vi en ligne de commande pour éditer un fichier en langage C puis on compile toujours en ligne de commande avec gcc. Quand à glibc est une bibliothèque C qui apporte les appels système et les fonctions de base telles que open, malloc, printf, etc. Si vous cherchez à étudier la programmation système il vous faudra connaître ces notions, mais pour l'instant ce n'est que pour la culture.

## 4. Linux

![Architecture OS GNU/LINUX](./OS-arch.jpg "GNU/Linux")

Le projet GNU n'est pas complet, il manque un noyau pour dialoguer avec le matériel de l'ordinateur, le noyau Hurd sera une tentative de concevoir une solution, mais qui sera pas opérationnel. Cette partie sera introduite par un finlandais du nom de Linus Torvalds en 1991 comme bénévole. Celui-ci va écrire un noyau à l'origine avec 10 000 lignes de code d'après le projet Minix. Le noyau [Linux][5] fonctionne pour les architectures de processeur x86 et fait 64Ko une fois compressé. La version 0.0.1, disponible sur le visualisateur de [code source du noyau][6], était composé d'une cinquantaine d'appel système, c'est à dire la gestion de base pour les processus, la mémoire et les fichiers. Ainsi le système d'exploitation sera finalisé par une fusion des projets GNU/Linux et l'arrivée d'interface graphique(GUI) comme le projet Debian. Une entreprise va rapidement entrée dans le jeu avec la fondation de Red Hat par Robert Young. C'est la naissance d'un éco-système économique commercial et communautaire. En 2021 il existe environ 15 600 développeurs du noyau qui ont contribué depuis 2005 et environ 1400 compagnies. Grâce a l'arrivée de Git il est possible de tracer les contributions. Il est possible de devenir un "kernel dev" et de hacker le noyau. La [documentation][7] pour contribuer pour le noyau est copieuse sur internet ainsi que des formations tel que chez la "Linux Foundation" gratuitement. Il faudra tout d'abord connaitre le langage C comme prérequis et être à l'aise avec Git.

## 5. Eco-système

On l'aura vue, depuis la genèse du projet GNU de Richard Stallman, un éco-système va ce mettre en place avec des programmeurs autour du logiciel libre qui donnera naissance à Linux. Tout d'abord la FSF ou free-software foundation. On va retrouver le premier système d'exploitation sous GNU/Linux et la communauté Debian, puis viendra la première entreprise avec Red Hat puis la distribution Fedora. On compte maintenant plus de 600 distribution sous GNU/Linux dans le monde avec des partisans et militants du logiciel libre. En France la promotion et la défense du logiciel libre est réalisé par l'[April][8], mais aussi par l' association Framasoft qui publie des documents et ressources et également Linuxfr.org qui est le principal site communautaire. En 2021 la documentation la plus accessible est celle de la distribution Ubuntu pour s'initier à la communauté ainsi que le wiki Arch Linux sur internet. A noter que Wikipédia, l'encyclopédie libre est une réussite du mouvement, autant apprécié des internautes curieux de connaissance que des thésards comme source d'information. Les idées reçuent comme quoi on ne peu pas faire confiance à une source d'information que n'importe qui peu éditer et contribuer n'est plus d'actualité grâce au travail des wikipédiens. Concernant les infrastructures critiques financières, la bourse de New-York à migré vers des solutions "Red Hat entreprise"en 2008. Du côté des militaires, au USA le "Department of Defense" de l'US Army utilise egalement Linux ainsi que pour la flotte de sous-marin nucléaire et le système de sonar.

Un autre mouvement va apparaitre en 1998 sous l'impulsion de Eric Raymond nommé l'OSI(Open source initiative) mettait plutôt l'accent sur le développement
technologique en permettant aux créateurs de se servir librement du travail
de leurs devanciers. L'open source sera particulièrement plus adapté pour les entreprises pour développer de la technologie alors que le logiciel libre sera plus un mouvement social selon Richard Stallman. Lawrence Lessig, le créateur de Creative Commons (CC) et du livre "culture libre" en 2005 fera la remarque que le copyright est un obstacle à la production culturelle, au partage de la connaissance, à l'innovation technologique et l'intérêt privée. Une autre ONG représente le paysage de la culture libre à l'échelle internationnale est l'[EFF(Electronic frontier foundation)][9]. l'EFF contribue à la protection des droits et liberté sur internet. L'objectif essentiel de l'EFF est de défendre la liberté d'expression sur Internet, et plus largement la vie privée en ligne des utilisateurs. Pour accompagner ces derniers dans cette optique, EFF a notamment mis en place un guide spécialisé dans la protection contre l'espionnage en ligne, intitulé Autodéfense contre la surveillance.

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




## 6. Les hackers

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

Les années 80 va être l'apparition des premiers groupes de hacker et de l'essor de l'ingénierie sociale, l'exploitation de la ressource humaine. Le phreaking et les blues box pour téléphoner gratuitement ont débuté auparavent. Le cyberespace fait son apparition dans le roman de science-fiction avec Neuromancien de William Gibson précurseur à Matrix. Le groupe "414s" sera par le FBI accusé des 60 premières intrusions dans un système informatique. De nos jours il y a une culture "old school" de hackers lié à Legion Of Doom au USA, Le Chaos Computer Club en Allemagne donnant lieu aux premières affaires de cyberespionnage et les magazines "2600:The Hacker Quaterly" et "Phrack". C'est l'époque de protagoniste tels que Kevin Mitnick qui passa des années en prison pour vol de logiciel et destruction d'ordinateur mais également Kevin Poulsen alias "Dark Dante" qui s'introduisa sur l'ARPAnet de l'université de Californie(UCLA) en 1983. En 1984, Fred Cohen développe le terme de Virus informatique. L'année 1988, le célebre protocole de chat IRC fait son apparition, toujours utilisé par une partie des hackers pour sa sécurité, même si des applications tel que Discord à vue le jour. En 1989 aura lieu le premier "Denial of service" par Robert Morris et le ver Morris à l'université de Cornell, il voulait tester l'effet sur un système UNIX sur l'ARPAnet. Les USA allaient règlementer le cybercrime qui prenait son envol à travers "Computer fraud et abuse act" en 1986. L'émergence des premiers blacks hats dans le jargon nécessitait d'arrêter les actes de malveillance. Un incident aura lieu ou un hacker nommé "The Mentor" sera arrêté. Il va jouer un rôle dans la propagation de l'esprit hacker à travers le [manifeste hacker][10] qu'il aura écrit suite à son arrestation. Devenu symbole de la culture et de la psychologie derrière.

L'esprit hacker d'UNIX va être ré-écrite par le projet GNU de Richard Stallman qui va définir le logiciel libre face à la privatisation du secteur depuis l'arrivée du micro-ordinateur. Avec le noyau Linux la communauté hacker va rebondir.

Les services secrets vont faire de plus en plus d'investigation sur les activités de groupe d'hacker soupçonné de fraude tel que l'opération Sundevil en 1990. La recherche de faille sur les systèmes informatiques et ce connecter sur une machine à distance fait partie des techniques utilisées.

En France la communauté hacker va se structurer, mais l'autoroute de l'information qu'est internet fait des débuts hasardeux face au Minitel. Pourtant un homme, Jean-Bernard Condat, consultant pour la DST, les services secrets français va créer le Chaos Computer Club France, comme faux groupe de hacker pour les surveiller et les ficher par le renseignement durant les années 90. 

L'arrivée d'internet et le www(world wide web) accélère le basculement vers l'âge de l'information. C'est en 1991 que PGP développé par Philip Zimmerman sera diffusé sur le web comme logiciel libre et garantir un droit aux communications chiffrées par email. Parmis les hackers et puriste d'UNIX, freeBSD sera créé comme une solution libre. En 1994, Vladimir Levin, mathématicien, va hacker la Citibank et dérober 10 millions de dollars. La [déclaration d'indépendance du cyberespace][11] est déclaré le 8 février 1996, par John Perry Barlow (un des co-fondateurs de l'EFF). C'est une déclaration très engagé sur la souveraineté d'internet qui n'appartient pas aux gouvernements. De nos jours la surveillance d'internet par les gouvernements est un enjeu ou chacun aimerait se déclarer possesseur des données transitant sur le réseau. La législation prend en compte le pays pour le stockage des données. Le chiffrement des connexions du protocole TCP/IP a été acceléré à travers le HTTPS depuis l'annonce de la surveillance du réseau par la NSA ou encore le GCHQ du Royaume-Unis. En 1998, deux hackers chinois Hao Jinglong et Hao Jingwen vont pénétrer dans un système bancaire et voler 720 000 Yuans, ils seront condamné à la peine de mort. Cette même année le célèbre groupe "The cult of Dead Cow" va montrer à la conférence du hacking Def Con à travers le programme Back Orifice, un trojan( cheval de Troie) que l'on peu obtenir des accès non-autorisé à Windows à distance. L'année 1999 fut marqué par le développement de la trilogie Matrix, un univers cyberpunk ayant une grande influence sur la culture Hacker rendant mainstream l'[hypothèse de simulation][12] de Nick Bostrom au grand jour comme quoi nous vivons dans un programme informatique et questionne la réalité, cela fit couler beaucoup d'encre en philosophie. L'an 2000 va être marqué par l'un des plus grandes attaques DDos de l'histoire sur Yahoo, eBay, Amazon.com, CNN et quelques autres sites d'un hacker nommé "MafiaBoy", un adolescent canadien pour épater la communauté des hackers. Eric S. Raymond, à l'origine de l'open source va écrire un article célèbre ["Comment devenir un Hacker"](https://www.cairn.info/libres-enfants-du-savoir-numerique--9782841620432-page-255.htm%20-%20no10) ou entre autre pour résumer le papier il est nécessaire d'apprendre à utiliser un système UNIX, savoir programmer dans plusieurs langages tels que C pour les systèmes, Perl, Python et Lisp. Il préconise d'écrire des programmes au code source ouvert pour la communauté. L'auteur souligne l'importance de former l'esprit à la résolution de problème et automatiser les tâches ennuyeuses. Il parle d'apprendre à utiliser internet le WWW et de savoir utiliser l'HTML.

En 2003 va naître un mouvement et groupe d'hacktiviste: Anonymous. Le système de bulletin électronique, 4chan sera très associé à la genèse du groupe qui défend la liberté d'expression par des actions tels que l'attaque DDoS ou le défaçage de site web. Le groupe dénonce et attaque régulièrement la secte de la scientologie par le projet Chanology. Selon Chris Lander, du Baltimore City Paper datant du 2 avril 2008, "Anonymous est la première superconscience construite à l'aide d'Internet" dans le sens qu'il n'y a pas de leadership par un réseau décentralisé. C'est un exemple à suivre dans les méthodes de management que permet internet. La même année sortira Metasploit, par H.D Moore écrit tout d'abord en Perl puis la version d'après en Ruby. Il deviendra l'outil de test de pénétration le plus populaire parmis les hackers permettant de fournir des vulnérabilités sur les systèmes informatiques et de faire des tests d'intrusion, on peut écrire des exploits et des shellcodes(chaîne de caractères qui représente un code binaire exécutable, invoque un shell) en vue de tester un système cible. En 2006 le système d'exploitation BackTrack verra le jour comme suite complète de logiciel pour les tests de pénétration(Pentesting) qui sera ré-écrit en 2013 à la base de Debian sous le nom de Kali Linux.
Bien des groupes de hacker vont proliférer qui sont au coeur de la résistance numérique ont peu noter en particulier Telecomix, Lulzsec, ou encore Lizard Squad. La décennie 2010, une nouvelle forme de menace informatique sous le couvert des Etats s'annonce sous le nom d'APT(Advanced Persistent Threat). L'attaque est furtive et sophistiquée souvent sponsorisé par les gouvernements et militaires dans le but d'opération d'influence et de renseignement tel que de cyberespionnage d'entreprise, mais aussi de déstabilisation d'infrastructure stratégique tel que l'énergie. C'est le cas du malware Stuxnet, un programme informatique attribué à la NSA aux U.S pour pénétrer dans un système industriel SCADA et perturber le fonctionnement d'équipement pour l'enrichissement d'uranium en Iran. On compte aujourd'hui [94 APT référencés par mitre att&ck][13]. En 2017 le ransomware WannaCry a infecté des ordinateurs remontant à un groupe de hacker en Corée du Nord, le groupe Lazarus. D'autres groupes sont sponsorisés par des Etats tels que Double Dragon en Chine, Equation Group aux USA, Fancy Bear en Russie. La technique est en constante évolution et l'avenir est à l'utilisation de Machine Learning en intelligence artificielle permettant de nouvelle manière d'aborder l'ingénierie sociale. Ce chapitre résume bien l'évolution des hackers depuis les origines de l'informatique et l'état des lieux du champ d'application des compétences. Les mercenaires de l'informatique prolifèrent tel que la vente de faille 0days pour des entreprises ou des Etats mais egalement le programme de bug bounty qui permet dans un cadre légal de trouver des failles de sécurité contre une prime dans le but d'améliorer les logiciels. Des hackers ont pu devenir millionaire comme Santiago Lopez. Le cybercrime n'est plus la seule source de revenue et de profit. Mais certain hacktivisme ne recherche que la destruction par idéologie pour que ce monde brule forçant le capitalisme à la remise en question ouvrant la voie à d'autres systèmes de gouvernance supervisé dans le futur par l'intelligence artificielle permettant un meilleur traitement des données pour la prise de décision. Dans un monde informationnel, à l'age d'internet, la compétence de hacking est la clé de ce siècle pour maitriser l'information mais aussi créer et faire évoluer la société.

Quelques hackers qui ont marqué la culture par leurs actes passés:
* **Kevin Mitnick**, en 1982, il a hacké le NORAD( North American Defense Command ) qui a inspiré le film *War Games*, plus tard c'est la société DEC ou il pénétra sur ces réseaux et copia les logiciels. 
* **Adrian Lamo** surnomé "the homeless hacker" sans domicile fixe, il n'avait qu'un sac léger pour voyager, sans adresse fixe, il est connu pour avoir pénétrer les réseaux du New York Times, Yahoo et Microsoft.
* **Albert Gonzalez** a organisé une fraude touchant 135 millions numéros de carte de crédit, il fut egalement un informateur des services secrets pour éviter la prison. Pour exploiter ces fraudes il utilisa l'injection SQL pour mettre en place des backdoors.
* **Matthew Bevan et Richard Pryce** qui ont joué au *war games* avec le Pentagone. Ils ont pénétré dans plusieurs systèmes militaires dont: Griffiss Air Force Base, the Defense Information System Agency et the Korean Atomic Research Institute (KARI). Ils ont été accusé de vouloir lancer une troisième guerre mondiale. Pour leur défense, l'un parla qu'il cherchait à prouver une conspiration d'OVNI.
* **ASTRA**, est un mathématicien grec de 58 ans qui a sévit sous le pseudo de ASTRA et pénétrer l'entreprise Dassault pour voler des informations sur des systèmes d'armement ainsi que des logiciels pour les revendres.

## 7. Ou trouver de l'aide?

Il existe bien des ressources disponible pour celui qui veut progresser en informatique et particulièrement touchant au logiciel libre et à l'open source. Le réflexe en l'occurence se réfère à *RTFM* >> Read The Fucking Manual! On le dira jamais assez, lisez le manuel et la documentation. Ainsi chaque commande dans un terminal est documenté. Un problème pensez `man` pour *manual* et taper le nom de la commande. C'est déjà un début. Pour ce familiariser à la ligne de commande car c'est de ça qu'il est question plus tard dans ce livre en particulier Arch Linux, mettez dans votre navigateur ces liens suivants:

* https://www.webminal.org/ est un site pour apprendre la ligne de commande
* Les wikis Arch Linux en français https://wiki.archlinux.fr/ et anglais https://wiki.archlinux.org/
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

Pour trouver des hackers, le web à rassemblé des ressources utile pour la communauté. Un point d'entrée intéressant est Reddit et r/Hacking dont le wiki est particulièrement bien documenté à cette adresse: https://new.reddit.com/r/hacking/wiki/index. Sur Reddit, la communauté compte 2,1 millions d'abonnés. Mais continuons à creuser plus profondemment comme les forums:

* https://raidforums.com/index.php
* https://hackforums.net/
* https://evilzone.org/
* https://0x00sec.org/

La communauté française est présente à travers quelques sites et chats de discussion, pour certain facile d'accès et pour d'autres il faut réaliser une série d'épreuve en tant que hacker.

* https://instant-hack.to/ 
* https://hackademics.fr/
* https://forum.zenk-security.com/

En ce qui concerne le dark web, on retrouve des activités illégalles de service tel que la vente de malware, mais utile si vous cherchez à vous fournir en materiel pour l'analyse et l'étude. On peut trouver des contenus sujet à contreverse mais intéressant pour la connaissance. Certain de ces communautés sont élitiste et restreint l'accès tel que:

* cryptBB
* Torum
* KickAss
* 0days

En résumé, vous n'êtes pas seul, ce poser des questions est le début de l'aventure, résoudre des problèmes et faire appel à la communauté est un processus normal, on ne peut pas tout connaitre, même moi je vais sur google de temps en temps pour des commandes basiques, YouTube pour des tutoriaux sur des sujets plus précis qui évoluent dans le temps. Apprendre à apprendre, que cela soit du junior au senior n'est pas forcément un comportement que l'on adopte naturellement, cela demande de mettre en place des automatismes que j'espère ces quelques lignes permettent d'aiguiller sur le territoire de l'informatique. 

## 8. Ce former à l'informatique sur le web

Cybrairy, Coursera, Udemy, Khan Academy, The Odin Project,
Open Source University (OSSU)
teach yourself computer science.

## 9. Ce que dit la loi

## 10. Keep it simple, stupid

## 11. La modularité

## 12. Gestion des mots de passe

Politique de mot de passe.
Accès BIOS
Ouvrir la partition chiffrée
Compte utilisateur et administrateur "root"
Keepass

## 13. Migration

## 14. Le matériel

## 15. Obtenir la dernière version d'Arch Linux

## 16. Booter sur une clé USB

## 17. Débuter l'installation

## 18. Connectez-vous au réseau internet 

## 19. Sélectionner la source

## 20. Configurer l'horloge

## 21. Partionner le disque

## 22. Chiffrer le disque

## APPENDICE I : Utiliser du matériel libre
## APPENDICE II : Contribuer à l'open source
## APPENDICE III : Configurer une VM(virtual machine) sous KVM/QEMU
## APPENDICE IV : Conteneurs avec Docker et Kubernetes
## APPENDICE V : Anonymat & furtivité "stealth"

Tor

[1]:https://www.labatailledulibre.org/ "La bataille du libre"
[2]:https://www.cairn.info/revue-hermes-la-revue-2006-2-page-51.htm "Economie de l'abondance, communs, immatériel"
[3]:https://www.science-ouverte.cnrs.fr/le-mouvement-pour-la-science-ouverte/ "Science ouverte"
[4]:https://wiki.archlinux.org/title/GNU "GNU Project"
[5]:https://www.blaess.fr/christophe/articles/linux-histoire-dun-noyau/ "Noyau Linux"
[6]:https://elixir.bootlin.com/linux/0.01/source/kernel "version 0.0.1"
[7]:https://www.kernel.org/doc/html/latest/ "Kernel documentation"
[8]:https://april.org/ "April"
[9]:https://www.eff.org/fr "EFF"
[10]:https://www.larevuedesressources.org/le-manifeste-du-hacker,2298.html "Manifeste hacker"
[11]:http://editions-hache.com/essais/barlow/barlow2.html "déclaration"
[12]:https://www.polytechnique-insights.com/tribunes/science/comment-savoir-si-nous-vivons-dans-une-simulation/ "hypothèse de simulation"
[13]:https://attack.mitre.org/groups/ "APT groups"