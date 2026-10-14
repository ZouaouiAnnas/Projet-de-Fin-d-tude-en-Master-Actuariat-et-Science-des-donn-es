# Théorie des équations différentielles stochastiques rétrogrades : représentation des martingales, monotonie et cadre markovien

## Présentation du projet

Ce mémoire de recherche a été réalisé à l’École Nationale d’Ingénieurs de Tunis (ENIT), dans le cadre du Mastère de Recherche en **Actuariat, Sciences des Données et Contrôle Stochastique**, au cours de l’année universitaire 2025–2026.

Le travail porte sur l’étude théorique des équations différentielles stochastiques rétrogrades (EDSR), des outils fondamentaux du calcul stochastique et de leurs applications en finance quantitative.

## Objectifs

- Étudier le théorème de représentation des martingales et son rôle dans la construction des solutions des EDSR.
- Analyser les conditions d’existence et d’unicité des solutions dans le cadre lipschitzien et dans le cadre monotone.
- Étudier les propriétés des EDSR dans un cadre markovien.
- Illustrer les applications numériques du calcul stochastique à travers la simulation de trajectoires financières et la valorisation d’options américaines.

## Méthodologie

Le travail est organisé autour de deux axes complémentaires.

### 1. Étude théorique

- Rappels de probabilités, de martingales et de calcul stochastique.
- Étude et démonstration du théorème de représentation des martingales.
- Analyse des résultats d’existence et d’unicité des solutions des EDSR.
- Extension au cadre monotone, avec des estimations a priori et des résultats de stabilité.
- Étude des propriétés du flot stochastique et des propriétés de Markov.

### 2. Application numérique en finance quantitative

- Modélisation du prix d’un actif financier par un mouvement brownien géométrique.
- Simulation de trajectoires par la méthode de Monte-Carlo.
- Étude du problème d’arrêt optimal et de l’enveloppe de Snell.
- Application de la méthode de Longstaff–Schwartz pour estimer la valeur de continuation d’un put américain.
- Utilisation de la régression polynomiale par moindres carrés pour approximer les espérances conditionnelles et analyser la stratégie d’exercice optimale.

## Outils utilisés

- **Python** : implémentation des simulations numériques.
- **Jupyter Notebook** : développement, exécution et visualisation des simulations.
- **Anaconda** : environnement de travail Python.
- **Calcul stochastique et probabilités** : fondements théoriques des modèles étudiés.

## Principaux résultats et observations

- Étude des conditions permettant d’établir l’existence et l’unicité des solutions des EDSR dans différents cadres.
- Analyse du rôle du théorème de représentation des martingales dans l’étude des EDSR.
- Vérification numérique des propriétés de dispersion du mouvement brownien géométrique par comparaison entre résultats empiriques et théoriques.
- Illustration de la méthode de Longstaff–Schwartz pour estimer les valeurs de continuation et identifier les situations où l’exercice anticipé d’un put américain peut être optimal.
- Mise en évidence de l’intérêt des méthodes de Monte-Carlo et de régression pour traiter des problèmes de valorisation financière et d’arrêt optimal.

## Organisation du dépôt

La structure du dépôt sera organisée selon les fichiers effectivement disponibles :

- `rapport/` : mémoire de recherche au format PDF.
- `presentation/` : présentation de soutenance au format PDF, si disponible.
- `notebooks/` : notebooks Python de simulation et de valorisation.
- `src/` : scripts Python réutilisables, si disponibles.
- `figures/` : graphiques générés par les simulations.

## Perspectives

Ce travail ouvre plusieurs pistes d’approfondissement, notamment l’étude des EDSR avec des coefficients plus généraux, l’extension aux modèles comportant des sauts et le développement de méthodes numériques pour l’approximation de leurs solutions.

## Cadre académique

- **Établissement :** École Nationale d’Ingénieurs de Tunis (ENIT)
- **Formation :** Mastère de Recherche en Actuariat, Sciences des Données et Contrôle Stochastique
- **Année universitaire :** 2025–2026

Projet académique réalisé dans le cadre d’un mémoire de recherche.
