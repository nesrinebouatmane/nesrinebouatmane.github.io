# Projet « Tu n’y peux rien » – Simulation de jeu de cartes

Mini-site de présentation réalisé dans le cadre de l’UE Génie Logiciel et Projet (GLP) 
L2 Informatique – CY Tech  

**Auteurs** : KHODJA Laiza, BOUATMANE Nesrine, BERRANDOU Nassim  
**Année** : 2026

---

## Description du projet

Ce projet consiste à concevoir et développer une **simulation informatique** du jeu de cartes  
*« Tu n’y peux rien »*.  

L’application permet à un joueur humain d’affronter plusieurs **bots** contrôlés par l’ordinateur,  
dans une partie respectant les règles du jeu original.

Le mini-site présente :
- les règles du jeu
- la mécanique de jeu
- les différents niveaux de difficulté des bots
- l’interface utilisateur
- une conclusion du projet

---

## Contenu du site

| Page | Description |
|------|-------------|
| `index.html` | Accueil, présentation du projet et objectifs pédagogiques |
| `regles.html` | Règles complètes, combinaisons, cartes spéciales, bombes |
| `mecanique.html` | Gestion des tours, ordre de jeu, validation des coups |
| `bots.html` | Niveaux de difficulté des bots (facile, moyen, difficile) |
| `interface.html` | Affichage et interactions avec l’utilisateur |
| `conclusion.html` | Bilan, compétences développées, perspectives |

---

## Fonctionnalités principales

- Jeu de 3 à 5 joueurs (humains + bots)
- Distribution automatique de 5 cartes par joueur
- Combinaisons gérées : carte simple, double, triple (bombe), série
- Cartes spéciales : **2** (écrase une combinaison), **Joker** (carte polymorphe)
- Bombe triple > carte 2 > combinaison normale
- Double joker = bombe ultime
- Pioche automatique si aucun coup possible
- Fin de partie dès qu’un joueur n’a plus de cartes
- Calcul des gains : 1 carte = 1 jeton, bombe = ×2, joker = ×4

---

## Niveaux de difficulté des bots

- **Facile** : jeu aléatoire parmi les coups valides
- **Moyen** : privilégie les petites cartes, conserve les bombes
- **Difficile** : stratégie optimisée, utilise les bombes au bon moment

---

## Technologies utilisées

- HTML5 (doctype, balises sémantiques)
- CSS3 (mise en forme, menu fixe, responsive simple)
- Pas de framework, pas de JavaScript (site statique)

---

## Validation W3C

Le code HTML et CSS a été testé avec les validateurs du W3C :

https://validator.w3.org/
https://jigsaw.w3.org/css-validator/


Chaque page inclut le badge de validation CSS.

---

## Lancer le site

1. Télécharger le dossier du projet
2. Ouvrir `index.html` dans un navigateur (Firefox, Chrome, Edge…)
3. Naviguer à l’aide du menu principal ou du sommaire fixe

Aucune installation ou serveur requis.

---

## Organisation du travail

- **Laiza** : règles du jeu, interface
- **Nesrine** : mécanique, bots
- **Nassim** : accueil, conclusion, HTML/CSS

Travail en équipe, répartition des pages, relecture croisée.

---

## Liens utiles

- [Documentation Markdown](https://commonmark.org/help/)
- [Validateur HTML W3C](https://validator.w3.org/)
- [Validateur CSS W3C](https://jigsaw.w3.org/css-validator/)

---

## Licence

Projet universitaire – Tous droits réservés aux auteurs.
© 2026 – KHODJA Laiza, BOUATMANE Nesrine, BERRANDOU Nassim
