Spider-Nightmare
================

Game programmed in C# with XNA and a Kinect.
The player has to move his arms in front of a Kinect in order to move the arms of a character which is constantly firing projectile on the screen. By directing the arms, the player is able to direct the projectiles. Spiders are permanently spawning on the screen.
The goal of the game is to kill as many spiders as possible in order to make the greatest score possible without being touched 3 times by the spiders. 

The game possesses a combo system. The player start with a combo multiplier of 1. Each time the player kill a spider, its score combo multiplier is incremented by one. The combo multiplier comes back to 1 as soon as you are touched by a spider.

The game is composed of 5 difficulty modes : Easy, Normal, Medium, Hard and God. At each difficulty is linked a score multiplier and a spider speed multiplier.

| Difficulty Mode  | Score Multiplier | Speed Multiplier |
| ---------------- | ---------------- | ---------------- |
| Easy             | 1                | 0.5              |
| Normal           | 2                | 1                |
| Medium           | 3                | 1.5              |
| Hard             | 4                | 2                |
| God              | 5                | 2.5              |

Killing a spider gives you 5 points. The score system is working with the following formula :
 * New score = Actual score + 5 * combo multiplier * difficulty multiplier
 
===============

Jeu programme en C# avec XNA et une Kinect.
Le joueur doit bouger ses bras en face d'une Kinect afin de faire bouger les bras d'un personnage qui tire constamment des projectiles à l'écran. En dirigeant les bras, le joueur est capable de diriger les projectiles. Des araignées apparaissent de façon permanente à l'écran.
Le but du jeu est de tuer autant d'araignées que posssible afin de réaliser le plus grand score possible sans être touchés 3 fois par les araignées.

Le jeu possède un système de combo. Le joueur commence avec un combo multiplicateur de 1. Chaque fois que le joueur tue une araignée, son combo multiplicateur de score est augmenté de un. Le combo multiplicateur retourne à 1 dès lorss que le joueur est touché par une araignée.

Le jeu est composé de 5 modes de difficultés : Facile, Normal, Moyen, Difficile et Dieu. A chaque difficulté est lié un multiplicateur de score et un multiplicateur de vitesse des araignées.

| Mode de difficulté  | Multiplicateur de score| Multiplicateur de vitesse |
| ------------------  | ---------------------- | ------------------------- |
| Facile              | 1                      | 0,5                       |
| Normal              | 2                      | 1                         |
| Moyen               | 3                      | 1,5                       |
| Difficile           | 4                      | 2                         |
| Dieu                | 5                      | 2,5                       |

Tuer une araignée vous apporte 5 points. Le système de score fonctionne selon la formule suivante :
 * Nouveau score = Score actuel + 5 * combo multiplicateur * multiplicateur de difficulté
