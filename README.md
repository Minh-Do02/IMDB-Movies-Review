# IMDB-Movies-Review

# Projet de traitement de données de critiques de films

## Présentation

Ce projet a pour objectif de [Insérez ici une brève description de l'objectif principal du projet, par exemple : "analyser les sentiments exprimés dans les critiques de films sur IMDB afin de prédire la note attribuée à un film"].

## Structure du projet

Le projet est organisé de la manière suivante :

* **main.py:**
  * Point d'entrée principal du programme.
  * Charge les données, entraîne le modèle, et évalue les performances.
* **data_processing.py:**
  * Contient les fonctions pour charger, nettoyer et préparer les données (IMDB_Dataset.csv).
  * Effectue des transformations telles que la tokenisation, le vectorisation, etc.
* **model.py:**
  * Définit les architectures des modèles (par exemple, réseaux de neurones, modèles de régression).
  * Implémente les fonctions d'entraînement et d'évaluation.
* **visualization.py:**
  * Crée des visualisations pour analyser les résultats (graphiques, matrices de confusion, etc.).
* **requirements.txt:**
  * Liste les bibliothèques Python nécessaires pour exécuter le projet.
* **IMDB_Dataset.csv:**
  * Jeu de données contenant les critiques de films.

## Installation

Pour installer les dépendances nécessaires, exécutez la commande suivante dans votre terminal :

```bash
pip install -r requirements.txt
