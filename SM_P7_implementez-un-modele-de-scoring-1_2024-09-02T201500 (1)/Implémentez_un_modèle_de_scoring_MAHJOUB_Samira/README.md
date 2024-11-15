# Implémentez un modèle de scoring

## Description du Projet
- Ce projet vise à développer un modèle de scoring pour évaluer la probabilité de remboursement d'un crédit pour une société financière, "Prêt à dépenser".
- L'objectif est de classifier les demandes de crédit en fonction du risque de défaut, permettant ainsi à l'entreprise de prendre des décisions éclairées.

## Objectifs
1. **Modélisation supervisée** :
   - Construire un modèle de scoring pour prédire la probabilité de défaut.
   - Analyser les features les plus importantes pour la prédiction, globalement et au niveau individuel, pour une meilleure interprétabilité.
2. **Déploiement MLOps** :
   - Suivre le cycle de vie du modèle en utilisant des outils MLOps, notamment MLFlow pour le tracking et la gestion des modèles.
   - Déployer le modèle sous forme d'API avec des outils comme FastAPI ou Flask, et l'exposer via une interface de test (Streamlit ou autre).
3. **Surveillance et maintenance** :
   - Détecter le data drift en production à l’aide d’evidently pour surveiller et maintenir la performance du modèle dans le temps.

## Contenu du Projet
- **Données** : Utilisation de données provenant de différentes sources (comportementales, institutionnelles, etc.).
- **Prétraitement des données** :
  - Gestion des variables catégorielles et numériques.
  - Traitement du déséquilibre de classes à l’aide de techniques comme SMOTE.
  - Création de nouvelles variables et transformations mathématiques pour améliorer la distribution.
- **Modélisation** :
  - Essai de plusieurs algorithmes de classification (régression logistique, modèles basés sur les arbres, etc.).
  - Optimisation des hyperparamètres et évaluation des modèles via des techniques de validation croisée.
  - Mesure de la performance avec des métriques adaptées (AUC, score métier tenant compte des faux positifs/négatifs).
- **Déploiement** :
  - Développement d'une API pour l'inférence.
  - Utilisation de Git et GitHub pour la gestion de version, avec intégration continue via GitHub Actions.

## Livrables
- **Modèle de scoring** : Notebook ou script Python détaillant l'ensemble du pipeline de modélisation.
- **API déployée** : Lien vers l'API de scoring.
- **Tableau HTML de détection de data drift** : Analyse générée avec evidently pour suivre la performance du modèle en production.
- **Interface de test** : Application Streamlit ou équivalent pour tester les prédictions de l'API.
- **Support de présentation** : Diaporama détaillant les étapes, résultats et choix méthodologiques.

## Évaluation et Résultats
- **Modélisation réussie** avec des scores métiers performants, basés sur l’optimisation du seuil de classification.
- **Cycle de vie du modèle suivi et maintenu** à l’aide d’outils MLOps pour la traçabilité des expérimentations et la gestion des modèles.
- **Détection proactive du data drift** pour assurer la pertinence des prédictions dans le temps.

## Remarques 
- **Points forts** : Structure claire du code et des expérimentations ; application des meilleures pratiques en MLOps.
  
## Ressources Utilisées
- **Bibliothèques** : scikit-learn, MLFlow, FastAPI/Flask, Streamlit, evidently.
- **Plateforme Cloud** : Heroku ou AWS pour le déploiement de l'API.
