## Prédiction de la Production d'Énergie Solaire

Ce projet a été réalisé en autodidacte dans le cadre de mon apprentissage de la data science. Il s'agit d'un projet visant à prédire la production d'énergie solaire d'une centrale en utilisant un jeu de données issu de Kaggle.

## Objectifs du Projet

L'objectif principal de ce projet est de prédire la production d'énergie solaire à partir de différents capteurs installés dans un centrale solaire.
Ces prédictions pourraient aider à optimiser la gestion des centrales et mieux comprendre l'impact des paramètres environnementaux.

## Jeu de Données

Le jeu de données contient des informations collectées pendant 34 jours dans deux centrales solaires en Inde. Il inclut :
La production d'énergie au niveau des onduleurs.
Les relevés des capteurs (température, rayonnement solaire, etc.).

## Méthodologie

### Analyse Exploratoire des Données (EDA) :

#### Nettoyage des données.

Analyse des tendances et des corrélations entre les variables.
Visualisation des données à l'aide de graphiques comme les heatmaps pour étudier les corrélations.

#### Préparation des Données :

Division des données en ensembles d'entraînement et de test.
Normalisation des variables lorsque nécessaire.

#### Modélisation :

Utilisation de la régression linéaire pour prédire la production d'énergie solaire.
Évaluation de la performance à l'aide de métriques comme le R² et l'Erreur quadratique moyenne (MSE)

#### Résultats:

Le modèle construit fournit des prédictions qui montrent une corrélation raisonnable avec les valeurs réelles. 
Les visualisations aident à comprendre les facteurs les plus influents sur la production d'énergie.

#### Limites:

Jeu de données limité à 34 jours, ce qui peut affecter la généralisation des résultats.
Modèle simple basé sur la régression linéaire : d'autres modèles avancés pourraient être explorés.
