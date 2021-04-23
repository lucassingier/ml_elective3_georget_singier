# TP Project - Ynov ML Elecctive 3

## Get started
* Créer son environnement conda
* A la racine du projet, run `conda install --file requirements.txt`


## Notebooks & Predictions

Le notebook est situé dans le dossier notebooks (Consignes.ipynb)

**Le pipeline utilisé pour générer nos prédictions** : 
* Remplacement des valeurs manquantes via KNN Imputer
* Suppression des lignes contenant des outliers
* Normalisation : StandardScaling
* Feature selection : Régularisation L1 via LinearSVC
* Modèle utilisé : SVC

Le fichier de prediction est dans le dossier notebooks (td-ml-elective3.csv)
