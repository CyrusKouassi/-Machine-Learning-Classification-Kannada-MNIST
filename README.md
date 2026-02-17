# Kannada MNIST — Classification de chiffres manuscrits

## Objectif

Ce projet vise à développer un modèle de Machine Learning capable de classifier des chiffres manuscrits (0 à 9) issus du dataset Kannada MNIST. Il s’inscrit dans une démarche complète de modélisation incluant l’exploration des données, le prétraitement, la réduction de dimension et l’optimisation de modèles supervisés.

L’objectif principal est de comparer différentes approches de classification afin d’identifier le modèle le plus performant et le plus robuste.

## Jeu de données

Le dataset Kannada MNIST est une alternative au MNIST classique et contient des images de chiffres manuscrits converties en vecteurs de pixels.

- Fichier `train.csv` : données d’entraînement avec labels  
- Fichier `test.csv` : données de test  
- Chaque ligne correspond à une image représentée par ses intensités de pixels  

Les fichiers de données ne sont pas inclus dans ce dépôt et doivent être placés dans le dossier `data/`.

## Méthodologie

Le projet suit une pipeline structurée de Machine Learning comprenant :

- Analyse exploratoire des données afin de comprendre la distribution des classes  
- Prétraitement et normalisation des variables  
- Réduction de dimension via Analyse en Composantes Principales (PCA)  
- Implémentation de modèles supervisés  
- Optimisation des hyperparamètres avec GridSearchCV  
- Évaluation comparative des performances  

Les modèles étudiés sont :

- Support Vector Machine (SVM)  
- Random Forest  

## Résultats

Les performances des modèles sont évaluées principalement à l’aide de l’accuracy. Une comparaison est effectuée afin d’analyser l’impact de la réduction de dimension sur la précision et le temps d’entraînement.

Le modèle final retenu correspond à celui offrant le meilleur compromis entre performance prédictive et stabilité.

## Technologies

Le projet a été réalisé en utilisant :

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## Organisation du dépôt

Le dépôt contient :

- `Kannada MNIST.ipynb` : notebook principal  
- `requirements.txt` : dépendances du projet  
- `.gitignore`  
- Dossier `data/` destiné à contenir les fichiers CSV  

## Exécution

- Installer les dépendances avec `pip install -r requirements.txt`  
- Placer les fichiers `train.csv` et `test.csv` dans le dossier `data/`  
- Ouvrir et exécuter le notebook `Kannada MNIST.ipynb`  

## Remarques

Ce projet illustre la mise en place d’une pipeline complète de Machine Learning et la comparaison de modèles supervisés dans un cadre académique.
