# Awale
Features two playable versions of the game of Awale

Le .zip est divisé en plusieurs parties :

-le dossier Jeu Console, permettant de jouer au jeu via la console intégrée à Python, pour jouer, lancer awale.py, puis faire appel à la fonction play() dans la console

-le dossier Jeu IHM, permettant de jouer au jeu via l'Interface Homme Machine, pour jouer, lancer Launcher.py, et faire appel à la fonction launchAwale() - ATTENTION, pour avoir l'affichage graphique correspondant, il est nécessaire de repréciser le chemin des images .png utilisées : dans le fichier window.py, aux lignes 50, 207 et 373, changer le chemin indiqué par celui correspondant au vôtre.

-le dossier Documentations, qui contient les .html de documentation des différentes fonctions, méthodes, modules, champs auteurs du projet

Remarques:

Une IA a pour nom Robot, il est possible de jouer à 2 joueurs, si le joueur 2 a pour nom donné "Robot", alors il sera manipulé par l'IA (i.e. équivalent à lancer une partie 1 joueur sous IHM).
