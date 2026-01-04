# 📂 Manipulation base de donnée relationelle

---
## 📊 **Automatiser les rapports de ventes avec SQL**

### 🧩 Contexte & problématique métier

Une entreprise souhaite disposer d’un **reporting automatisé des performances de ventes**, afin de :

- Suivre l’évolution du chiffre d’affaires dans le temps  
- Identifier les produits les plus rentables et les moins performants  
- Analyser le comportement des clients (fréquence d’achat, contribution au CA)  
- Faciliter la prise de décision commerciale (pricing, promotions, actions marketing)

L’objectif est de centraliser la logique métier directement en SQL, afin de garantir des indicateurs cohérents, réutilisables et facilement exploitables dans des outils de reporting.

---

### 🎯 Objectifs du projet

Ce mini-projet a pour objectifs de :

- Analyser une base de données relationnelle de ventes (Chinook)
- Extraire et agréger les ventes par produit, client et période
- Calculer des KPI commerciaux clés :
  - Chiffre d’affaires
  - Quantités vendues
- Mettre en place des **vues SQL** pour automatiser le reporting
- Concevoir un mini data mart de ventes exploitable dans Excel et Power BI

---

### 🗂️ Base de données

- **Base utilisée** : Chinook Database  
- **Type** : base de données relationnelle (SQLite)
- **Tables principales exploitées** :
  - `Invoice`
  - `InvoiceLine`
  - `Customer`
  - `Track`

---

### 🛠️ Approche & méthodologie

#### 1️⃣ Analyse de la base de données
- Compréhension du modèle relationnel
- Identification des clés de jointure
- Analyse des dimensions métier : temps, produits, clients

#### 2️⃣ **Requêtes SQL analytiques**
- Jointures multi-tables
- Agrégations (`SUM`, `AVG`, `COUNT`)
- Calculs de KPI commerciaux
- Analyses temporelles (mensuelles, trimestrielles)

#### 3️⃣ Automatisation via des vues SQL
- Centralisation de la logique métier
- Création de vues SQL réutilisables
- Calcul dynamique du **dernier trimestre disponible**
- Standardisation des indicateurs de performance

---

### 📈 Analyses réalisées

Les analyses suivantes ont été automatisées via SQL :

#### 🔹 Performance des ventes
- Ventes mensuelles (courbes de tendance)
- Analyse de la saisonnalité
- Comparaison des performances trimestrielles

#### 🔹 Analyse produit
- Top produits par chiffre d’affaires
- Identification des produits les moins performants
- Analyse Pareto (80/20)
- Contribution des produits au chiffre d’affaires total

#### 🔹 Analyse client
- Meilleurs clients par chiffre d’affaires
- Fréquence d’achat client
- Contribution client au CA
- Aide à l’identification du churn et de la valeur client

---

### 🧠 Automatisation du reporting avec SQL

Plusieurs **vues SQL métiers** ont été conçues, notamment :

- Vue de ventes du dernier trimestre
- Vue de ventes mensuelles
- Vue de classement des produits
- Vue de performance client

Ces vues permettent une mise à jour automatique des KPI et une exploitation directe dans Excel et Power BI

---

### 📊 Exploitation dans Excel & Power BI

Les vues SQL peuvent être été connectées à Excel via ODBC pour créer des tableaux de bord dynamiques ou à Power BI pour des visualisations interactives sur :

  - Le suivi des performances commerciales
  - L’analyse produit et client
  - Le rafraîchissement automatique des données

---

### 🖼️ Aperçu – requêtes & résultats

#### Exemple de vue SQL – ventes du dernier trimestre
![Vue SQL - ventes dernier trimestre](images/sql_last_quarter_view.png)

#### Résultat de la requête – agrégation par produit
![Résultat requête ventes produit](images/sql_results_sales.png)

> 📌 Les images sont stockées dans le dossier `/images` du repository.

---

### 🚀 Améliorations possibles
- Utilisation de fonctions analytiques (window functions)
- Prévisions simples (moyennes mobiles)
- Segmentation client plus avancée (RFM)
