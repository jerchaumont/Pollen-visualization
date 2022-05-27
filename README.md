# Pollen-visualization
## Etat du projet
En cours, non fini 
## Description
Projet de visualisation de données polliniques. L'objectif est de visualiser les données de concentration pollinique au Luxembourg sur 26 ans, avec une trentaine de pollens différents répertoriés, ceci afin de pouvoir observer de potentielles variations de concentration pollinique selon les mois, les années.

Les données sont exprimées en pollens/m3. Selon [pollenetallergie.ch](https://www.pollenundallergie.ch/informations-polliniques/donnees-polliniques/donnees-polliniques-mesures-des-pollens?pflanzenartId=9&messstationId=4&startDatum=2021-04-02&scrollto=tagesuebersicht) :
- Valeur 0–1: aucune concentration (ou station hors-service)
- Valeur 1–20: faible concentration
- Valeur 20–50: concentration moyenne
- Valeur 50–150: concentration forte
- Valeur >150: concentration très forte

## Idées
- Données trouvées sur les pollens. Disponibles sur https://data.public.lu/en/datasets/pollen/ (consulté le 19.05.2022)
- Possibilité de visualisation : https://d3-graph-gallery.com/graph/density2d_hexbin.html 
- Possibilité choisie : une line chart : https://d3-graph-gallery.com/graph/line_basic.html. Ce serait intéressant de visualiser selon le/les pollens sélectionnés. Pour utiliser plusieurs groupes, voir ici : https://d3-graph-gallery.com/graph/line_several_group.html. Pour choisir le pollen à visualiser, voir ici : https://d3-graph-gallery.com/graph/line_filter.html. 

## Notes
- Pour l'axe des X, utiliser d3.scaleTime plutôt que d3.scaleLinear
- Tuto utile : https://vizhub.com/curran/73bcdb68be6b4500b03827c9d58defba?file=useData.js 
- Explication sur les timelines : https://www.goodmarketing.club/guide/d3-js-multiple-lines-chart-w-line-by-line-code-explanations/ 


## Carnet de bord
_2022.05.19_
- 1h30 : recherches idées, recherches de sets de données
-  2h : Jouer avec les données, nettoyer les données, différents tests

_2022.05.19_
- 2h30 : Comprendre comment faire une échelle et une line chart 

_22.05.27
- 45 min : test des données sur un graphe axial 