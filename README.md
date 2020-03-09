# WannaPlayAGameOfDices

Introduction :

Dans les jeux, on a notre personnage, contrôler par nous "le joueur", mais dans les jeux il y a aussi ce qu'on appel les PNJ (personnage non joueur). Et là vous taper dans le mile, c'est que les deux class hériterons de la class Personnage.
Les PNJ auront les mêmes fonctionnalité que nous, sauf que ce n'est pas nous qui choisissons comment ils vont jouer (je parle pendant le jeu, pas nous en tant que dev), mais eux qui vont choisir.
La difficulté de l'exercice augmente car il vas falloir réussir à faire prendre des décisions à nos PNJ en fonction de sa situation.

Objectif du jeu :

Passons à l'objectif de l'exercice, de notre jeu.
Tout ce passe autour d'un jeu de dés, utiliser actuellement dans un jeu "Kingdom come delivrance".
Le but du jeu c'est d'atteindre un certain nombre de point avant le joueur adverse.
A chacun leur tour, les joueurs lance six dés. En fonction de dés lancé, un certain nombre de points seront gagner (je rajouterai une image explicative du jeu et une vidéo comme exemple).
Pendant le tour du joueur, tu peux soit te contenter des points gagnés. Soit de garder quelques dés que tu mets de côté pour une meilleur combinaison et relancer les dés que tu ne gardes pas.
Attention, si tu n'obtiens aucune combinaison sur ce second jet alors tu ne gagnes pas de points pendant ce tour. (plus d'info dans l'image).
Après c'est le tour de l'autre joueur.

Objectifs du développeur :

Chaque partie les données seront sauvegarder dans un fichier texte ou une base de donnée.
Les choix de l'IA prendra compte finalement de ces données, en fonction de certains pourcentage alors des choix seront pris plutôt que d'autre.
Exemple : L'ia à perdu en jouant le choix numéro 1, alors son pourcentage de chance de gagner baisse et finalement jouera le choix numéro 2.

Petite subtilité : Si l'IA est en avance face au joueur alors il prendra le choix numéro 1 car il obtiendra des points plus facilement mais les chances d'obtenir le maximum de point est bas.
Par contre si L'IA à du retard comparer au joueur qui risque de gagner au prochain tour alors il choisira le choix numéro 2 qui est plus risquer mais lui permettra de gagner plus de points d'un coup.

Condition de l'exercice :

Heritage
https://openclassrooms.com/fr/courses/1894236-programmez-avec-le-langage-c/1898475-decouvrez-lheritage
Savoir lire et modifier un fichier
https://openclassrooms.com/fr/courses/1894236-programmez-avec-le-langage-c/1896398-lisez-et-modifiez-des-fichiers
Challenge :

Il est vrai qu'il n'est pas très fun de toujours utiliser la console comme interface, surtout qu'il n y pas moyen de mettre en place de bouton. Mais il est possible d'y parvenir via la QT !
Par contre l'apprentissage peut être long au début, donc c'est vraiment pour le challenge !
https://openclassrooms.com/fr/courses/1894236-programmez-avec-le-langage-c/1898935-initiez-vous-a-qt
