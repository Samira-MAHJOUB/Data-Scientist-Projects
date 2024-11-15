# Réalisez un traitement dans un environnement Big Data sur le Cloud

## Description du Projet
- Ce projet a pour objectif de concevoir une chaîne de traitement Big Data capable de gérer des volumes massifs de données dans un environnement cloud.
- Vous travaillez pour une start-up AgriTech, "Fruits!", qui souhaite développer une application mobile de reconnaissance d'images de fruits et mettre en place une architecture Big Data évolutive.

## Objectifs
1. **Configurer un environnement Big Data sur le cloud** :
   - Utilisation d'AWS EMR, S3 et IAM pour créer une architecture distribuée.
   - Gestion des normes RGPD en paramétrant les serveurs en Europe.
2. **Développer une chaîne de traitement PySpark** :
   - Traitement des données avec des scripts distribués.
   - Réduction de dimensions avec PCA.
   - Diffusion des poids d'un modèle TensorFlow pour l'inférence.
3. **Optimiser les coûts** :
   - Limiter l’utilisation des instances EMR pour réduire les frais.

## Étapes Clés
1. **Préparation en local** :
   - Étudier le notebook existant fourni par un alternant.
   - Compléter et adapter les scripts pour inclure la PCA et la diffusion des poids TensorFlow.
2. **Migration vers le cloud** :
   - Déployer la chaîne de traitement sur AWS EMR.
   - Stocker les données et résultats dans des buckets S3.
3. **Présentation des résultats** :
   - Préparer un support expliquant l’architecture, les choix techniques et les résultats.

## Livrables
- **Notebook PySpark** : Scripts pour le traitement des données et la réduction de dimensions.
- **Données** : Images et sorties des traitements stockées sur le cloud.
- **Support de présentation** : Diaporama détaillant l'architecture, les choix techniques, et les étapes de la chaîne de traitement.

## Résultats
- **Architecture cloud fonctionnelle** :
  - Mise en place réussie d’un cluster EMR avec une chaîne de traitement opérationnelle.
  - Stockage des résultats dans un bucket S3 conforme aux normes RGPD.
- **Scripts PySpark optimisés** :
  - Intégration de la PCA et diffusion des poids TensorFlow.
  - Traitements distribués testés avec succès sur des jeux de données volumineux.

## Remarques
### Points forts
- Respect des normes RGPD dans la mise en œuvre des services cloud.
- Documentation claire des scripts et choix techniques.
- Démonstration fluide de la chaîne de traitement.
  
## Technologies Utilisées
- **Cloud** : AWS EMR, S3, IAM.
- **Big Data** : PySpark, Hadoop.
- **Machine Learning** : TensorFlow pour la diffusion des poids des modèles.
