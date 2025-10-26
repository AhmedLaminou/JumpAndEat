# Ahmed Laminou Platformer Game

Un jeu de plateforme complet développé avec Pygame.

## Description
Ce jeu est un platformer où vous incarnez un personnage devant sauter de plateforme en plateforme, ramasser des pièces, éviter les ennemis, et progresser à travers plusieurs niveaux. Le jeu propose :
- Plusieurs niveaux générés dynamiquement
- Gestion du score et de l’historique des scores
- Système de vies
- Ennemis mobiles
- Sons (saut, pièce, game over, etc.)
- Boutons pour recommencer, quitter, mettre en pause et continuer
- Interface simple et efficace

## Contrôles
- **Flèche gauche/droite** : déplacer le joueur
- **Espace** : sauter
- **P** : pause/continuer
- **Souris** : cliquer sur les boutons (Recommencer, Quitter, Rejouer)

## Installation
1. Installez Python 3.x et Pygame :
   ```pwsh
   pip install pygame
   ```
2. Placez les fichiers du jeu dans le dossier `Pygame`.
3. Placez les fichiers sons (`jump.wav`, `coin.wav`, `gameover.wav`, `hit.wav`) dans un dossier `assets` à la racine du projet.
4. Lancez le jeu :
   ```pwsh
   python main.py
   ```

## Fichiers
- `main.py` : boucle principale, gestion du joueur, des niveaux, de l’interface
- `other.py` : gestion des niveaux (Level)
- `another.py` : gestion de l’historique des scores (ScoreManager)
- `assets/` : sons du jeu

## Auteur
Ahmed Laminou

## Améliorations possibles
- Ajout de graphismes personnalisés
- Système de sauvegarde
- Plus d’ennemis et de power-ups
- Classement en ligne
