# Escape Backrooms

Escape game 3D en vue à la première personne, dans les backrooms. Chaque salle a son décor, son ambiance sonore et sa chaîne d'énigmes : une découverte en débloque une autre jusqu'à la clé. Avec la clé, la porte s'ouvre et le joueur tombe dans la salle suivante.

**Jouer :** 
https://megane-digit.github.io/escape-backrooms/
Fonctionne sur PC, Android et iPhone, directement dans le navigateur. Rien à installer.

## Le jeu

- 4 étapes en pyramide : 4 salles, puis 3, puis 2, puis la salle finale (10 salles au total).
- Un compte à rebours par salle, 1 à 3 étoiles selon le temps restant.
- Aide à 3 niveaux (coup de pouce, indice précis, solution), chaque niveau coûte du temps.
- Aucune connaissance extérieure nécessaire : tout se résout avec ce qu'on voit dans la salle.
- Trois difficultés : Facile, Normal, Difficile.

**Salles disponibles pour l'instant (étape 1) :** le Bureau Jaune, la Piscine Vide, le Parking Souterrain, la Cuisine Abandonnée. Les autres arrivent.

## Commandes

| | PC | Mobile |
|---|---|---|
| Se déplacer | Z Q S D ou flèches | Joystick à gauche |
| Regarder | Souris (clic pour verrouiller) | Glisser sur la moitié droite de l'écran |
| Interagir | E | Toucher l'objet, ou bouton AGIR |
| Indices | H | Bouton « Indices » |
| Courir | Maj | Pousser le joystick à fond |
| Pause | Échap | Bouton ⏸ |

Sur téléphone, jouer en **paysage**. Les écouteurs sont recommandés.

## Mettre en ligne (GitHub Pages)

1. Le jeu tient dans un seul fichier : `index.html`.
2. Dans le dépôt : **Settings → Pages → Deploy from a branch → `main` / root**.
3. Après une ou deux minutes, le jeu est disponible à l'adresse indiquée plus haut.

Pour mettre à jour, remplace `index.html` et fais un commit. Si la nouvelle version n'apparaît pas, vide le cache du navigateur.

## Technique

- HTML, CSS et JavaScript dans un seul fichier.
- [Three.js](https://threejs.org/) r128, chargé depuis cdnjs.
- Polices : Sora, Inter et JetBrains Mono, chargées depuis Google Fonts.
- Décors, textures, musique et bruitages générés dans le navigateur (canvas et Web Audio).
- Réglages sauvegardés dans le navigateur (`localStorage`).
- Une connexion internet est nécessaire au premier chargement.
