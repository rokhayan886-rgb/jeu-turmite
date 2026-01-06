# Jeu de Turmites (Fourmis de Langton)

## Description

Ce projet est une implémentation en Python du **jeu des Turmites** (ou fourmis de Langton) avec interface graphique **Tkinter**.  
Le jeu permet de simuler le déplacement de plusieurs fourmis sur une grille représentant une "planète", avec différentes couleurs et règles de mouvement.  

Le projet comprend deux fichiers principaux :  
- `S08_TP15.py` : Définit les classes de base du jeu (`PlanetTk`, éléments de la grille).  
- `Turmites.py` : Contient la logique du jeu des Turmites, la simulation des fourmis et l'interface graphique.  

---

## Fonctionnalités

- Placement interactif des fourmis sur la grille avec un clic de souris.
- Simulation continue ou pas-à-pas via les touches du clavier :
  - **Espace** : démarrer/arrêter la simulation
  - **Flèche droite** : effectuer une étape unique
- Chaque fourmi a une couleur aléatoire et suit les règles classiques des Turmites.
- Réinitialisation complète de la grille avec bouton reset.
- Interface graphique avec Tkinter, possibilité de personnaliser :
  - Taille de la grille
  - Taille des cellules
  - Vitesse de déplacement des fourmis

---

## Prérequis

- Python 3.x
- Modules Python :
  - `tkinter`
  - `random`
  - `copy`

> Tkinter est généralement inclus avec Python. Sinon, installer via :  
> ```bash
> sudo apt install python3-tk   # Linux
> ```

---

## Installation

1. Clonez le dépôt GitHub :  
```bash
git clone https://github.com/rokhayan886-rgb/jeu-turmite.git
