# Modèle d'Analyse des Publications Scientifiques avec l'API Scopus

Un modèle d'analyse des publications scientifiques utilisant l'**API Scopus**, avec des outils puissants comme **NumPy**, **Pandas**, **Matplotlib**, **RDF**, et **SPARQL** pour le traitement des données et la visualisation.

## Description

Ce projet propose un modèle permettant d'analyser les publications scientifiques à partir des données récupérées via l'**API Scopus**. Le modèle exploite des bibliothèques comme **NumPy** et **Pandas** pour le traitement des données, **Matplotlib** pour la visualisation des résultats, et **RDF** et **SPARQL** pour interroger et manipuler les données au format RDF. Le projet vise à fournir des informations sur les publications, les auteurs, les institutions, ainsi que d'autres statistiques pertinentes.

### Fonctionnalités principales :
- Extraction des publications scientifiques à partir de l'API Scopus.
- Traitement des données à l'aide de **Pandas** et **NumPy**.
- Visualisation des tendances des publications, des auteurs, et des citations avec **Matplotlib**.
- Utilisation de **RDF** et **SPARQL** pour interroger et analyser les données de publication.
- Création de rapports détaillés sur les tendances de publication et l'impact des chercheurs.

## Technologies utilisées

- **NumPy** : Bibliothèque Python pour le calcul scientifique et le traitement des données numériques.
- **Pandas** : Bibliothèque Python pour la manipulation et l'analyse des données.
- **Matplotlib** : Bibliothèque Python pour la création de graphiques et la visualisation des données.
- **RDF** : Format de données pour représenter les informations sous forme de triplets (sujet, prédicat, objet).
- **SPARQL** : Langage de requête pour interroger des bases de données RDF, utilisé pour interroger les publications et extraire des informations spécifiques.
- **API Scopus** : API permettant d'accéder aux publications scientifiques et de récupérer des métadonnées à partir de la base de données Scopus.

## Installation

### Prérequis

- Python 3.6 ou supérieur.
- Un compte Scopus avec une clé API.
- Les bibliothèques Python suivantes doivent être installées : 
  - NumPy
  - Pandas
  - Matplotlib
  - rdflib
  - requests

Vous pouvez installer les dépendances requises avec pip :
```bash
pip install numpy pandas matplotlib rdflib requests
