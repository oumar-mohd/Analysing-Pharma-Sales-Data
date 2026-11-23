# Analyse des ventes pharmaceutiques avec Python

Petit projet d'EDA pour pratiquer Pandas et Matplotlib sur des données réelles de ventes de médicaments.

## Outils

Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

## Les données

Dataset téléchargé sur Kaggle : [Pharma Sales Data](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data). Six ans de ventes quotidiennes (2014-2019), réparties en 8 catégories ATC.

## Ce que j'ai fait

- Exploration et nettoyage des données.
- Ventes totales par catégorie ATC et comparaison entre périodes.
- Recherche de la catégorie avec la meilleure moyenne quotidienne.
- Analyse mensuelle de la catégorie R03 (médicaments respiratoires).

## Résultats clés

- **N02BE** a le plus grand volume de ventes et la meilleure moyenne quotidienne (environ 29,92).
- **R03** : décembre est le meilleur mois en moyenne, juillet le plus faible.

## Lancer le projet

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook

**Ouvrez** pharmaceutical_sales_analysis.ipynb pour suivre l'analyse étape par étape.
Auteur
Oumar Mohamed Diarrasouba, étudiant en informatique, passionné par la Data Analysis et la Data Science.

