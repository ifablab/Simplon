# Projet sélection formation CDA


*Révision UML Api Rest
*Choix techno (docker ? -> LAMP, php7.5 ou 8?, mysql ou MariaDB)
*langage Php, Js, api rest, Postman
*Programmation POO
*CRUD (Creation, Read, Update, Delete)

A partir du diagramme suivant :

![diagramme](./cda.PNG)

## Dans un dépôt Gitlab/Github dont tu nous donneras le lien :
* créer les entités correspondantes ;
* créer les composants d'accès aux données (Repository/DAO) pour ces entités ;
* rendre le CRUD accessible via une API REST ;
* décrire dans un fichier tes choix, la méthodologie employée, les difficultés rencontrées, les ressources utilisées, le temps passé…

Aucune contrainte sur le langage, mais il est interdit d'utiliser un framework ou un ORM.


### 1) Création de 4 entités pour la BDD avec des contraintes:
##Utilisation du diagramme des classes, UML.
D’après ce diagramme de class, nous voulons que l’entité USER, puissent créer un sujet, entité TOPIC, dans un forum, dans une catégorie, entité CATEGORY, pour classer le post, entité POST.

### 2) Créer connexion BDD pour chaque Entité
