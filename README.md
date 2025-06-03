# TwoWayChallenge

# Analyse exploratoire – Sales Dataset

Ce notebook présente une analyse exploratoire d’un jeu de données de ventes.  
L’objectif était de détecter des **patterns visuels pertinents** pouvant orienter des décisions business.

## Remarque sur le nettoyage

Aucun nettoyage avancé n’a été réalisé, car :
- Le dataset était déjà bien structuré
- Aucune valeur manquante n’a été détectée
- Les noms de colonnes étaient exploitables directement

Le travail s’est donc concentré sur l’exploration visuelle et l’interprétation.

## Visualisations réalisées

Le notebook inclut plusieurs types de graphiques :

- **Histogrammes** : pour observer la distribution des prix, des quantités, etc.
- **Boxplots** : pour analyser les écarts par région, produit ou catégorie
- **Courbes temporelles** : évolution des quantités, prix et revenus dans le temps
- **Heatmaps** : comparaison des produits ou catégories selon les régions
- **Scatter plots** : relations entre prix, quantité et revenus
- **Graphiques interactifs Plotly** : pour analyser le revenu journalier dynamiquement

Chaque visualisation a servi à détecter des comportements spécifiques dans les données.

## Principaux patterns observés

- La catégorie **Books** connaît une forte baisse après un pic initial
- Le chiffre d’affaires varie fortement selon les jours, avec des **pics très marqués**
- La région **North** domine en revenu, malgré des prix et quantités similaires ailleurs
- Certains produits performent **localement** selon la région

## Objectif

Le but de ce projet était de raisonner à travers les données, d’extraire des tendances utiles, et de proposer des pistes d’actions basées sur l’analyse visuelle.

---
