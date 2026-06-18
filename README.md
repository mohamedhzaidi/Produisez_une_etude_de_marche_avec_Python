# 🌍 Étude de marché internationale et segmentation de pays

## 🎯 Objectif

Réaliser une étude de marché internationale afin d'identifier les pays présentant le plus fort potentiel de développement commercial à partir d'indicateurs économiques, démographiques et géopolitiques.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'objectif est d'aider une entreprise à sélectionner les marchés internationaux les plus attractifs en s'appuyant sur une analyse quantitative multicritère.

## ❓ Problématique

Comment exploiter des données internationales afin d'identifier les pays offrant les meilleures opportunités de développement et construire une stratégie d'expansion fondée sur les données ?

## 📂 Sources de données

Les données utilisées proviennent de plusieurs organismes internationaux :

* FAO
* Banque Mondiale
* Données démographiques internationales
* Données économiques et géopolitiques

## 🛠️ Méthodologie

### Préparation des données

* Sélection des variables pertinentes
* Nettoyage des données
* Gestion des valeurs manquantes
* Harmonisation des jeux de données
* Création de nouvelles variables (feature engineering)

### Analyse exploratoire

* Analyse statistique descriptive
* Étude des distributions
* Détection des valeurs atypiques
* Analyse des corrélations

### Réduction de dimension

Mise en œuvre d'une :

* Analyse en Composantes Principales (ACP)

avec :

* Standardisation des données
* Éboulis des valeurs propres
* Cercle des corrélations
* Projection des individus

### Segmentation des pays

Application de méthodes de clustering :

* Classification Ascendante Hiérarchique (CAH)
* K-Means

afin d'identifier des groupes de pays présentant des caractéristiques similaires.

## 📊 Analyses réalisées

### Analyse économique

* PIB par habitant
* Niveau de développement économique
* Potentiel de consommation

### Analyse démographique

* Population
* Dynamique démographique
* Taille des marchés potentiels

### Analyse géopolitique

* Stabilité politique
* Risques pays

### Analyse alimentaire

* Disponibilité alimentaire
* Niveau de sécurité alimentaire

## 📈 Principaux résultats

* Identification de plusieurs segments de pays aux profils distincts
* Mise en évidence des facteurs les plus discriminants
* Construction d'une typologie des marchés internationaux
* Sélection des pays les plus attractifs pour un développement commercial

## 💡 Recommandations stratégiques

Les analyses permettent :

* D'identifier les marchés prioritaires
* D'évaluer les risques associés
* De cibler les pays offrant le meilleur équilibre entre potentiel économique et stabilité
* D'appuyer les décisions d'expansion internationale

## 🧰 Technologies utilisées

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

## 📁 Structure du projet

```text
data/
│
├── population.csv
├── disponibilite_alimentaire.csv
├── pib_habitant.csv
├── stabilite_politique.csv

notebooks/
│
├── nettoyage.ipynb
├── acp.ipynb

exports/
│
├── df_final.csv

README.md
```

## ✅ Compétences développées

* Analyse exploratoire de données
* Feature Engineering
* ACP (Analyse en Composantes Principales)
* Réduction de dimension
* Clustering (CAH & K-Means)
* Segmentation de marchés
* Analyse internationale
* Data Visualisation
* Recommandations stratégiques

## 🚀 Valeur ajoutée métier

Ce projet démontre comment les techniques statistiques et de machine learning non supervisé peuvent être utilisées pour orienter des décisions stratégiques de développement international.

## 👨‍💻 Auteur

**Mohamed Zaidi**
