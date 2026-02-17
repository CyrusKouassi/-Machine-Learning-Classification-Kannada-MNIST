# Kannada MNIST — Classification de chiffres manuscrits

## Objectif

Ce projet vise à développer et comparer des modèles de Machine Learning pour la classification de chiffres manuscrits (0 à 9) issus du dataset Kannada MNIST.

L’objectif est de construire une démarche rigoureuse allant de l’exploration des données jusqu’à l’optimisation des modèles, afin d’identifier l’approche offrant le meilleur compromis entre performance et complexité.

---

## Jeu de données

Le dataset Kannada MNIST constitue une alternative au MNIST classique. Chaque observation correspond à une image convertie en vecteur de pixels, permettant une approche par apprentissage supervisé.

Les fichiers utilisés sont :

- `train.csv` : données d’entraînement avec variable cible  
- `test.csv` : données de test  

Compte tenu du volume des fichiers, les données ne sont pas incluses dans ce dépôt.  
Le dataset est disponible sur Kaggle :  https://www.kaggle.com/c/Kannada-MNIST/data
---

## Démarche méthodologique

Une analyse exploratoire initiale permet de comprendre la structure des données et la distribution des classes.  

Une phase de prétraitement est ensuite réalisée afin de préparer les variables pour l’apprentissage. Une réduction de dimension par Analyse en Composantes Principales (PCA) est appliquée afin de compresser l’information et d’étudier l’impact de la dimensionnalité sur la performance des modèles.

Deux approches de classification supervisée sont comparées : un Support Vector Machine et un Random Forest. Les hyperparamètres sont optimisés par validation croisée (GridSearchCV) afin d’obtenir une estimation robuste des performances.

L’évaluation repose sur la comparaison des performances prédictives et sur l’analyse du compromis biais–variance.

---

## Compétences mobilisées

Ce projet met en œuvre :

- Structuration d’une pipeline complète de Machine Learning  
- Réduction de dimension et analyse de variance expliquée  
- Comparaison méthodique de modèles supervisés  
- Optimisation d’hyperparamètres par validation croisée  
- Analyse critique des performances  

---

## Reproductibilité

L’ensemble des étapes de traitement, de modélisation et d’évaluation est contenu dans le notebook `Kannada MNIST.ipynb`.

Pour reproduire les résultats :

1. Télécharger le dataset depuis Kaggle.
2. Placer les fichiers `train.csv` et `test.csv` dans le même répertoire que le notebook.
3. Ouvrir le notebook dans un environnement Python (Jupyter Notebook, JupyterLab ou équivalent).
4. Exécuter les cellules séquentiellement.

Le projet repose sur les bibliothèques standards de Python (NumPy, Pandas, Matplotlib, Scikit-learn).


---

## Remarque

Ce projet académique a été réalisé dans le cadre d’un Master en Mathématiques Appliquées et Statistiques.

Le dépôt met en évidence ma capacité à formaliser une problématique, à mettre en œuvre une pipeline de modélisation rigoureuse et à analyser de manière critique les résultats obtenus. Il témoigne de compétences en statistique appliquée, en apprentissage supervisé et en programmation scientifique.

