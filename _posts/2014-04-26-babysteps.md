---
layout: post
title: Baby Steps en Coding dojo
---

Nous disposions de seulement 1h30 pour découvrir les [babys steps](http://coderetreat.org/profiles/blogs/taking-baby-steps) en Coding Dojo.
Ayant déjà pratiqué cet exercice lors de [Code Retreat](http://coderetreat.org/about), je savais à peu près comment le présenter. [@avernois] et [@VincentFERRIES] m'ont aiguillé dans le choix du kata, merci à eux.

La séance s'est déroulé de la façon suivante :

###Explication des règles du jeu <div style="float:right">*15 minutes*</div>  

#### Rappel du besoin du kata Mars Rover

>* Développer une API qui déplace le Mars Rover sur une grille
>* Une première méthode prends en paramètre les coordonnées initiales (x,y) et sa direction (N,S,E,W)
>* Une seconde méthode prends une chaine de caractère en paramètre correspondant à la commande à executer
>  * les commandes 'f' et 'b' permettent d'avancer et reculer
>  * les commandes 'r' et 'l' permettent de tourner sur la gauche et tourner sur la droite
>* Implémenter une façon de faire boucler la grille d'un bord à l'autre
>* Implémenter la détection d'obstacles
>* Example: Le Mars Rover sur une grille de 100x100 à la position (0, 0) en direction du Nord. En donnant la commande "ffrff" au Mars Rover il doit finir à la position (2, 2)
>* Tips: utilisé des classes multiples et du TDD
>* [Plus d'infos ici](http://craftsmanship.sv.cmu.edu/katas/mars-rover-kata#sthash.uvI3QFRX.dpuf)


#### Rappel des commandes git utiles

>
>* git init pour initialiser le repo
>* git add *fichier*
>* git commit -m "*message*"
>* git reset hard --HEAD^
>

#### choix du binome, de l'environnement de développement...

###Déroulement du coding dojo <div style="float:right">*40 minutes*</div>

Nous avons utilisé le format Kata (et non Randori) pour cet exercice. C'était important pour que tout le monde comprenne bien le format des baby steps. 
Comme me l'a fait remarquer [@avernois], pour que ça fonctionne, "Il faut vivre l'experience soi même sur la durée".

Chacun a choisit un binome, un langage de programmation puis muni d'un timer programmé sur 2 minutes nous avons débuté l'exercice.

###Retrospective <div style="float:right">*20 minutes*</div>

Tour de table des ressenties de chacun sur l'exercice, en vrac : 

* Le travail sous pression par rapport à la qualité du code. 
* Est-ce qu'une telle technique est utilisable dans la vie de tout les jours ? 
* Nécessité de commiter fréquemment.
* Nécessité de se focaliser sur une seule chose (ouverture sur les pomodoro;..)
* Permet une boucle de feedback rapide.


[@avernois]:http://twitter.com/avernois
[@VincentFERRIES]:http://twitter.com/VincentFERRIES


