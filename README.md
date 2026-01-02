# 📊 Moulhat AHMED | Data Analyst
### **Spécialiste Visualisation de Données & Business Intelligence**

<p align="left">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Location-Paris,%20France-blue?style=for-the-badge" alt="Location">
  <img src="https://img.shields.io/badge/Education-Master%20Big%20Data-orange?style=for-the-badge" alt="Education">
</p>

---

## 🚀 À propos de moi
Passionné par l'impact concret des données, j'accompagne les entreprises dans la transformation de données brutes en insights actionnables. Mon parcours, allant du **Master Big Data (Paris Saclay)** au **Mastère Cybersécurité**, me permet d'allier rigueur analytique et compréhension de besoins métier.
j'aide les entreprises à optimiser leurs performances en transformant des volumes de données brutes en informations exploitables pour la prise de décision. Je dispose d'une double compétence : une maîtrise technique des outils (SQL, Python, Excel, Power BI) et une forte compréhension des besoins métiers et de la Business Intelligence. Mon expérience inclut également la préparation et l'intégration de données via des outils ETL comme Talend. Mon objectif est d'apporter des solutions concrètes, qu'il s'agisse d'automatiser des reportings, de valider des hypothèses par les statistiques ou de segmenter une clientèle pour mieux cibler les actions stratégiques



- 🏗️ **Expertise** : Conception de Dashboards - Visualisation de données, Pipelines ETL, Automatisation de reporting et Analyse de KPI.
- 🎓 **Formation** : Datascientest
- 💡 **Ma philosophie** : "Là où certains voient des limites, les données ouvrent des possibilités"


---

## 🛠 Mon Stack Technique

### 📊 Data Visualization & BI
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat-square&logo=power-bi&logoColor=black) 
![Excel](https://img.shields.io/badge/-Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) 

### 🐍 Data Science & Programmation
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) 
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### ⚙️ ETL & Big Data
![Talend](https://img.shields.io/badge/-Talend-FF0000?style=flat-square&logo=talend&logoColor=white) 
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) 
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📂 Projets Data Phares
### 📊 Automatiser les rapports de ventes avec SQL

#### 🧩 Contexte & problématique métier

Une entreprise souhaite disposer d’un **reporting automatisé des performances de ventes**, afin de :

- Suivre l’évolution du chiffre d’affaires dans le temps  
- Identifier les produits les plus rentables et les moins performants  
- Analyser le comportement des clients (fréquence d’achat, contribution au CA)  
- Faciliter la prise de décision commerciale (pricing, promotions, actions marketing)

L’objectif est de **centraliser la logique métier directement en SQL**, afin de garantir des indicateurs cohérents, réutilisables et facilement exploitables dans des outils de reporting.

---

#### 🎯 Objectifs du projet

Ce mini-projet avait pour objectifs de :

- Analyser une base de données relationnelle de ventes (Chinook)
- Extraire et agréger les ventes par produit, client et période
- Calculer des KPI commerciaux clés :
  - Chiffre d’affaires
  - Quantités vendues
  - Prix moyens
- Mettre en place des **vues SQL** pour automatiser le reporting
- Concevoir un **mini data mart de ventes** exploitable dans Excel et Power BI

---

#### 🗂️ Base de données

- **Base utilisée** : Chinook Database  
- **Type** : base de données relationnelle (SQLite)
- **Tables principales exploitées** :
  - `Invoice`
  - `InvoiceLine`
  - `Customer`
  - `Track`

---

#### 🛠️ Approche & méthodologie

##### 1️⃣ Analyse de la base de données
- Compréhension du modèle relationnel
- Identification des clés de jointure
- Analyse des dimensions métier : temps, produits, clients

##### 2️⃣ Requêtes SQL analytiques
- Jointures multi-tables
- Agrégations (`SUM`, `AVG`, `COUNT`)
- Calculs de KPI commerciaux
- Analyses temporelles (mensuelles, trimestrielles)

##### 3️⃣ Automatisation via des vues SQL
- Centralisation de la logique métier
- Création de vues SQL réutilisables
- Calcul dynamique du **dernier trimestre disponible**
- Standardisation des indicateurs de performance

---

#### 📈 Analyses réalisées

Les analyses suivantes ont été automatisées via SQL :

##### 🔹 Performance des ventes
- Ventes mensuelles (courbes de tendance)
- Analyse de la saisonnalité
- Comparaison des performances trimestrielles

##### 🔹 Analyse produit
- Top produits par chiffre d’affaires
- Identification des produits les moins performants
- Analyse Pareto (80/20)
- Contribution des produits au chiffre d’affaires total

##### 🔹 Analyse client
- Meilleurs clients par chiffre d’affaires
- Fréquence d’achat client
- Contribution client au CA
- Aide à l’identification du churn et de la valeur client

---

#### 🧠 Automatisation du reporting avec SQL

Plusieurs **vues SQL métiers** ont été conçues, notamment :

- Vue de ventes du dernier trimestre
- Vue de ventes mensuelles
- Vue de classement des produits
- Vue de performance client

Ces vues permettent :

- Une mise à jour automatique des KPI
- Une exploitation directe dans Excel et Power BI
- Une séparation claire entre :
  - **Logique métier (SQL)**
  - **Visualisation (BI)**

> 💡 La logique métier étant centralisée dans SQL, les indicateurs restent cohérents quel que soit l’outil de restitution.

---

#### 📊 Exploitation dans Excel & Power BI

Les vues SQL ont été connectées à :

- **Excel** (via ODBC) pour créer des tableaux de bord dynamiques
- **Power BI** pour des visualisations interactives

Les dashboards permettent :
- Le suivi des performances commerciales
- L’analyse produit et client
- Le rafraîchissement automatique des données

---

#### 🖼️ Aperçu – requêtes & résultats

##### Exemple de vue SQL – ventes du dernier trimestre
![Vue SQL - ventes dernier trimestre](images/sql_last_quarter_view.png)

##### Résultat de la requête – agrégation par produit
![Résultat requête ventes produit](images/sql_results_sales.png)

##### Exploitation dans Excel
![Dashboard Excel](images/excel_dashboard.png)

> 📌 Les images sont stockées dans le dossier `/images` du repository.

---

#### 🧰 Technologies utilisées

- SQL (SQLite)
- DB Browser for SQLite
- ODBC
- Excel
- Power BI

---

#### ✅ Compétences démontrées

- Analyse de données relationnelles
- SQL analytique (jointures, agrégations)
- Création de vues SQL automatisées
- Modélisation simple de data mart
- Reporting orienté métier
- Connexion SQL → Excel / Power BI

---

#### 📌 Ce que ce projet met en évidence

> Capacité à transformer une base de données brute en **reporting automatisé orienté décision**, en centralisant la logique métier dans SQL et en la rendant exploitable par des outils BI.

---

#### 🚀 Améliorations possibles

- Utilisation de fonctions analytiques (window functions)
- Prévisions simples (moyennes mobiles)
- Segmentation client plus avancée (RFM)


### 🏠 Analyse du Marché Immobilier & Scoring
> Analyse exploratoire des données Airbnb et construction de modèles de scoring de crédit.
- **Outils** : Python (Scikit-learn, Pandas), Jupyter.
- **Résultat** : Identification des facteurs clés influençant les prix et prédiction des comportements d'emprunt.

### 🎬 Système de Recommandation de Films
> Développement d'un algorithme de recommandation basé sur les datasets IMDb/TMDB.
- **Outils** : Python, Machine Learning.
- **Résultat** : Filtrage collaboratif pour suggérer des contenus personnalisés.

---

## 📊 Mes expériences professionnelles

### 🏛️ Migration de Données Patrimoniales (Ministère de la Culture)
> Migration et nettoyage de +100 000 données d'urbanisme.
- **Outils** : Talend, PostgreSQL, ETL Pipelines.


### 📈 Pilotage de Performance Formation (Orange)
> Optimisation du suivi de déploiement de formations internes via des dashboards interactifs.
- **Outils** : Power BI, SQL, KPI Analysis.
- **Résultat** : Amélioration de la visibilité sur le taux de réussite et de satisfaction de +5000 apprenants.

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=TON_PSEUDO&show_icons=true&theme=nord&include_all_commits=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TON_PSEUDO&layout=compact&theme=nord"/>
</p>

---

## 📫 Contactez-moi
Je suis à la recherche de nouveaux défis en Data Analyse et Business Intelligence !

- **LinkedIn** : [linkedin.com/in/moulhat-ahmed](https://www.linkedin.com/in/moulhat-ahmed-7695a31b1/)
- **Email** : [moulhatahmed@gmail.com](mailto:moulhatahmed@gmail.com)
- **Portfolio** : [Lien vers tes projets](#)

---
<p align="center">
  Dernière mise à jour : Décembre 2024 • Réalisé par Moulhat AHMED
</p>
