# Classifiez automatiquement des biens de consommation

## Description du Projet
- Ce projet vise à automatiser la classification des articles en utilisant des descriptions textuelles et des images de produits.
- Ce système permet d'optimiser l'expérience utilisateur et de faciliter la catégorisation des articles pour un marketplace e-commerce.

## Objectifs
- **Étudier la faisabilité de la classification automatique** à partir des descriptions et des images.
- **Automatiser l'attribution des catégories** pour réduire le besoin de classification manuelle par les vendeurs.

## Contenu du Projet
- **Données textuelles** : Noms et descriptions des produits.
- **Données visuelles** : Images des produits, avec une organisation en dossiers par catégorie.
- **Catégories principales** : 7 catégories principales incluant Baby Care, Beauty and Personal Care, Computers, etc.
- **Techniques de traitement des données** :
  - Prétraitement des données textuelles et visuelles.
  - Extraction de caractéristiques textuelles (Bag of Words, Word Embeddings) et visuelles (SIFT, Transfer Learning avec CNN).

## Méthodologie de Classification
1. **Prétraitement des données textuelles** :
   - Suppression des ponctuations, stopwords, stemming et lemmatisation.
   - Vectorisation avec CountVectorizer et TF-IDF.
2. **Classification textuelle** :
   - Modèles d'embedding (Word2Vec, BERT, Universal Sentence Encoder).
   - Clustering avec K-Means et évaluation des clusters avec le score ARI.
3. **Prétraitement des images** :
   - Génération de descripteurs avec SIFT et Transfer Learning avec VGG-16.
4. **Classification supervisée des images** :
   - Modèles CNN pré-entraînés (VGG16, VGG19, ResNet50) avec augmentation des données pour améliorer les performances.

## Résultats
- **Score ARI pour les différentes méthodes textuelles** :
  - CountVectorizer : ARI de 0,37
  - TF-IDF : ARI de 0,45
  - Word2Vec : ARI de 0,30
  - BERT : ARI de 0,36
  - USE : ARI de 0,42
- **Classification d'images** :
  - SIFT : ARI de 0,58
  - Transfer Learning avec VGG16 : ARI de 0,52
  - VGG19 s'est avéré le plus performant en termes de généralisation et de précision pour la classification.

## Conclusion
- La faisabilité de la classification automatique a été validée pour les textes et les images.
- Les résultats indiquent des performances satisfaisantes, notamment avec l'utilisation de VGG19 pour la classification supervisée d'images, qui est la plus adaptée pour une application e-commerce.

## Ressources Utilisées
- **Données** : Base Flipkart, incluant descriptions et images des produits.
- **Bibliothèques Python** : pandas, scikit-learn, TensorFlow pour les réseaux de neurones, et OpenCV pour l'extraction de caractéristiques visuelles.

## Remarques
- **Points forts** : Classification performante des articles en utilisant des techniques avancées de NLP et de traitement d'images.
