# P4_Prevision_Energie_Batiments
## Prévision des besoins électriques de bâtiments 

![P4](https://user-images.githubusercontent.com/71134226/117352178-f69da080-aeae-11eb-8610-aa0d9ecbb659.gif)

La ville de Seattle souhaite atteindre son objectif de ville neutre en émissions de carbone en 2050, et s’intéresse de près aux émissions des bâtiments non destinés à l’habitation.

## Les données
Les données de consommation sont à télécharger à cette adresse: https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

## Problématique de la ville de Seattle
Des relevés minutieux ont été effectués en 2015 et en 2016. Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, la mission consiste à prédire les émissions de CO2 et la consommation totale d’énergie de bâtiments pour lesquels elles n’ont pas encore été mesurées.

La prédiction se basera sur les données déclaratives du permis d'exploitation commerciale (taille et usage des bâtiments, mention de travaux récents, date de construction..)

Une évaluation de l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions, qui est fastidieux à calculer, est également souhaitée.

## Objectifs

- Réaliser une courte analyse exploratoire.
- Tester différents modèles de prédiction afin de répondre au mieux à la problématique.
- Mettre en place une évaluation rigoureuse des performances de la régression, et optimiser les hyperparamètres et le choix d’algorithme de ML à l’aide d’une validation croisée.

## Erreurs à éviter :

- L’objectif est de te passer des relevés de consommation annuels (attention à la fuite de données), mais rien n'interdit d’en déduire des variables plus simples (nature et proportions des sources d’énergie utilisées). 

- Attention au traitement des différentes variables, à la fois pour trouver de nouvelles informations (peut-on déduire des choses intéressantes d’une simple adresse ?) et optimiser les performances en appliquant des transformations simples aux variables (normalisation, passage au log, etc.).

![P4_2](https://user-images.githubusercontent.com/71134226/117352194-fc938180-aeae-11eb-8d36-3a2d1015d552.gif)
