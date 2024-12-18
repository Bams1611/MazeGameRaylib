# MazeGameRaylib

Ce projet est un jeu de labyrinthe développé en C++ avec la bibliothèque graphique **Raylib**. Le joueur doit naviguer dans un labyrinthe généré aléatoirement pour atteindre la sortie tout en mesurant son temps. Les scores sont enregistrés et triés par niveau de difficulté.

## Fonctionnalités

- Génération aléatoire de labyrinthes avec trois niveaux de difficulté :
  - **Facile** : Grands chemins et peu de complexité.
  - **Moyen** : Taille intermédiaire avec plus de complexité.
  - **Difficile** : Petits chemins et très complexe.
- **Gestion des scores** : Enregistrement des 10 meilleurs scores pour chaque niveau.
- **Textures intégrées** : Le joueur est représenté par une texture de rat, et la sortie par une texture de fromage.
- **Interface intuitive** :
  - Menu principal pour commencer une partie ou voir les scores.
  - Écran de fin pour rejouer ou quitter.

## Structure du Projet

- **`src/`** : Contient le code source principal, y compris les classes `Jeu`, `Labyrinthe`, `Joueur`, et `ScoreManager`.
- **`textures/`** : Contient les fichiers des textures :
  - `rat.png` : Texture du joueur.
  - `cheese.png` : Texture de la sortie.
- **`demo/`** : Contient une vidéo de démonstration du jeu.
- **`docs/`** : Contient le rapport du projet au format PDF.

## Instructions pour exécuter le projet

### Prérequis

1. **Compiler compatible C++17 ou supérieur** :
   - Par exemple, GCC, Clang ou Visual Studio.
2. **Installation de Raylib** :
   - Téléchargez et installez Raylib depuis [le site officiel](https://www.raylib.com/).
3. **Textures requises** :
   - Assurez-vous que les fichiers `rat.png` et `cheese.png` sont dans le répertoire racine ou spécifiez leur chemin dans le code.

