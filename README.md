# docup
Scripts de mise à jour des conteneur Docker

## Pré-requis

 - Docker 
 - Docker-compose V2


## Ajout du script en tant que commande bash

    mkdir scripts && cd scripts && git clone https://github.com/Wolf117Warrior/docup.git && cd docup && chmod +x docup && sudo ln -s ~/scripts/docup/docup /usr/bin/docup && nano docup

Vous n'êtes pas obligé de prendre toute la commande, ajustez en fonction de votre configuration et votre besoin.

## Configuration du script

Il faut dans un premier temps renseigner le bon dossier ou se trouve vos applications dockérisé et les fichiers docker-compose.yml.

Modifiez la variable CHEMIN correspondant au chemin de votre dossier.
 
    #!/bin/bash
    ######## Variable ###########
    CHEMIN=/stockage/docker_apps/
    ############################
  
Et ajouter également **sudo** au début des commandes si cela est nécessaire avec votre utilisateur courant.

Vous n'aurez plus qu'a lancer la commande de cette manière **docup**, et suivez les instructions.
