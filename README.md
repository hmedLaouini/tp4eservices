# Homework TP4 e-Services

Ce travail a été fait par le trinôme se composant de : 

 - Ahmed Touaiti
 - Ghaith Troudi
 - Ahmed Laouini

Ce document servira à illustrer la démarche faite pour accomplir les tâches nécessaires.


# Installation des outils
La première phase est l'installation des outils suivants:

 - [Docker](https://docs.docker.com/install/)
 - [IntelliJ](https://www.jetbrains.com/idea/download/)
 - [JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)



# Dockerisation des services

La 2ème phase est la dockérisation des services ce qui inclue les étapes suivants:

 1. Ajouter le plugin "docker-maven-plugin" de "io.fabric8" dans le pom.xml de chaque service.
 2. Création des images dans l'ordre suivant :
	 1. config-service
	 2. les autres images
 3. Ajouter le docker-compose.yml
 4. Lancer la commande `docker-compose up` 
 5. Tester les services.
