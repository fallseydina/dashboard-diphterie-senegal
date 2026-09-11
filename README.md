# Dashboard de suivi de l'épidémie de diphtérie au Sénégal

Dashboard interactif développé avec **R et Quarto** pour synthétiser et cartographier la situation de l'épidémie de diphtérie au Sénégal.

**Situation au 08 septembre 2026**

## Objectif

Ce projet vise à transformer des données de surveillance épidémiologique en informations synthétiques et facilement interprétables pour appuyer le suivi de la situation sanitaire.

Le dashboard permet notamment de :

- suivre les principaux indicateurs épidémiologiques ;
- visualiser la répartition géographique des cas ;
- comparer la contribution des différentes régions ;
- identifier les districts sanitaires touchés ;
- présenter une synthèse régionale des données.

## Indicateurs

Le tableau de bord présente notamment :

- le nombre de cas confirmés ;
- le nombre de décès ;
- la létalité ;
- l'étendue géographique de l'épidémie ;
- la part des cas confirmés par région ;
- les cas confirmés par district sanitaire.

## Cartographie

Deux approches cartographiques sont utilisées :

**Carte régionale**  
Représentation choroplèthe de la part (%) des cas confirmés par région.

**Carte des districts sanitaires**  
Représentation des nombres absolus de cas par symboles proportionnels.

Cette distinction permet d'adapter la représentation cartographique à la nature de l'indicateur.

## Technologies utilisées

- R
- Quarto Dashboard
- tidyverse
- sf
- Leaflet
- gt

## Structure du projet

```text
Dashboard_Diphterie/
├── dashboard.qmd
├── README.md
├── .gitignore
├── Data/
│   ├── diphterie_senegal_08_septembre_2026.csv
│   └── Spatial/
│       ├── regions_sn.geojson
│       └── districts_sanitaires_sn.geojson
├── Script/
├── Output/
└── images/
```

## Réutilisation

Le projet est progressivement conçu comme un **template réutilisable de dashboard de surveillance épidémiologique**.

L'objectif est de permettre son adaptation à d'autres maladies, périodes et jeux de données tout en conservant une architecture commune pour :

- les indicateurs ;
- la cartographie ;
- les tableaux de synthèse ;
- les métadonnées.

## Auteur

**Seydina Issa Laye Fall**  
Géographe de la santé | SIG | Gestion et qualité des données | Suivi-Évaluation