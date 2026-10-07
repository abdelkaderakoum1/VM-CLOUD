\###############################

# ETAPE 1

\###############################



1. Qu'est ce qu'une machine virtuelle

Il s'agit d'un environnement que l'on isole, et où on crée une autre machine, avec qui on partage des ressources de notre machine afin d'y installer un OS que l'on pourra utiliser



2. Deux avantages de la virtualisation dans un environnement professionnel.
* Isoler les différentes services d'une application.
* Créer des environnements pour pouvoir faire des test.



3. Différence entre travailler sur notre ordinateur et sur la machine virtuelle

La VM est isolé de notre ordinateur et il aura un accès limité sur nos ressources et sur les fichiers, tandis que sur notre machine on a plus de contrôle dessus.



\###############################

# ETAPE 2

\###############################



1. Qu'est ce qu'un conteneur docker

Un conteneur est une isolation une certaine partie de la machine avec son OS pour partager les ressources mais en même temps isoler les systèmes de fichiers



2\. Un conteneur doit être installé sur un OS dont elle va dépendre mais une VM est un environnement qui est conçu pour installer un OS.



3\. Les conteneurs sont particulièrement adapté au déploiement d'application car, dépendament de l'OS sur lesquels il sera installé, ce dernier contient déjà tout l'environnement dans lequel toute les parties de notre application aura besoin pour tourner. Il lui faudra donc juste le bon OS pour fonctionner et le conteneur pourra faire tourner l'application.



\###############################

# ETAPE 3

\###############################



1. Dockerfile est préférable à la configuration manuelle d'un conteneur car on pourra de cette facon créer plusieurs conteneur à la chaine.



2\. Une image Docker est la sauvegarde des spécification d"un conteneur et un conteneur Docker est l'instanciation de cette image 











