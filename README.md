# Sell4All - Analyse exploratoire des données

## Présentation

Ce projet consiste à réaliser une première exploration des données clients de Sell4All afin de préparer leur utilisation dans un futur projet d'intelligence artificielle.

## Étapes réalisées

- Lecture du fichier CSV avec Pandas.
- Exploration et analyse des données.
- Calcul de la moyenne et de la médiane de l'âge et des dépenses.
- Calcul de la médiane de l'âge par pays.
- Création d'un graphique des dépenses par pays.
- Nettoyage des données (suppression des dépenses < 10 € et des doublons).
- Export des données nettoyées dans un nouveau fichier CSV.

## Technologies utilisées

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Difficultés rencontrées

- Utilisation de `groupby()` pour regrouper les données.
- Filtrage des lignes avec Pandas.
- Création du graphique à barres.

## Lancer le projet

1. Installer les dépendances :

```bash
pip install pandas matplotlib notebook
```

2. Lancer Jupyter Notebook :

```bash
jupyter notebook
```

3. Ouvrir et exécuter le notebook `Sell4All.ipynb`.

## Résultat

Le projet génère un fichier "resultat.csv" contenant les données nettoyées avec les colonnes :
- Country
- Age
- Gender
- Customer spendings
