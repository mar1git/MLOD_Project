# MLOD_Project
PROJET - TETRIS COLOR
avec Raylib

Lien de la vidéo: https://drive.google.com/file/d/1U_j2udOYT7dhOae0Y1lsdNYmo1KTawd9/view?usp=sharing

Ce projet est une implémentation du jeu Tetris avec la bibliothèque RAYLIB. 
Note : Tout le code source est contenu dans un seul fichier tetris.c.

COMPILER LE PROGRAMME

Pour mon cas j'ai utilisé Notepad++ Raylib qui facilite grandement l'installation et la compilation de la bibliothèque.

Sur Linux, on peut executer cette ligne de commande, après avoir préalablement installé Raylib.
gcc main.c -lraylib -lGL -lm -lpthread -ldl -lrt -lX11

LANCER LE JEU TETRIS

Afin de lancer le projet, il vous suffit de télécharger "tetris.zip", puis d'exécuter le fichier "tetris.exe". Pour les utilisateurs de linux, exécuter le projet via le logiciel wine.

JOUER AU JEU TETRIS

Ce projet implémente toutes les fonctionnalités de base du jeu Tetris, soit:

- des pièces générées aléatoirement tombent sur la carte
- on peut les deplacer et changer leur orientation
- lorque l'on complète une ligne notre score augmente
- si nos pièces depassent l'écran on perd

TOUCHES

Menu Principal :

[SPACE] : Lancer la partie
[^] : Change l'orientation de la pièce
[<] : Deplace la pièce vers la gauche
[>] : Deplace la pièce vers la droite
