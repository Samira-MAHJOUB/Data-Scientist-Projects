# Préparez des données pour un organisme de santé publique

## Description du Projet
- Ce projet consiste à préparer et nettoyer les données de la base de données **Open Food Facts** pour un organisme de santé publique.
- L'objectif est d'améliorer la qualité des données nutritionnelles pour faciliter leur analyse et leur utilisation dans des études de santé publique.

## Objectifs
- **Nettoyer les données** : Identifier et traiter les valeurs manquantes, les valeurs aberrantes et les doublons.
- **Améliorer la qualité des données** : Sélectionner les variables pertinentes pour les analyses nutritionnelles et préparer les données pour l'auto-complétion.
- **Explorer les données** : Analyser la distribution des données et les corrélations entre les variables nutritionnelles.

## Contenu du Projet
- **Fichiers de données** : Base de données Open Food Facts en format CSV, comprenant environ 320,772 lignes et 162 colonnes avec des informations sur les produits alimentaires.
- **Analyse des données** :
  - Nettoyage des données (suppression des colonnes inutiles, traitement des valeurs manquantes et aberrantes).
  - Sélection des variables clés : nom du produit, marque, énergie, glucides, protéines, lipides, fibres pour 100g, etc.
  - Analyse univariée, bivariée, et multivariée (ACP et ANOVA).

## Méthodologie
1. **Nettoyage des données** : Suppression des colonnes vides, transformation des données de type date, et traitement des valeurs manquantes.
2. **Imputation des valeurs manquantes** :
   - Moyenne pour les variables continues symétriques.
   - Médiane pour les variables continues asymétriques.
   - Mode pour les variables catégorielles.
3. **Exploration statistique** : Utilisation d'analyses univariée, bivariée, et multivariée pour mieux comprendre les relations entre les variables.
4. **ACP et ANOVA** : Analyse en Composantes Principales pour réduire la dimensionnalité des données et Analyse de la Variance pour évaluer les différences statistiques.

## Résultats et Synthèse
- **Intégrité des données** : Après nettoyage, un taux de remplissage de 76,22% a été atteint, indiquant une bonne qualité de la base.
- **Potentiel pour un système d'auto-complétion** : Les analyses montrent qu'un système de suggestion de valeurs pourrait améliorer la complétude des données.
- **Analyse des corrélations** : Des corrélations significatives ont été observées entre certaines variables nutritionnelles, notamment entre énergie et graisses.

## Conclusion et Perspectives
- **Améliorations potentielles** : Développement d'un système de suggestion automatique pour aider à compléter les valeurs manquantes.
- **Ouverture** : Intégration d'outils de visualisation pour les utilisateurs finaux et exploration de partenariats pour enrichir la base de données.

## Ressources Utilisées
- **Base de données Open Food Facts** : Données sur les produits alimentaires.
- **Bibliothèques Python** : Utilisation de pandas, numpy, matplotlib, et scikit-learn pour l'analyse et le nettoyage des données.

## Remarques
- **Points forts** : Méthodologie de nettoyage rigoureuse et analyse statistique approfondie.
