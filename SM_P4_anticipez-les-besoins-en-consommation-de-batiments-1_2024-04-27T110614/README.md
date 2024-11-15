# Anticipez les besoins en consommation de bâtiments

## Description du Projet
- Ce projet vise à développer un modèle prédictif pour estimer la consommation d'énergie et les émissions de CO2 des bâtiments non résidentiels de Seattle. 
- Ce modèle contribue aux objectifs de durabilité de la ville, notamment l'objectif de neutralité carbone d'ici 2050.

## Objectifs
- **Prédire la consommation d'énergie** des bâtiments pour soutenir la planification des ressources.
- **Estimer les émissions de CO2** afin de contribuer aux efforts de réduction d'empreinte carbone de la ville.
- **Évaluer l'importance du Score ENERGY STAR** pour la prédiction des émissions de CO2 et de la consommation énergétique.

## Contenu du Projet
- **Données** : Relevés des bâtiments de Seattle en 2016, comprenant des informations structurelles, de localisation, et énergétiques.
- **Étapes du traitement des données** :
  - Assemblage des jeux de données.
  - Nettoyage des données : suppression des doublons, gestion des valeurs manquantes et des valeurs aberrantes.
  - Analyse exploratoire : analyse univariée, bivariée, et multivariée pour sélectionner les variables pertinentes.
  - Pré-traitement : encodage, standardisation et transformation des variables.

## Modélisation
- **Modèles testés** :
  - Modèles linéaires : Régression linéaire, Ridge, Lasso, Elastic Net.
  - Modèles ensemblistes : Random Forest, Gradient Boosting, XGBoost.
  - Modèle basé sur la proximité : K-Nearest Neighbors (K-NN).
- **Sélection du modèle final** : XGBoost a été choisi pour sa performance et sa capacité à gérer les relations complexes entre les variables.
- **Métriques de performance** :
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² (Coefficient de Détermination)

## Résultats
- **Prédictions des émissions de CO2** : Le modèle XGBoost a montré de bonnes performances pour prédire les émissions de gaz à effet de serre.
- **Prédictions de la consommation d'énergie** : Les résultats du modèle montrent une précision acceptable pour les besoins énergétiques des bâtiments.
- **Impact du Score ENERGY STAR** : L'intégration du score ENERGY STAR a légèrement amélioré la précision des modèles.

## Conclusion et Perspectives
- **Améliorations futures** : Exploration de modèles avancés comme les réseaux neuronaux pour améliorer la précision des prédictions.
- **Axes de développement** : Utilisation de réseaux neuronaux pour capturer des relations non linéaires plus complexes et affiner les prévisions sur des données volumineuses.

## Ressources Utilisées
- Données de la ville de Seattle (Open Data).
- Bibliothèques Python : pandas, numpy, scikit-learn, XGBoost.

## Remarques
- **Points forts** : Utilisation efficace des modèles ensemblistes pour des prédictions précises et intégration du score ENERGY STAR.
