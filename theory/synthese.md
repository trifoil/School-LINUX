* Logiciel libre
    ```
    logiciel fourni avec les autorisations pour quiconque de l'exécuter, de le copier, de l'étudier, de le modifier, et de le distribuer (modif ou non)
    Ils ne sont pas forcément gratuits
    ```

* Citer licence logiciel libre
    ```
    MIT, GPLv3 (modifs doivent rester sous GPL)
    ```

* Logiciel open source
    ```
    L’open source est une méthodologie de développement ; le logiciel libre est un mouvement de société.
    Le logiciel libre est d'office open source.
    ```

* Linux 
    ```
    Linux est une famille de systèmes d'exploitation basés sur un noyau UNIX
    (désigne aussi le kernel à l'origine)
    ```

* Distro
    ```
    Une distribution Linux est un système d'exploitation qui possède une collection de logiciels dont le kernel Linux. Il possèdent dans la plupart des cas un package manager. 
    ex : debian, fedora, opensuse, nixos, RHEL
    ```

* Shell 
    ```
    A shell is a special user program that provides an interface for the user to use operating system services. Shell accepts human-readable commands from users and converts them into something which the kernel can understand. It is a command language interpreter that executes commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or starts the terminal.
    ```

* Console vs terminal
    ```
    Console = ensemble ecran clavier souris directement connecté
    Terminal = ensemble ecran clavier souris par l'intermédiaire d'un réseau
    ```

* Commandes de base
    ```
    ls
    man
    -help
    cd
    touch
    lmkdir
    rm
    cp
    ```

* Role de l'admin
    ```
    La gestion des besoins, du budget et des priorités
    La gestion des ordinateurs et des périphériques
    La gestion des performances des systèmes
    La gestion des utilisateurs
    La gestion des fichiers et des disques
    La gestion des services
    La gestion des problèmes
    La gestion des sauvegardes et du stockage des données
    La gestion du réseau
    La gestion de la sécurité

    Documenter
    Sauvegarder
    Automatiser
    Agir de manière réversible
    Etre proactif

    Savoir communiquer
    Avoir une bonne connaissance du marché
    Connaître ses limites
    ```

* Fichiers
    ```
    suite de bits qui constituent un ensemble cohérent
    tout est fichier (dossiers, fichiers, tables de partitions, etc...)
    ```

* Arborescence de fichiers
    

    * /     
    la racine, elle contient les répertoires principaux
    * /bin      
    Contient les exécutables essentiels au système, employés par tous les utilisateurs.
    * /boot     
    Contient les fichiers de chargement du noyau, dont le chargeur d'amorce.
    * /dev      
    Contient les points d'entrée des périphériques.
    /etc        
    Contient les fichiers de configuration nécessaires à l'administation du système (fichiers passwd, group, inittab, ld.so.conf, lilo.conf, ...).
    * /etc/x11        
    Contient les fichiers spécifiques à la configuration de X (contient XF86Config par /etc/X11
    exemple)
    * /home     
    Contient les répertoires personnels des utilisateurs. Dans la mesure où les répertoires situés
    sous /home sont destinés à accueillir les fichiers des utilisateurs du système, il est conseillé
    de dédier une partition spécifique au répertoire /home afin de limiter les dégâts en cas de
    saturation de l'espace disque.
    * /lib       
    Contient les bibliothèques standards partagées entre les différentes applications du système.
    * /mnt      
    Permet d'accueillir les points de montage des partitions temporaires (cd-rom, disquette,
    ...)2.
    * /proc     
    Regroupe un ensemble de fichiers virtuels permettant d'obtenir des informations sur le
    système ou les processus en cours d'exécution.
    * /root      
    Répertoire personnel de l'administrateur root. Le répertoire personnel de l'administrateur
    est situé à part des autres répertoires personnels car il se trouve sur la partition racine, afin
    de pouvoir être chargé au démarrage, avant le montage de la partition /home.
    * /sbin         
    Contient les exécutables essentiels du système (par exemple la commande useradd).
    * /tmp          
    Contient les fichiers temporaires
    * /usr          
    Hiérarchie secondaire
        * /usr/X11R6 
        Ce répertoire est réservé au système X version 11 release 6
        * /usr/X386          Utilisé avant par X version 5, c'est un lien symbolique vers /usr/X11R6
        * /usr/bin          
        Contient la majorité des fichiers binaires et commandes utilisateurs
        * /usr/include      
        Contient les fichiers d'en-tête pour les programmes C et C++
        * /usr/lib          
        Contient la plupart des bibliothèques partagées du système
        * /usr/local        
        Contient les données relatives aux programmes installés sur la machine locale par le root
        * /usr/sbin         
        Contient les fichiers binaires non essentiels au système et réservés à l'administrateur système
        * /usr/share            
        Réservé aux données non dépendantes de l'architecture
        * /usr/src      
        Contient des fichiers de code source
        * /var          
        Contient des données versatiles telles que les fichiers de bases de données, les fichiers journaux (logs), les fichiers du spouleur d'impression ou bien les mails en attente.
    
* Types de fichiers
    * Fichiers normaux -> - 
    * Directories -> d
    * Links -> l
    * Special files -> b,c,p,s

* Liens
    