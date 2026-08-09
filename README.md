<div align="center">

# 📊 Projets Réalisés — Portfolio Data

**Smide ALEXIS** — *Data Analyst & Data Scientist*

Économie appliquée et planification (CTPEA) · Science des données (IBM / Coursera)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

</div>

---

## 🎯 Objet de ce dépôt

Ce dépôt rassemble mes travaux d'analyse et de science des données : modélisation prédictive en Python, tableaux de bord décisionnels, études économétriques et enquêtes statistiques de terrain.

Chaque projet est présenté ci-dessous avec son **contexte**, sa **démarche**, ses **outils** et son **livrable**, afin que le travail puisse être apprécié rapidement.

---

## 🗂️ Organisation

```
01-data-science-python/          Machine learning et visualisation avec Python
02-business-intelligence/        Tableaux de bord Power BI et rapports Excel
03-econometrie-et-statistiques/  Modélisation économétrique et enquêtes statistiques
```

---

## 📌 Vue d'ensemble

| # | Projet | Domaine | Outils | Livrable |
|:--|:--|:--|:--|:--|
| 1 | [Prédiction de l'atterrissage du Falcon 9 — SpaceX](Presentation_de_projet_DS.pdf) | Machine learning | Python, scikit-learn | PDF |
| 2 | [Prix de l'immobilier — King County, USA](01-data-science-python/king-county-house-sales-regression.pdf) | Régression | Python, pandas, scikit-learn | PDF |
| 3 | [Feux de forêt en Australie](01-data-science-python/australia-wildfire-visualization.pdf) | Visualisation de données | Python, pandas | PDF |
| 4 | [Student Performance Analysis Dashboard](02-business-intelligence/student-performance-dashboard.pdf) | Business Intelligence | Power BI | PBIX + PDF |
| 5 | [Rapport de consommation d'énergie](02-business-intelligence/rapport-consommation-energie.xlsx) | Reporting | Excel | XLSX |
| 6 | [Rapport d'analyse Excel](02-business-intelligence/rapport-analyse-excel.xlsx) | Reporting | Excel | XLSX |
| 7 | [Le prix du Bitcoin et les grands agrégats macroéconomiques](03-econometrie-et-statistiques/bitcoin-agregats-macroeconomiques.pdf) | Économétrie | Séries temporelles | PDF |
| 8 | [Aspirations des étudiants — enquête statistique](03-econometrie-et-statistiques/enquete-aspirations-etudiants.pdf) | Statistique appliquée | Enquête, statistique descriptive | PDF |

---

## 🔍 Détail des projets

### 1. Winning Space Race with Data Science — Prédiction de l'atterrissage du Falcon 9

> **Domaine** : machine learning · **Outils** : Python, scikit-learn · **Cadre** : projet capstone, *IBM Data Science Professional Certificate* (février 2024)

Le coût d'un lancement spatial dépend directement de la capacité à récupérer le premier étage du lanceur. Ce projet consiste à collecter les données historiques des lancements de Falcon 9, à les explorer, puis à entraîner des modèles de classification capables de prédire la réussite de l'atterrissage — et donc d'estimer le coût réel d'un lancement.

📄 [Consulter la présentation](Presentation_de_projet_DS.pdf)

---

### 2. House Sales in King County, USA — Estimation du prix des logements

> **Domaine** : analyse exploratoire et régression · **Outils** : Python (pandas, NumPy, SciPy, Seaborn, Matplotlib, scikit-learn)

Mission d'analyste de données pour un fonds d'investissement immobilier souhaitant se positionner sur le résidentiel : déterminer le prix de marché d'un logement à partir de ses caractéristiques. Le jeu de données couvre **21 613 transactions** décrites par **22 variables** (surface habitable, chambres, salles de bain, état général, vue sur l'eau, année de construction, localisation…).

**Démarche** — nettoyage et typage des données, traitement des valeurs manquantes, analyse exploratoire et étude des corrélations, puis modélisation : régression linéaire simple et multiple, régression polynomiale et régression Ridge. Le tout industrialisé avec des *pipelines* scikit-learn (standardisation, transformation polynomiale), une validation croisée et une optimisation des hyperparamètres par `GridSearchCV`. Évaluation par le R² et l'erreur quadratique moyenne.

📄 [Consulter le rapport](01-data-science-python/king-county-house-sales-regression.pdf)

---

### 3. Wildfire Activities in Australia — Analyse et visualisation

> **Domaine** : visualisation de données · **Outils** : Python (pandas, Matplotlib, Seaborn), tableau de bord interactif

Analyse des tendances et des schémas d'activité des feux de forêt selon les régions australiennes. Le travail aboutit à un ensemble de visualisations puis à un tableau de bord interactif permettant à l'utilisateur de sélectionner la **région** et l'**année** pour explorer les données à sa convenance.

📄 [Consulter le rapport](01-data-science-python/australia-wildfire-visualization.pdf)

---

### 4. Student Performance Analysis Dashboard — Power BI

> **Domaine** : business intelligence · **Outils** : Power BI Desktop

Tableau de bord interactif analysant les résultats scolaires de **100 étudiants** en mathématiques, lecture et écriture.

**Indicateurs clés** — score moyen global de **61,18** (mathématiques 62,51 · écriture 60,53 · lecture 60,49).

**Axes d'analyse** — les performances sont ventilées par genre, origine ethnique, niveau d'études des parents et participation à un programme de préparation aux examens. Le rapport intègre des filtres dynamiques, un diagramme de flux croisant origine et éducation parentale, ainsi qu'un classement des cinq meilleurs étudiants.

📊 [Aperçu PDF](02-business-intelligence/student-performance-dashboard.pdf) · 📁 [Fichier source .pbix](02-business-intelligence/student-performance-dashboard.pbix) *(nécessite Power BI Desktop)*

---

### 5. Rapport de consommation d'énergie — Excel

> **Domaine** : reporting et analyse tabulaire · **Outils** : Microsoft Excel

Rapport d'analyse de données de consommation énergétique construit sous Excel.

📁 [Télécharger le classeur](02-business-intelligence/rapport-consommation-energie.xlsx)

---

### 6. Rapport d'analyse Excel

> **Domaine** : reporting et analyse tabulaire · **Outils** : Microsoft Excel

Travail d'analyse et de mise en forme de données sous Excel.

📁 [Télécharger le classeur](02-business-intelligence/rapport-analyse-excel.xlsx)

---

### 7. Le prix du Bitcoin expliqué par les grands agrégats macroéconomiques

> **Domaine** : économétrie appliquée · **Cadre** : cours d'Économétrie, CTPEA

Analyse économétrique sur **données trimestrielles de 2012 à 2023** visant à expliquer l'évolution du prix du Bitcoin à partir des principaux agrégats économiques des pays développés et des pays les plus peuplés. Le travail articule construction de la base de données, spécification du modèle, estimation et interprétation économique des résultats.

📄 [Consulter l'étude](03-econometrie-et-statistiques/bitcoin-agregats-macroeconomiques.pdf)

---

### 8. Recherche statistique sur les aspirations des étudiants

> **Domaine** : statistique appliquée et enquête · **Cadre** : Atelier de statistique appliquée, CTPEA (décembre 2023)

Enquête statistique menée auprès d'étudiants et conduite selon une démarche de recherche complète : justification du sujet, problématique, hypothèse et objectifs, choix des variables, matériels et méthodes, puis analyse et discussion des résultats — répartition par niveau d'étude et par sexe, départements souhaités par les étudiants de première et deuxième année.

📄 [Consulter l'étude](03-econometrie-et-statistiques/enquete-aspirations-etudiants.pdf)

---

## 🧰 Compétences mises en œuvre

| Domaine | Compétences |
|:--|:--|
| **Langages et outils** | Python (pandas, NumPy, SciPy, scikit-learn, Matplotlib, Seaborn), R, SQL, Excel avancé, Power BI |
| **Analyse de données** | Nettoyage et préparation, analyse exploratoire, statistique descriptive et inférentielle |
| **Modélisation** | Régression linéaire, polynomiale et Ridge, classification, validation croisée, optimisation d'hyperparamètres, économétrie sur séries temporelles |
| **Restitution** | Tableaux de bord interactifs, rapports analytiques, visualisation et storytelling de données |
| **Métier** | Économie appliquée, planification économique, analyse de marché |

---

## 📫 Contact

- GitHub — [@Smithy-22](https://github.com/Smithy-22)

<div align="center">

*Merci de votre visite. N'hésitez pas à parcourir les rapports : chacun retrace l'intégralité de la démarche, de la donnée brute à la recommandation.*

</div>
