# Data-Mining

Projet étudiant de data mining

Nous avons ici chercher à analyser les données des donateurs d'une ONG qui lutte contre les inégalités.
Les données (confidentielles) mises à disposition sont:
- les informations de tous les types de donateurs de l'ONG
- l'historique de tout leurs dons sur les 5 dernières années avec différentes caractéristiques
- des informations quant aux mails envoyés  

Ce projet se décompose de la manière suivante : à l'intérieur du dossier *code_projet* se trouve tout le code utilisé dans ce projet. A l'interieur du dossier data se trouve les données du projet.
Vous pouvez installer les librairies utiles à ce projet en utilisant le fichier _requirements.txt_.

## Introduction
Il y a trois types de donateurs: réguliers, évènementiels et occasionnels.
Nous discernons un dernier type de "donateurs" dans la base de donnée quis ont uniquement ceux qui ont signé une petition.
L'approche que nous avons choisie ici consiste à détecter la probabilité qu'un client s'en aille.
Cela permet de mieux le cibler et le faire rester afin qu'il continue de donner à l'ONG.


## Analyse de données
Cette partie a pour but d'analyser les données des donateurs réguliers (en terme de donations) ainsi que d'analyser le churn de ces donateurs et ce qui différencie les deux catégories (ceux qui churnent et ceux qui ne churnent pas) selon les différentes caractéristiques clées.


## Feature Engineering 1

Ce script a pour but de charger, de traiter et de sauvegarder les données brutes que nous avons à disposition.
Il vise à les nettoyer et les agréger afin de travailler sur des datasets propres.
On extrait ici les donateurs réguliers : qui sont les donateurs sur lesquels nous allons faire nos analyses.

## Feature Engineering 2

Ce script a pour but de traiter les données, créer des features en vue de l'élaboration d'un algorithme de détection de churn au sein des clients.

## Modèles

Ce script a pour but de développer les modèles de prédiction de churn des donateurs réguliers de l'ONG. 
On dispose des données traitées dans le script Feat_Eng_2.
