# Mini-jeux HTML

Collection de jeux classiques en **un seul fichier HTML** chacun.  
Aucune installation : ouvre le fichier dans ton navigateur.

## Comment jouer

1. Double-clique sur un fichier `.html`
2. Ou clic droit → **Ouvrir avec** → ton navigateur

---

## Liste des jeux

| Fichier | Jeu | Description | Contrôles |
|---|---|---|---|
| [`dino-game.html`](dino-game.html) | **Dino** | Runner façon Chrome offline | `Espace` pour sauter |
| [`snake-game.html`](snake-game.html) | **Snake** | Serpent, pommes, record local | Flèches / `ZQSD`, `Espace` pause |
| [`pong-game.html`](pong-game.html) | **Pong** | Raquette vs IA, premier à 7 | `W`/`S` ou flèches, `Espace` |
| [`breakout-game.html`](breakout-game.html) | **Breakout** | Casse-briques, 3 vies | Souris / flèches, `Espace` lancer |
| [`flappy-bird-game.html`](flappy-bird-game.html) | **Flappy Bird** | Vole entre les tuyaux | `Espace` ou clic |
| [`tetris-game.html`](tetris-game.html) | **Tetris** | Pièces, lignes, niveaux | Flèches, `Espace` drop, `P` pause |
| [`game-2048.html`](game-2048.html) | **2048** | Fusionne les tuiles jusqu’à 2048 | Flèches / `ZQSD` / swipe |
| [`space-invaders-game.html`](space-invaders-game.html) | **Space Invaders** | Vaisseau vs aliens | `←` `→`, `Espace` tirer |
| [`asteroids-game.html`](asteroids-game.html) | **Asteroids** | Vaisseau libre, rochers | `←` `→` tourner, `↑` thrust, `Espace` |
| [`pacman-game.html`](pacman-game.html) | **Pac-Man** | Labyrinthe, pastilles, fantômes | Flèches / `ZQSD` |
| [`memory-game.html`](memory-game.html) | **Memory** | 8 paires de cartes | Clic sur les cartes |
| [`whack-a-mole-game.html`](whack-a-mole-game.html) | **Whack-a-Mole** | Tape les taupes en 30 s | Clic |

---

## Détails par jeu

### Dino
Évite les cactus en sautant. Le score augmente avec la distance.

### Snake
Mange la nourriture rouge pour grandir. Collision mur ou corps = game over.  
Le **record** est sauvegardé dans le navigateur (`localStorage`).

### Pong
Toi à gauche (vert), IA à droite (rouge). Premier qui marque **7 points** gagne.

### Breakout
Détruis toutes les briques avec la balle. **3 vies**. Raquette pilotable à la souris.

### Flappy Bird
Espace / clic pour battre des ailes. Évite les tuyaux. Record sauvegardé.

### Tetris
7 types de pièces (I, O, T, S, Z, J, L).  
- `←` `→` : déplacer  
- `↑` / `X` : tourner  
- `↓` : descendre  
- `Espace` : hard drop  
- `P` : pause  

### 2048
Glisse la grille pour fusionner les tuiles identiques. Objectif : atteindre **2048**. Record sauvegardé.

### Space Invaders
Déplace ton vaisseau et tire sur les vagues d’aliens. **3 vies**. Les aliens descendent et tirent aussi.

### Asteroids
Vaisseau en rotation libre. Casse les gros rochers en plus petits. **3 vies**, invulnérabilité courte après un hit.

### Pac-Man
Mange toutes les pastilles. Les grosses pastilles te rendent temporairement invincible face aux fantômes. **3 vies**.

### Memory
Retourne les cartes et trouve les **8 paires**. Compte les coups et le temps.

### Whack-a-Mole
30 secondes pour taper un maximum de taupes. Le rythme s’accélère avec le score. Record sauvegardé.

---

## Technique

- HTML + CSS + JavaScript pur (pas de dépendances)
- Canvas 2D pour la plupart des jeux
- Scores / records via `localStorage` quand c’est pertinent
- Style sombre unifié (fond `#0f1419`, accents verts)


---

Amuse-toi bien 🎮
