# README - Classification de la Fonte des Glaces via Infrasons et Données Climatiques

## Introduction
Le changement climatique et la fonte des glaces sont des phénomènes ayant un impact majeur sur l'environnement mondial. L'étude des signaux d'infrasons, générés par les déplacements de masses d'air, représente une approche prometteuse pour mieux comprendre et prédire ces phénomènes. Ces signaux, bien que inaudibles pour l'oreille humaine, peuvent fournir des informations précieuses sur l'intensité de la fonte des glaces.

Ce projet vise à développer un modèle de classification permettant de prédire la quantité de glace dans une région spécifique du Groenland en utilisant des enregistrements d'infrasons et des données climatiques. Le modèle repose sur des algorithmes d'apprentissage automatique afin d'évaluer la présence de glace en fonction de variables météorologiques fournies par le Centre européen pour les prévisions météorologiques à moyen terme (CEPMMT).

## Objectifs
L'objectif principal de ce projet est de concevoir un classificateur capable de :
- Analyser des données infrasonores et climatiques pour détecter des tendances de fonte des glaces.
- Distinguer les périodes de fonte faible et élevée.
- Améliorer la compréhension des processus de fonte en Arctique et contribuer à la recherche sur le changement climatique.

## Données utilisées
Les données utilisées dans ce projet proviennent des sources suivantes :
- **Enregistrements d'infrasons** : Captés par des capteurs spécialisés, ces signaux permettent de détecter les mouvements d'air liés à la fonte des glaces.
- **Données climatiques** : Issues du CEPMMT, elles incluent des variables telles que la température, la vitesse du vent, la pression atmosphérique et l'humidité.

## Méthodologie
1. **Collecte et prétraitement des données** :
   - Nettoyage des enregistrements infrasonores et des données climatiques.
   - Normalisation et mise en correspondance des différentes sources de données.
2. **Exploration et analyse des données** :
   - Visualisation des tendances de fonte des glaces en fonction des variables climatiques.
   - Extraction des caractéristiques les plus pertinentes.
3. **Développement du modèle de classification** :
   - Test de différents algorithmes d'apprentissage automatique (SVM, Random Forest, Réseaux de Neurones, etc.).
   - Évaluation des performances du modèle avec des métriques adaptées (précision, rappel, F1-score).
4. **Validation et interprétation des résultats** :
   - Analyse des performances du modèle sur un ensemble de test.
   - Identification des facteurs climatiques ayant le plus d'influence sur la fonte des glaces.

## Technologies et Outils
- **Langages** : Python
- **Bibliothèques** : NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Sources de données** : CEPMMT, capteurs d'infrasons

## Résultats attendus
- Un modèle performant capable de classifier les niveaux de fonte des glaces à partir des données infrasonores et climatiques.
- Une meilleure compréhension de la relation entre les signaux infrasonores et la fonte des glaces.
- Une contribution potentielle à la surveillance du changement climatique en Arctique.

## Contribution
Les contributions à ce projet sont les bienvenues ! Si vous souhaitez apporter des améliorations, n'hésitez pas à proposer des modifications via des pull requests.

## Contact
Pour toute question ou suggestion, vous pouvez me  contacter  à l'adresse : athoumani.ibroihmia@gmail.com .


