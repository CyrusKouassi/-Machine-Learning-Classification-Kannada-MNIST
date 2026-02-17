# Kannada MNIST — Classification de chiffres manuscrits

## Objectif

Ce projet a pour objectif de développer un modèle de Machine Learning capable de classifier des chiffres manuscrits (0 à 9) issus du dataset Kannada MNIST. Il s’inscrit dans une démarche complète de modélisation incluant l’exploration des données, le prétraitement, la réduction de dimension, l’entraînement de modèles supervisés ainsi que l’optimisation des hyperparamètres.

L’ambition du projet est de comparer différentes approches de classification et d’évaluer leur performance afin d’identifier le modèle le plus robuste et le plus performant.

## Jeu de données

Le dataset Kannada MNIST est une alternative au MNIST classique et contient des représentations numériques d’images de chiffres manuscrits. Les données sont fournies sous forme de fichiers `train.csv` et `test.csv`, dans lesquels chaque ligne correspond à une image transformée en vecteur de pixels.

Les fichiers de données ne sont pas inclus dans ce dépôt. Ils doivent être placés dans le dossier `data/` avant l’exécution du notebook.

## Méthodologie

La première étape du projet consiste en une analyse exploratoire des données afin de comprendre leur structure et la distribution des classes. Un travail de prétraitement est ensuite réalisé pour normaliser et préparer les variables en vue de l’apprentissage.

Une réduction de dimension par Analyse en Composantes Principales (PCA) est appliquée afin de compresser l’information, réduire le bruit et améliorer l’efficacité computationnelle des modèles.

Deux modèles de classification supervisée sont ensuite implémentés : un Support Vector Machine (SVM) et un Random Forest. Une procédure d’optimisation des hyperparamètres via GridSearchCV est utilisée afin d’améliorer les performances et de sélectionner la meilleure configuration.

Les performances sont évaluées principalement à l’aide de la métrique d’accuracy et d’une comparaison entre les modèles testés.

## Résultats

Les modèles SVM et Random Forest sont comparés sur la base de leurs performances en validation. L’impact de la réduction de dimension sur la précision et le temps d’entraînement est analysé. Le modèle final retenu correspond à celui présentant le meilleur compromis entre performance prédictive et stabilité.

## Technologies

Ce projet a été réalisé en Python en utilisant les bibliothèques NumPy, Pandas, Matplotlib, Seaborn et Scikit-learn.

## Organisation du dépôt

Le dépôt contient le notebook principal `Kannada MNIST.ipynb`, un fichier `requirements.txt` listant les dépendances nécessaires, un fichier `.gitignore` ainsi qu’un dossier `data/` destiné à contenir les fichiers de données.

## Exécution

Après installation des dépendances via `pip install -r requirements.txt`, les fichiers `train.csv` et `test.csv` doivent être placés dans le dossier `data/`. Le projet peut ensuite être exécuté en ouvrant le notebook `Kannada MNIST.ipynb` et en lançant les cellules séquentiellement.

## Remarques

Ce projet met en œuvre une pipeline complète de Machine Learning et illustre la structuration d’un workflow reproductible allant de l’analyse des données à l’optimisation de modèles supervisés.

