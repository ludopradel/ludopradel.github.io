---
layout: post
title: Ncrafts.io - When DDD meets Documentation
---

#When DDD meets Documentation 

On m'avait prévenu que [@cyriux](https://twitter.com/cyriux) était un orateur qui décoiffe, et ben je n'ai pas été déçu.

Au niveau de la forme, voici une idée du rythme : Plus de 230 slides en 45 min, moins 15sec par slides !

-----------

[@cyriux](https://twitter.com/cyriux) part du principe (partagé par un bon nombre d'entre nous) que la documentation c'est chiant et souvent obselète voire inutile.

###Mais au final qu'est-ce que la documentation ??

La documentation est un moyen de transmettre des informations, des connaissances. Un moyen de rendre accessible à tous ces connaissances.

Nous écrivons de la doc la plupart du temps parce que celle-ci est demandée (ordonné) par nos chefs !
Mais au final, une discussion ne serait-elle pas suffisante ? 
Le pair-programming ou le Mob programming sont une bonne manière de transmettre la connaissance dans une équipe par exemple.

=> *La documentation est un symptome de non confiance !*

Dans la seconde partie de son tgv (_talk à grande vitesse_) [@cyriux](https://twitter.com/cyriux) nous présente d'autres façon d'obtenir de l'information en piochant dans les pratiques DDD et BDD.

En vrac : 

- Domain immersion,
- Event storming, 
- Investigation wall, 
- Documentation vivante dans le code (cucomber) 

Il a aussi donné quelques pistes permettant de documenter notre application directement dans le code [^1].
A partir ces ces pratiques une génération de doc est possible.

Pour conclure, il a présenté le côté bénéfique que la documentation pouvait avoir sur le design de notre appli.
En effet, si la documentation fait partie intégrante de notre code, elle peut nous aider à prendre du recul sur le design de notre celui-ci.

Une idée qui m'a particulièrement plus (et qui ne me parait simple à mettre en place) est de réaliser un nuage de mot du code de notre application (en faisant disparaitre les mots clés du langage) afin de voir si les concepts qui se démarquent sont effectivement les concepts métiers de notre application.



###Conclusion

Je vous recommande de jeter un oeil sur le talk qui a été filmé et qui devrait bientôt être disponible.
Ainsi que de faire un tour sur [leanpub] [https://leanpub.com/livingdocumentation] où @cyriux est en train de préparer un livre sur le sujet. 

[^1]: _Knowledge augmentation_ : annotation ou lien vers le web directement dans le code


