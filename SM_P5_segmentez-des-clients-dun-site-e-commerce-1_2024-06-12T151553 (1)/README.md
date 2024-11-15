# Segmentez des clients d'un site e-commerce

## Description du Projet
- Ce projet consiste à analyser et segmenter les clients d'Olist, un site e-commerce, pour améliorer la satisfaction client et optimiser les campagnes marketing.
- L'objectif est de fournir une segmentation basée sur les comportements et les données personnelles des clients, tout en proposant un contrat de maintenance pour assurer la pertinence de la segmentation dans le temps.

## Objectifs
- **Identifier et segmenter les différents types de clients** pour cibler efficacement les campagnes de communication.
- **Proposer un contrat de maintenance** pour la mise à jour régulière de la segmentation en fonction de l'évolution des comportements clients.

## Contenu du Projet
- **Données** : Base de données anonymisée contenant l'historique des commandes, les produits achetés, les commentaires de satisfaction et la localisation des clients (9 fichiers CSV).
- **Analyse exploratoire** :
  - Analyse univariée, bivariée, et multivariée des comportements d'achat.
  - Création et transformation des variables pertinentes pour la segmentation (Récence, Fréquence, Montant).
  - Préparation des données : nettoyage, encodage, standardisation, et transformation logarithmique.

## Méthodologie de Modélisation
- **Segmentation RFM** :
  - **K-Means** : Segmentation basée sur des groupes homogènes.
  - **DBSCAN** : Clustering basé sur la densité pour des segments de formes variées.
  - Comparaison des deux méthodes pour identifier le modèle le plus performant.
- **Évaluation des segments** :
  - Silhouette Score, Calinski-Harabasz Score, et Davies-Bouldin Score pour évaluer la qualité des clusters.
  - Choix du modèle K-Means pour la segmentation finale en raison de sa clarté et de ses résultats stables.

## Résultats
- **Segments Identifiés** :
  - **Clients Fidèles et Rentables** : Programmes de fidélité et offres personnalisées.
  - **Nouveaux Clients Satisfaits** : Offres de bienvenue et recommandations de produits.
  - **Clients à Réactiver** : Campagnes de réactivation et enquêtes de satisfaction.
  - **Acheteurs Occasionnels** : Offres saisonnières et programmes de fidélité.
  - **Clients à Fort Potentiel** : Programmes de parrainage et notifications push.
- **Recommandations** : Personnaliser les communications pour chaque segment et suivre régulièrement les segments pour ajuster les stratégies marketing.

## Contrat de Maintenance
- **Fréquence de Réentraînement** : Réentraîner le modèle tous les 6 semaines ou lorsque l'ARI (Adjusted Rand Index) descend en dessous de 0.8 pour maintenir une segmentation fiable.
- **Évaluation de la Stabilité Temporelle** : Utilisation de l'ARI pour mesurer la cohérence des clusters au fil du temps.

## Ressources Utilisées
- **Base de données Olist** : Données clients et historiques d'achat.
- **Bibliothèques Python** : pandas, numpy, scikit-learn pour le traitement des données et la modélisation.

## Remarques
- **Points forts** : Segmentation claire et performante avec recommandations marketing spécifiques pour chaque segment.
