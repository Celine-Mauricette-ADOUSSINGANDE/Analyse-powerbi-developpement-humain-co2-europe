# 🌍 Analyse du développement humain et des émissions de CO₂ en Europe (2004-2023)

## Présentation du projet

Ce projet consiste à concevoir un tableau de bord interactif avec **Power BI** afin d'analyser l'évolution conjointe du développement humain et des émissions de CO₂ dans les pays européens sur la période **2004-2023**.

L'objectif est d'étudier les relations entre les indicateurs socio-économiques et environnementaux, tout en mettant en évidence les disparités entre les pays européens et les principales sources d'émissions de gaz à effet de serre.

## Problématique

**Comment les pays européens ont-ils concilié, entre 2004 et 2023, l'amélioration du niveau de vie avec la réduction des émissions de CO₂, et quels sont les différents secteurs à l'origine de ces émissions ?**

## Objectifs du projet

- Analyser l'évolution des émissions de CO₂ en Europe entre 2004 et 2023.
- Étudier les disparités entre les pays européens en matière d'émissions.
- Explorer les relations entre le développement humain, le PIB par habitant et les revenus.
- Identifier les principaux secteurs responsables des émissions de gaz à effet de serre.
- Comparer les indicateurs environnementaux et socio-économiques à l'échelle européenne et française.
- Concevoir un tableau de bord interactif facilitant l'exploration des données.

## Outils et technologies

| Outil | Utilisation |
|---|---|
| Power BI | Création des tableaux de bord et visualisations |
| Power Query | Importation, nettoyage et transformation des données |
| DAX | Création de mesures et indicateurs dynamiques |
| Eurostat | Source principale des données statistiques |
| REST Countries API | Informations sur les pays européens |
| Flagpedia | Images des drapeaux des pays |

## Sources de données

Les données utilisées proviennent principalement d'Eurostat et d'autres sources complémentaires.

| Indicateur | Source / Référence |
|---|---|
| PIB réel par habitant | Eurostat – `tipsna40` |
| Revenu moyen et médian par âge et sexe | Eurostat – `ilc_di03` |
| Émissions de gaz à effet de serre par secteur | Eurostat – `env_air_gge` |
| Population par niveau d'éducation | Eurostat – `edat_lfs_9904` |
| Caractéristiques des pays européens | REST Countries API |
| Drapeaux des pays | Flagpedia |

## Méthodologie

Le projet suit une démarche d'analyse de données basée sur le processus **ETL (Extract, Transform and Load)**.

### 1. Extraction des données
- Collecte des données statistiques sur Eurostat.
- Récupération des caractéristiques des pays européens.
- Importation des différentes sources dans Power BI.

### 2. Transformation des données
- Nettoyage des données avec Power Query.
- Harmonisation des formats et des variables.
- Vérification de la cohérence des informations.
- Préparation des données pour l'analyse.

### 3. Modélisation des données
- Construction d'un modèle relationnel.
- Organisation des tables de faits et de dimensions.
- Mise en place des relations entre les différentes tables.

### 4. Analyse et visualisation
- Création de mesures dynamiques avec DAX.
- Définition des indicateurs clés de performance (KPI).
- Conception de tableaux de bord interactifs.
- Mise en place de filtres permettant une analyse par pays et par période.

## Présentation du tableau de bord

Le tableau de bord est organisé autour de plusieurs axes d'analyse :

### 🇪🇺 1. Vue d'ensemble de l'Europe
- Évolution des émissions de CO₂ entre 2004 et 2023.
- Analyse des indicateurs clés de performance.
- Comparaison des émissions entre les pays européens.
- Exploration des relations entre PIB par habitant et revenu moyen.

### 🇫🇷 2. Analyse de la France
- Présentation des indicateurs clés de la France.
- Analyse des données socio-économiques.
- Suivi des émissions de gaz à effet de serre.

### 3. Répartition des émissions par pays
- Cartographie des émissions en Europe.
- Comparaison des niveaux d'émissions entre les pays.
- Identification des principaux pays émetteurs.

### 4. Analyse sectorielle des émissions en France
- Répartition des émissions selon les secteurs d'activité.
- Identification des principales sources de pollution.
- Analyse des caractéristiques socio-démographiques.

## Principaux constats

L'analyse présentée dans le rapport met notamment en évidence :

- L'Allemagne figure parmi les principaux pays émetteurs de gaz à effet de serre en Europe.
- L'Italie, la France, la Pologne et l'Espagne présentent également des niveaux d'émissions importants.
- Les émissions varient sensiblement selon les pays européens.
- Le secteur de l'énergie constitue la principale source d'émissions identifiée dans l'analyse sectorielle de la France, suivi de l'agriculture.
- Les indicateurs économiques et sociaux permettent de compléter l'analyse environnementale.



## Compétences mobilisées

- Analyse et exploration de données.
- Extraction, nettoyage et transformation des données (ETL).
- Modélisation relationnelle des données.
- Création de mesures avec DAX.
- Data Visualisation et conception de tableaux de bord.
- Analyse des indicateurs socio-économiques et environnementaux.
- Utilisation de Power BI et Power Query.


## Auteur

**Céline Mauricette S. ADOUSSINGANDE**

Projet réalisé dans le cadre d'un projet de substitution au stage à Aix-Marseille School of Economics (AMSE).

## Période d'analyse

2004 – 2023

---

*Ce projet a pour ambition de contribuer à une meilleure compréhension des liens entre développement humain, activités économiques et enjeux environnementaux en Europe.*
