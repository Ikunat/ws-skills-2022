# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️

Pour créer une image docker il nous faut un Dockerfile, qui rassemble les instructions permettant de compiler une image d'une application.
Ce Dockerfile se trouve à la racine du dossier dont on souhaite faire l'image (ex : /client).

Afin de créer l'image, il va falloir écrire "docker build -t lenomdudossieroùsetrouveledockerfile" dans le terminal.
Pour vérifier si l'image a bien été montée : "docker image ls".

Une image contient tous les élèments nécessaires à l'exécution de l'application:

    - le système d'exploitation
    - l'environnement d'exécution
    - les sources de l'application


- l'éxécution d'un container ✔️

Lorsqu'une image docker est compilée, il faut encore l'exécuter.

Pour cela nous allons utiliser la commande "docker run (-d) lenomdudossieroùsetrouveledockerfile", qui permet de démarrer un container.
Pour vérifier si le container est bien démarré : "docker ps".


- l'orchestration de containers avec docker-compose ❌ / ✔️


## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
