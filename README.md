# Data-Mining
Ce projet a pour but d'aider une ONG à maximiser ses dons. L'approche que nous avons choisie ici consiste à détecter la probabilité qu'un client s'en aille.
Cela permet de mieux le cibler et le faire rester afin qu'il continue de donner à l'ONG.

### Structure

Ce projet se décompose de la manière suivante : à l'intérieur du dossier *code_projet* se trouve tout le code utilisé dans ce projet. A l'interieur du dossier data se trouve les données du projet.
Vous pouvez installer les librairies utiles à ce projet en utilisant le fichier _requirements.txt_.  
Pour des raisons confidentielles, les données de ce projet ne sont pas publiques.
- _Feat Eng 1_ : ce script correspond au traitement des données brutes reçues en amont du projet. Il vise à les nettoyer et les agréger afin de travailler sur des datasets propres.
- _Analyse_ : ce script a pour but de tirer quelques conclusions des données et de valider notre approche de détecter le churn des clients.
- _Feat Eng 2_ : ce script a pour but de créer un dataset de train/test en vue de l'élaboration d'un modèle prédictif en nous basant sur les datasets propres crées par le premier script de feature engineering.
- _Modèles_ : ce script contient l'élaboration du modèle, son entrainement ainsi que son évaluation.

