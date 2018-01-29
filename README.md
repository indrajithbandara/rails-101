# Découverte de Ruby on Rails ![alt text][logo]

1. La différence entre un site statique et un site dynamique
2. Le MVC
3. Les routes
4. Les Bases de Données
5. GET / POST
6. Le concept de migration
7. Les relations entre les models des BDD

### La différence entre un site statique et un site dynamique
<hr>

Une page web statique est une page web dont le contenu ne varie pas en fonction des caractéristiques de la demande, c'est-à-dire qu'à un moment donné tous les internautes qui demandent la page reçoivent le même contenu.

<div> 
<p>
À l'inverse, une page web dynamique est générée à la demande et son contenu varie en fonction des caractéristiques de la demande (heure, adresse IP de l'ordinateur du demandeur, formulaire rempli par le demandeur, etc.) qui ne sont connues qu'au moment de sa consultation.
	<a href="https://fr.wikipedia.org/wiki/Page_web_statique" target="_blank">Wikipédia</a>
</p>
</div>

<p align="center">
	<img src="https://www.ibrandox.com/SecureAdmin/LargeImg/9a6a35f3d1634154a306b1a67c6b67aa.jpg" alt="La différence entre un site statique et un site dynamique" target="_blank">
</p>


### Le MVC
<hr>
<p>
Ce design pattern est une solution reconnue permettant de séparer l’affichage des informations (la vue), les actions de l’utilisateur (le contrôleur) et l’accès aux données (le modèle).

Le modèle est ce que l’on appelle un objet, c’est le cœur de l’application. Il traite principalement les données et les interactions avec la base de données.

La vue traite ce que nous voyons dans notre navigateur web, elle restitue le modèle au sein de notre interface web et permet à l’utilisateur d’interagir avec le modèle.

Le contrôleur fait le lien entre le modèle et la vue, il gère les requêtes des utilisateurs et détermine les traitements qui doivent être effectués pour chaque action. Il va utiliser les données du modèle, les traiter et les envoyer à la vue pour que celle-ci les affiche.
<a href="https://www.supinfo.com/articles/single/1625-mvc-presentation-patron-conception" target="_blank">Source</a>

<p>

1. L’utilisateur envoie une requête HTTP

2. Le contrôleur appelle le modèle, celui-ci va récupérer les données

3. Le modèle retourne les données au contrôleur

4. Le contrôleur décide de la vue à afficher, va l’appeler

5. Le code HTML de la vue est envoyé à l’utilisateur pour qu’il puisse naviguer normalement



<p align="center">
	<img src="https://www.elephorm.com/system/files/imagecache/thumb_full_widescreen/formations/MASTER-SYMPHONY/vignettes/le-design-pattern-mvc.jpg" alt="MVC" target="_blank">
</p>

### Les routes
<hr>

### Les Bases de Données
<hr>

### GET / POST
<hr>

### Le concept de migration
<hr>


### Les relations entre les models des BDD
<hr>






[logo]: https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Ruby_On_Rails_Logo.svg/200px-Ruby_On_Rails_Logo.svg.png "Ruby On Rails"



