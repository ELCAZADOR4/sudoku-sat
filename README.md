# Sudoku & solveur SAT

Projet individuel de BUT Informatique — IUT de Nantes, SAE S1-02.

## Objectif

Étudier la satisfiabilité de formules booléennes en forme normale conjonctive (CNF) et appliquer cette approche à la modélisation du Sudoku.

## Approche

- Représentation des clauses par des listes d'entiers signés.
- Évaluation des formules avec des valuations partielles.
- Recherche exhaustive par force brute.
- Parcours d'arbre, retour arrière et simplification des formules.
- Implémentation expérimentale de DPLL : clauses unitaires et littéraux purs.

## Code source

[`sudoku_sat.py`](sudoku_sat.py) contient les fonctions développées et les tests associés. Il utilise Python 3 et sa bibliothèque standard.

Cette version de travail comporte des fonctions de modélisation et de conversion de la grille Sudoku encore à compléter. La correction générale du solveur et la réussite de tous les tests ne sont pas garanties.

## Compétences

Python, logique propositionnelle, algorithmique, récursivité, structures de données et tests.
