# Pollen-visualization
## Description
Projet de visualisation de données polliniques. L'objectif est de visualiser les données de concentration pollinique au Luxembourg sur 26 ans, avec une trentaine de pollens différents répertoriés, ceci afin de pouvoir observer de potentielles variations de concentration pollinique selon les mois, les années.

## Etat du projet
En cours, non fini 

## Idées
- Données trouvées sur les pollens. Disponibles sur https://data.public.lu/en/datasets/pollen/ (consulté le 19.05.2022)
- Possibilité de visualisation : https://d3-graph-gallery.com/graph/density2d_hexbin.html 
- Possibilité choisie : une line chart : https://d3-graph-gallery.com/graph/line_basic.html. Ce serait intéressant de visualiser selon le/les pollens sélectionnés. Pour utiliser plusieurs groupes, voir ici : https://d3-graph-gallery.com/graph/line_several_group.html. Pour choisir le pollen à visualiser, voir ici : https://d3-graph-gallery.com/graph/line_filter.html. 

## Notes
- Pour l'axe des X, utiliser d3.scaleTime plutôt que d3.scaleLinear


## Carnet de bord
_2022.05.19_
- 1h30 : recherches idées, recherches de sets de données
-  2h : Jouer avec les données, nettoyer les données, différents tests

_2022.05.19_
- 2h : Comprendre comment faire une échelle et une line chart 