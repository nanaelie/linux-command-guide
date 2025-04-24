# Commandes Linux Utiles

Ce dépôt contient une collection organisée de commandes Linux courantes, classées par catégories pour faciliter leur utilisation et leur apprentissage. Que vous soyez un utilisateur débutant ou un professionnel, vous y trouverez des commandes pour accomplir différentes tâches sous Linux.

## Table des matières

- [Installation](#installation)
- [Commandes de base](#commandes-de-base)
- [Développement](#développement)
- [Gestion de fichiers](#gestion-de-fichiers)
- [Réseau](#réseau)
- [Sécurité](#sécurité)
- [Système](#système)
- [Virtualisation](#virtualisation)
- [Autre](#autre)
- [Toutes les commandes](#global)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Installation

Aucune installation n'est nécessaire. Vous pouvez simplement cloner ce dépôt sur votre machine locale :

```bash
git clone https://github.com/nanaelie/linux-command-guide.git
```

## Commandes de base

Les commandes de base sont les premières que tout utilisateur Linux doit connaître :

```bash
    pwd   # Affiche le répertoire de travail actuel.
    cd    # <chemin> : Change de répertoire.
    ls    # Liste les fichiers dans un répertoire.
    mkdir # <nom_du_répertoire> : Crée un nouveau répertoire.
    rmdir # <nom_du_répertoire> : Supprime un répertoire vide.
```

## Développement

Ces commandes sont utiles pour les développeurs travaillant sur des projets Linux :

```bash
    git         # Commandes Git pour le contrôle de version.
    gcc         # <fichier.c> -o <programme> : Compiler un fichier C.
    make        # Utiliser des fichiers Makefile pour automatiser les compilations.
    vim         # Éditeur de texte en mode terminal pour modifier des fichiers.
    npm install # Installer des dépendances pour un projet Node.js.
```

## Gestion de fichiers

Voici des commandes pour manipuler les fichiers et répertoires :

```bash
    cp    # <source> <destination> : Copie un fichier ou un répertoire.
    mv    # <source> <destination> : Déplace ou renomme un fichier ou un répertoire.
    rm    # <fichier> : Supprime un fichier.
    rm -r # <répertoire> : Supprime un répertoire et son contenu.
    touch # <fichier> : Crée un fichier vide.
```

## Réseau

Ces commandes permettent de gérer les connexions réseau sous Linux :

```bash
    ping       # <hôte> : Tester la connectivité réseau avec un hôte.
    ifconfig   # Afficher la configuration des interfaces réseau.
    netstat    # Afficher les connexions réseau et les ports utilisés.
    curl       # <url> Récupérer des données depuis une URL.
```

## Sécurité

Les commandes de sécurité permettent de gérer l'accès et la protection du système :

```bash
    chmod # Modifier les permissions d'un fichier ou répertoire.
    chown # Changer le propriétaire d'un fichier ou répertoire.
    ufw   # Configurer le pare-feu UFW (Uncomplicated Firewall).
    sudo  # Exécuter des commandes avec les privilèges de l'administrateur.
```

## Système

Ces commandes permettent de gérer le système et ses processus :

```bash
    ps       # Affiche les processus en cours d'exécution.
    top      # Affiche les processus en temps réel.
    df       # Affiche l'utilisation du disque.
    free     # Affiche l'utilisation de la mémoire.
    shutdown # Arrêter ou redémarrer le système.
```

## Virtualisation

Les commandes pour travailler avec la virtualisation sous Linux :

```bash
    docker  # Utiliser Docker pour créer et gérer des conteneurs.
    vagrant # Gérer des environnements virtuels avec Vagrant.
    virsh   # Commandes pour gérer les machines virtuelles sous KVM.
```

## Autre

Cette section contient des commandes diverses qui ne rentrent pas dans les autres catégories mais qui sont tout de même utiles :

```bash
    alias    # Créer des raccourcis pour des commandes.
    history  # Afficher l'historique des commandes.
    tar -cvf # <archive.tar> <fichiers> : Créer une archive tar.
    zip      # <archive.zip> <fichiers> : Compresser des fichiers avec zip.
```

## global

Cette section contient toutes les commandes du dépôt, classées par ordre alphabétique, pour une recherche rapide.

## Contribuer

Si vous souhaitez contribuer à ce projet, vous pouvez :

- Forker le dépôt.
- Créer une branche pour vos modifications (git checkout -b feature).
- Committer vos modifications (git commit -am 'Ajout de nouvelles commandes').
- Push vos modifications (git push origin feature).
- Ouvrir une pull request.

## Licence

Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.
