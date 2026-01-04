
### **Spécialiste Visualisation de Données & Business Intelligence**

<p align="left">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Location-Paris,%20France-blue?style=for-the-badge" alt="Location">
  <img src="https://img.shields.io/badge/Education-Master%20Big%20Data-orange?style=for-the-badge" alt="Education">
</p>

---

## 🚀 À propos de moi
Passionné par l'impact concret des données, j'accompagne les entreprises dans la transformation de données brutes en insights actionnables. Mon parcours, allant du Master Big Data (Paris Saclay) au Mastère Cybersécurité, me permet d'allier rigueur analytique et compréhension de besoins métier.
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

## 📂 Projets réalisés
### 📊 ** 1 Automatisation de rapports de ventes avec SQL**
Dans ce projet, j’ai travaillé sur la conception d’un système de reporting de ventes automatisé à partir d’une base de données relationnelle existante : **Chinook Database**. L’objectif était de répondre à des problématiques concrètes de pilotage de la performance commerciale, en centralisant la logique métier directement dans SQL afin de produire des indicateurs fiables, cohérents et exploitables dans des outils de Business Intelligence.

#### 🧩 **Contexte & problématique métier**
Une entreprise souhaite disposer d’un reporting automatisé offrant une vision claire et actualisée de ses performances de ventes, pour suivre l’évolution du chiffre d’affaires dans le temps, identifier les produits les plus rentables, détecter les produits sous-performants et mieux comprendre le comportement de ses clients(fréquence d’achat, contribution au CA), afin de faliciter la prise de décisions éclairées en matière de pricing, de promotions et de stratégie commerciale (actions marketing. :

#### 🛠️ **Approche & méthodologie**
Pour répondre à ces besoins, j’ai commencé par analyser le modèle relationnel de la base de données Chinook, en identifiant les tables clés liées aux ventes, aux produits, aux clients et aux dates de facturation. Cette étape m’a permis de comprendre les relations entre les entités et de définir les dimensions métiers nécessaires à l’analyse : le temps, les produits et les clients.

##### 🧰 **Technologies utilisées**
- SQL (SQLite)
- DB Browser for SQLite

J’ai ensuite développé des requêtes SQL analytiques reposant sur des jointures multi-tables et des agrégations avancées (SUM, AVG, COUNT) afin de calculer les principaux indicateurs de performance commerciale (chiffre d'affaires, quantités vendues, etc.). 
Afin de rendre le reporting durable et facilement exploitable, j’ai conçu plusieurs vues SQL métiers qui centralisent la logique de calcul des KPI. Ces vues constituent un mini data mart de ventes, structuré autour d’indicateurs standards et directement consommable par des outils comme Excel ou Power BI. Cette approche permet de séparer clairement la logique métier, implémentée en SQL, de la couche de visualisation, garantissant ainsi la cohérence des indicateurs quel que soit l’outil de restitution utilisé.
Les analyses mises en place couvrent plusieurs dimensions clés de la performance commerciale :
  - **Suivi des ventes mensuelles et trimestrielles** afin d'identifier les périodes de forte activité, de mettre en évidence des phénomènes de saisonnalité et de comparer les performances d’un trimestre à l’autre. Ces analyses sont essentielles pour anticiper les pics de ventes et ajuster les stratégies commerciales en fonction des périodes les plus porteuses.
  - **Analyse produits** : pour identifier les produits les plus rentables, mais aussi ceux dont les performances sont insuffisantes. L’utilisation d’une analyse de type Pareto (80/20) met en évidence le nombre minimal de produits générant la majorité du chiffre d’affaires. Cette approche aide à prioriser les efforts marketing, à optimiser les assortiments et à concentrer les actions commerciales sur les produits à plus forte valeur ajoutée.
  - **Analyse clients** : pour identifier les meilleurs clients en termes de chiffre d’affaires et de fréquence d’achat. Ces analyses permettent de mettre en place une segmentation client de type RFM (Récence, Fréquence, Montant), essentielle pour comprendre la valeur des clients et adapter les actions marketing. Grâce à cette segmentation, il devient possible d’identifier les clients à forte valeur afin de les fidéliser, de repérer les clients à risque de churn et de proposer des offres ou promotions ciblées en fonction des habitudes d’achat.

L’ensemble de ces analyses offre une vision complète et actionnable de la performance commerciale. Elles permettent non seulement de suivre les indicateurs clés, mais aussi d’orienter les décisions stratégiques, qu’il s’agisse d’optimiser les ventes sur certaines périodes, de mettre en avant des produits spécifiques ou de personnaliser les actions marketing selon les profils clients.

#### 🖼️ Aperçu – requêtes & résultats
##### Exemple de vue SQL – ventes du dernier trimestre
![Vue SQL - ventes dernier trimestre](images/sql_last_quarter_view.png)

##### Résultat de la requête – agrégation par produit
![Résultat requête ventes produit](images/sql_results_sales.png)

#### ✅ Compétences démontrées
> Ce projet illustre ma capacité à utiliser SQL comme un véritable outil d’analyse et de pilotage métier, et non comme un simple langage de requêtage. En centralisant la logique analytique dans des vues SQL automatisées, j’ai modélisé un data mart simple et conçu une solution de reporting robuste, évolutive et directement exploitable dans un contexte professionnel de Business Intelligence.

---

### 🏠 2 Analyse du Marché Immobilier & Scoring
> Analyse exploratoire des données Airbnb et construction de modèles de scoring de crédit.
- **Outils** : Python (Scikit-learn, Pandas), Jupyter.
- **Résultat** : Identification des facteurs clés influençant les prix et prédiction des comportements d'emprunt.

### 🎬 3 Système de Recommandation de Films
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
