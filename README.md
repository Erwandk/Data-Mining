# Data-Mining
Projet étudiant de data mining

Nous avons ici chercher à analyser les données des donateurs d'une ONG qui lutte contre les inégalités.
Les données (confidentielles) mises à disposition étaient les informations de tous les types de donateurs de l'ONG. Nous avions également l'historique de tout leurs dons sur les 5 dernières années avec différentes caractéristiques.

## Introduction
Il y a trois types de donateurs: réguliers, évènementiels et occasionnels.
Nous discernons un dernier type de "donateurs" dans la base de donnée quis ont uniquement ceux qui ont signer une petition.

## Analyse de données
Cette partie a pour but d'analyser les données des donateurs réguliers (en terme de donations) ainsi que d'analyser le churn de ces donateurs et ce qui différencie les deux catégories (ceux qui churnent et ceux qui ne churnent pas) selon les différentes caractéristiques clées.


## Feature Engineering 1

Ce script a pour but de charger, de traiter et de sauvegarder les données brutes que nous avons à disposition.
On extrait ici les donateurs réguliers : qui sont les donateurs sur lesquels nous allons faire nos analyses.

## Feature Engineering 2

Ce script a pour but de traiter les données, créer des features en vue de l'élaboration d'un algorithme de détection de churn au sein des clients.
