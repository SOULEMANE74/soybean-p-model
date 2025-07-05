# Soybean Yield Predictor

Ce projet propose une analyse complète et un modèle prédictif du rendement du soja à partir du jeu de données **Advanced Soybean Agricultural Dataset** (Kaggle, 2025). L’étude s’appuie sur des techniques de machine learning pour identifier les facteurs agronomiques clés et fournir des recommandations concrètes aux producteurs de soja biologique, notamment au Togo.

## Objectifs

- Analyser les variables les plus influentes sur le rendement du soja.
- Construire un modèle prédictif performant (Random Forest, Gradient Boosting, etc.).
- Proposer des recommandations applicables pour améliorer la production de soja bio.

## Dataset

Le jeu de données contient plus de 55 000 enregistrements sur différentes pratiques culturales, stress hydrique, traitements à l’acide salicylique, et mesures biologiques des plants de soja.

## Structure du projet

- **sooja predictor.ipynb** : Notebook principal contenant l’analyse exploratoire, la préparation des données, la modélisation et l’interprétation des résultats.
- **GradientBoosting_model.pkl** et **RandomForest_model.pkl** : Modèles entraînés et sauvegardés.
- **soybean clean dataset.xlsx** : Jeu de données nettoyé (non inclus dans le repo pour des raisons de licence).

## Principaux résultats

- Les variables les plus déterminantes pour le rendement sont : le poids biologique, le poids de 300 graines et le nombre de gousses.
- Les modèles de machine learning permettent de prédire efficacement le rendement à partir de mesures simples.
- Des recommandations sont formulées pour les agriculteurs togolais afin d’optimiser leur production tout en respectant les normes du bio.

## Utilisation

1. Cloner le repo et installer les dépendances nécessaires (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`, etc.).
2. Placer le fichier de données dans le dossier du projet.
3. Ouvrir et exécuter le notebook `sooja predictor.ipynb`.
