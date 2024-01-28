# Formula Fun

Ce projet de jeu de voiture sur Unreal 5 (v5.3.2) a été réalisé dans le cadre de la Global Game Jam 2024. Le thème de la jam était "Make me laugh" C'est pourquoi nous avons décider de réaliser un jeu de course fun assez basé sur la physique ! 

Voici la listes des cointraintes qui ont été choisis pour ce jeu :
- Sharing is caring   - (Sponsored by Github): Share the source code for your submission in a public GitHub repository and list the URL on your submission page.
- Lunch Special: Your game can be played with one hand. The other hand is free to hold your sandwich.
- Mouthing Off: "Audio is an important part of game design, but with so many DAWs and midi keyboards to choose from, it can be hard to choose! So we're going back to basics! For this diversifier, every bit of audio in your game must be made with your mouth! Singing, beatboxing, and little lip smacks for impact are all allowed and encouraged! You may still use software to trim the audio files as needed, but they should not be artificially created. Good Luck!"
- Forrest Gump: The character only has the "Yes" option in all dialogues with NPCs.
- Woodstock vibes: The art of your game is done in psychedelic style.

## Concepte du jeu

Dans ce jeu, le joueur participe à une course truquée : 
À chaque début de course, il reçoit un message de la part de l'annonceur, lui donnant l'opportunité de remporter gros s'il finit la course à une certane place. Sur le circuit, les participants doivent faire autant de tour qu'ils le peuvent, car jouant contre la montre. 

Cependant, les adversaires sur le circuit sont très peu compétent au volant. Certain peuvent avoir reçu des objectifs similaires et vouloir également arriver en dernier. Le joueur devra donc trouver un moyen pour atteindre son objectif, coûte que coûte, quitte a aider ses rivaux.

## Contrôles

> W -> Avancer
> S -> Reculer
> A -> Tourner à gauche
> D -> Tourner à droite
> Espace -> Frein a main
> Effacer -> Se retourner (lorsque renversé)
> Alt + F4 -> Quitter le jeu


## UI
En haut a gauche : La liste des participants triée selon leurs ordres dans la course (les joueurs clandestins n'y figure donc pas).
En bas à droite : Le compteur de vitesse du véhicule (en km/h).
En bas à gauche : Le temps restant avant la fin de la course.

## Démo
Démonstration en jeu : 

- La course démare après un décompte. Certains font demi-tour.
![Démonstration départ](demo_depart.gif)

- Les joueurs peuvent se rentrer dedans
![Démonstration collision](demo_collision.gif)

- Sur la piste se trouve des boosteurs
![Démonstration booster](demo_booster.gif)

## Contributeurs du projet

- Auberval Florian : Level design et effet visuel
- Auliac Yann : Modélisation et animation
- Barron Quentin : Sound design et musique
- Cavailles Théo : Programmation et ajout
- Geslin Antoine : Programmation

