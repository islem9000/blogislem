CREATION PROJET
* composer create-project symfony/website-skeleton blogislem "5.4.*"

LIASON PROJET AVEC GIT
* git remote add origin https://github.com/islem9000/blogislem
* git add
* git commit -m "first commit"
* git push --set-upstream origin main

CREATION BASE DE DONNEES
* symfony console doctrine:database:create
* composer require annotations 

DEMARRAGE SERVER
* symfony serve

CREATION ENTITE' UTILISATEUR
* symfony console make:entity
* symfony.exe console make:migration
* symfony.exe console doctrine:migrations:migrate

CREATION ENTITE' COMMENT
* symfony console make:entity
* symfony.exe console make:migration
* symfony.exe console doctrine:migrations:migrate

CREATION ENTITE' ARTICLE
* symfony console make:entity
* symfony.exe console make:migration
* symfony.exe console doctrine:migrations:migrate

MISE à JOUR DU REPOSITORY
* -git commit
* -git push
* -git status
