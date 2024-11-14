# Analysez des données de systèmes éducatifs

## Description du Projet
- Ce projet fait partie du parcours de formation Data Scientist d'OpenClassrooms.
- Il vise à analyser les données de systèmes éducatifs de différents pays pour aider la start-up EdTech "Academy" dans sa stratégie d'expansion internationale.
- Le but est de déterminer les marchés potentiels pour des services éducatifs en ligne.

## Objectifs
- **Validation de la qualité des données** : Vérifier la présence de données manquantes ou dupliquées.
- **Description du jeu de données** : Analyser les colonnes, lignes et types d'informations.
- **Sélection des données pertinentes** : Identifier les indicateurs clés pour l'expansion internationale.
- **Analyse statistique** : Utiliser des mesures statistiques comme la moyenne, la médiane, et l'écart-type pour évaluer les tendances par pays.

## Contenu du Projet
- **Fichiers de données utilisés** :
  - `EdStatsData.csv` : Valeurs des indicateurs pour tous les pays et plusieurs années.
  - `EdStatsSeries.csv` : Informations socio-économiques par thème.
  - `EdStatsCountry.csv` : Informations économiques globales par pays.
  - `EdStatsFootNote.csv` : Notes explicatives sur les indicateurs.
  - `EdStatsCountry-Series.csv` : Source des indicateurs par pays.

## Exploration Préliminaire des Données
1. **Pré-sélection des données** : Identifier les informations cruciales pour l'analyse.
2. **Analyse de la qualité des données** : Vérifier l'intégrité des données (87,9% de taux de remplissage).
3. **Sélection des indicateurs** : Choix des mesures significatives pour l'éducation en ligne.
4. **Calcul des scores d'attractivité** : Évaluer le potentiel des marchés cibles.

## Indicateurs Clés
- **Utilisateurs d'Internet** (`IT.NET.USER.P2`) : Mesure de la connectivité Internet.
- **PIB par habitant** (`NY.GDP.PCAP.CD`) : Indicateur économique pour évaluer la capacité de dépenses.
- **Population étudiante** (`UIS.E.3` et `SE.TER.ENRL`) : Taille de la population étudiante dans le secondaire et le tertiaire.

## Résultats et Synthèse
- Les pays avec un fort potentiel pour l'expansion sont ceux avec une bonne connectivité Internet et un PIB par habitant élevé.
- La population étudiante en expansion dans certains pays (ex. : Inde, Chine, États-Unis) indique un marché favorable pour les services d'éducation en ligne.

## Conclusion et Perspectives
- **Potentiel des marchés ciblés** : Les analyses montrent des opportunités dans les pays à haut revenu et forte connectivité.
- **Priorités d'expansion** : Les pays avec les scores les plus élevés sont à prioriser.
- **Perspectives** : Envisager des données supplémentaires et une analyse plus fine pour mieux cibler les marchés.

## Ressources Utilisées
- Données de la Banque mondiale.
- Cours et outils de data science d'OpenClassrooms.

## Remarques
- **Points forts** : Analyse détaillée des indicateurs et propositions stratégiques.
