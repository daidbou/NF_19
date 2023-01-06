# Projet NF19 - A22

Réalisé par David Bounliane et Tristan Jogee

# Entreprise GiftCard
# Déploiement dockers WordPress et MySQL

## Ajouter ce git à votre répertoire

Pour cela, il est nécessaire que vous installiez **Git** sur votre appareil, si vous ne l'avez pas vous pouvez le retrouver ici :

https://github.com/git-guides/install-git

Puis veuillez exécuter la commande suivante :

```git clone https://github.com/daidbou/NF_19```

## Installer docker sur votre appareil

### Pour Linux

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/linux-install/

### Pour Windows

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/windows-install/

### Pour MacOS

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/mac-install/


## Lancer le docker

Dans votre terminal, veuillez vous placer dans le dossier où se trouve le fichier *docker-compose.yml*.

Puis veuillez exécuter la commande suivante pour lancer le docker-compose.

```[sudo] docker-compose up -d```

## Accéder au wordpress

### Visiter le Wordpress

Veuillez vous rendre à l'adresse  *localhost:8000*  sur votre navigateur internet préféré pour accéder et visiter le wordpress.

### Modifier le WordPress

Voici les identifiants de connexion du compte pour modifier le WordPress :

identifiant : nf19

mot de passe : nf19

Veuillez-vous rendre à l'adresse suivante pour accéder à la personnalisation du Wordpress :

http://localhost:8000/wp-admin/

## Accéder au serveur MySQL

###Visiter phpMyAdmin

Veuillez vous rendre à l'adresse *localhost:8080* sur votre navigateur internet préféré pour accéder et visiter phpMyAdmin.  
Les identifiants sont :

- login : wordpress
- password : wordpress

## Arrêter le docker

Exécutez la commande suivante dans votre terminal pour arrêter le docker-compose.

```[sudo] docker compose down```
