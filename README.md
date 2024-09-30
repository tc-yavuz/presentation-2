# Cercle Musical
## Idée
### Concept
3 à 6 personnes sont assignées à différents instruments représentant un genre musical (jazz, rock, etc.). Ensemble, elles forment un groupe et créent de la musique.

L’environnement est équipé de lumières LED qui changent de couleur en fonction du genre musical joué. Au centre du groupe se trouve une roulette interactive. En la tournant, les participants peuvent changer de genre musical, ce qui entraîne non seulement un changement des instruments, mais également une modification des couleurs et des ambiances lumineuses associées à chaque genre.

### Objectifs
L'objectif est de faire découvrir aux participants des genres musicaux qu'ils n'écoutent pas souvent, tout en leur offrant un moment amusant et immersif. Grâce à un système interactif avec musique, lumière et instruments, ils pourront explorer différents styles et s'amuser à jouer ensemble. L'expérience cherche à éveiller la curiosité musicale et à offrir un plaisir simple autour de la diversité musicale.

### Motivations
Passionné par la musique et la découverte des genres de manière interactive, j’ai été inspiré par Duetti: Mobili musicali pour créer une expérience immersive, combinant plaisir musical et technologie.

## Scénario
````mermaid
flowchart TD
    A[Interacteur] -->|Joue les instruments| B{Sons_musique}
    B --> C[Effet]
    C --> D[Lumière]
    C --> E[Sons]
    C --> F[Vidéos]
    A --> G[Change Genre Musique]
    G --> |Joue les instruments|B
    D --> H{Fin Interaction}
    E --> H
    F --> H
    H --> |Oui|I[Veille]
    H --> |Non|B
    H --> |Change|G
````

## Ambiance
### Planche d'ambiances visuelles
<img src="https://lh4.googleusercontent.com/nFn-T_Yr9ymG_vMq0TOesnAoKBoVv5d2FS_fjJEsLjKl8TUPM9EEY0JVFB3aG_NJcxDldrwbguIYA661Uq-8OFIuRjP9yejWl0Joi0G0AAfX0LH4__oFTjmcXWPK6pXTQJpJT9jQKaG4"></img>

### Planche d'ambiances sonores

- [Jazz - Trompette](https://www.youtube.com/watch?v=US2uDbkiMPQ)
- [Rock - Guitare Électrique](https://www.youtube.com/watch?v=LTeW10EefKI)
- [Classique - Piano](https://www.youtube.com/watch?v=xejeEtdfgZY)


### Références artistiques
Duetti: Mobili Musicali, Parcours Musical Immersif

## Technologies
### Support médiatique
- Audio

### Matériel
- Capteur/Détecteur
- Clavier Midi
- Lumières LED
- Haut-Parleurs

### Logiciels
- Arduino
- Touch Designer
- Reaper
- Max
