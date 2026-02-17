# Kannada MNIST - Classification de chiffres manuscrits

Ce projet consiste à développer un modèle de Machine Learning capable de classifier des chiffres manuscrits (0 à 9) issus du dataset Kannada MNIST. L’objectif est de mettre en place une pipeline complète allant de l’analyse exploratoire des données jusqu’à l’optimisation des modèles de classification.

## Objectifs du projet

- Explorer et comprendre la structure des données
- Prétraiter les données (normalisation, mise à l’échelle)
- Réduire la dimension avec PCA
- Implémenter plusieurs modèles de classification
- Optimiser les hyperparamètres
- Comparer les performances des modèles

## Méthodologie

### Analyse exploratoire (EDA)
- Visualisation des distributions
- Vérification des classes
- Analyse des corrélations

### Prétraitement
- Standardisation des variables
- Réduction de dimension via PCA
- Séparation train / validation

### Modélisation
Les modèles testés :

- Support Vector Machine (SVM)
- Random Forest

Optimisation via RandomizedSearchCV.


## Évaluation des performances

- Accuracy
- Comparaison des scores validation
- Sélection du meilleur modèle
  
## Technologies utilisées

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Données 
Le projet nécessite :

- train.csv
- test.csv

Les fichiers ne sont pas inclus dans ce repository.

Télécharger le dataset depuis Kaggle et placer les fichiers dans le dossier `data/`.


