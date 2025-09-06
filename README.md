# Projet Data Visualisation

Bienvenue sur le projet **Data Visualisation** !  
Ce dépôt présente une série d’études et de visualisations réalisées à partir de jeux de données immobilières françaises, dans le but de valoriser l’analyse et l’exploitation de la data pour des problématiques concrètes.

## Table des matières

- [Objectifs du projet](#objectifs-du-projet)
- [Structure du dépôt](#structure-du-dépôt)
- [Cas d'étude](#cas-détude)
- [Fichiers de données](#fichiers-de-données)
- [Prérequis & Installation](#prérequis--installation)
- [Utilisation](#utilisation)
- [Auteurs](#auteurs)

---

## Objectifs du projet

Ce projet vise à :
- Explorer et visualiser des données immobilières publiques (base DVF de la DGFiP)
- Proposer des analyses de marché, des cartographies et des tableaux de bord interactifs
- Illustrer les étapes de la préparation des données, de l’analyse exploratoire et de la présentation visuelle

## Structure du dépôt

```
├── Case_1.ipynb           # Étude de cas 1 : analyse exploratoire, visualisations
├── Case_1.pdf             # Rapport PDF du cas 1
├── Case_2.ipynb           # Étude de cas 2 : analyses complémentaires
├── Case_2.pdf             # Rapport PDF du cas 2
├── Case_3.ipynb           # Étude de cas 3 : cartographie, analyses avancées
├── Case_3.pdf             # Rapport PDF du cas 3
├── preprocessing.ipynb    # Nettoyage et préparation des données
├── interactive_notebook.ipynb # Tableau de bord interactif
├── README.ipynb           # Présentation interactive du projet
├── data.csv               # Jeu de données analysé
├── notice-descriptive-du-fichier-dvf-20221017.pdf # Documentation officielle DVF
├── regions.shp/.dbf/.shx  # Fichiers de géolocalisation pour cartographie
```

## Cas d’étude

Le projet se compose de trois études de cas principales :
- **Case 1** : Analyse exploratoire des transactions immobilières
- **Case 2** : Visualisation des tendances de marché et comparaison inter-régions
- **Case 3** : Cartographie et visualisation spatiale des prix immobiliers

Chaque cas comprend un notebook Jupyter détaillant le processus, et un rapport PDF synthétisant les résultats.

## Fichiers de données

- **data.csv** : Jeu de données principal issu du fichier DVF (Données de Valeurs Foncières)
- **notice-descriptive-du-fichier-dvf-20221017.pdf** : Documentation sur la structure des données
- **regions.shp / .dbf / .shx** : Données géographiques pour la cartographie des régions

## Prérequis & Installation

Ce projet utilise **Python 3.x** et les bibliothèques de data science et visualisation :  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `geopandas`, `folium`...

Pour installer les dépendances :

```bash
pip install pandas numpy matplotlib seaborn plotly geopandas folium
```

Les notebooks peuvent être ouverts et exécutés avec **Jupyter Notebook** ou **Jupyter Lab**.

## Utilisation

1. **Prétraitement** : Exécutez `preprocessing.ipynb` pour charger et nettoyer les données.
2. **Exploration** : Parcourez les notebooks `Case_1.ipynb`, `Case_2.ipynb`, `Case_3.ipynb` pour découvrir les analyses et visualisations.
3. **Cartographie** : Visualisez les prix et transactions sur la carte via les modules `geopandas` et `folium`.
4. **Tableau de bord** : Lancez `interactive_notebook.ipynb` pour une exploration interactive.
