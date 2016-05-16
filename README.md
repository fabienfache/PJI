# Projet de Master 1 Informatique Semestre 2

Intro
=====

Il s'agit du projet individuel effectué dans le cadre de la première années de master informatique réalisé avec ma binôme Amina Boussalia 
Cependant sur cette version vous ne trouverez que ma reflexion personnel sur le sujet ainsi que mes avancées.
Le but du projet est de rendre une application web '__responsive__' afin qu'elle puisse être portable et redimensionnable sans pour autant avoir de problème
d'affichage ou de débordement de contenu.
Il est donc question essentiellement question de framework responsive (Bootstrap) de HTML, CSS et JavaScript.
Le site est une application de suivi de patient atteint de leucémie.

Challenge
=========

Il faut réaliser 3 versions sans "__aucun scroll__" tout en exploitant le maximum de surface et integrer l'existant. Puis définir un mode à la fois __hors ligne__ qui permet 
de consulter et gérer des données et __connecté__ qui peut se synchroniser avec le serveur (non commencé).

Contenu
=======

Actuellement le projet est toujours en phase de __prototypage__ aucune intégration du code n'a été effectué (__mais quelque test non fournis__).
Le browser contient une version "__mobile__" et une autre version qui devrait être celle de la "__tablette__".
Il existe pour chaque version un mode "__portrait__" et "__landscape__". Néanmoins il existe encore quelque soucis au niveau de la transition entre différents elements.
J'ai abandonné l'idée de faire des "__clones carrés proportionnels à la hauteur__" pour donner une taille fixe. Il faut néanmoins faire attention aux trés petite tailles.


Mobile
======

Le choix du carrousel pour le mode mobile me parrait être un "choix délicat", car il permet d'une part d'exploiter la totalité de l'écran tout en ayant de bons moyens
d'accés au différentes fenêtre (sequentiellement ou grâce au "carrousel-indicator"), mais pose problème avec l'elaboration d'un mode "bureau". En effet, pour un rendu 
cohérent il faudrait disposer des fenêtres que le carrousel contient et les redispatché en quatre zone (graphe, gride, liste lymphocyte, info).

Tablette
========

Partie un peu plus délicate, elle n'exploite plus le caroussel mais possède une majeur section à gauche et une plus petite section à droite qui contient 3 sections disposés en colonne.
La fonctionnalité principale de cette version et de pouvoir "swapper" le contenu d'une petite section avec le contenu de la grande section par "double-click" (__JQuery__).

Bureau
======

Le modèle n'est pas encore défini même si celle ci devrait être "similaire" à la version original.



