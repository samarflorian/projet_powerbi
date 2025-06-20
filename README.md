# 📊 Premier League Dashboard – Analyse interactive avec Power BI

Ce projet Power BI propose une analyse complète de plusieurs saisons de Premier League anglaise, avec un accent sur la performance d'une équipe sélectionnée.

## 🧠 Objectif du projet

L'objectif est de créer un tableau de bord interactif permettant à un utilisateur de :

- Sélectionner une équipe de Premier League,
- Visualiser ses performances saison après saison,
- Comparer ses résultats à d'autres clubs,
- Étudier son évolution dans le classement et ses statistiques clés.

Ce projet a été conçu comme un **cas pratique de niveau Data Analyst junior**, avec un fort accent sur l’interprétation des données sportives.

---

## 🔍 Données utilisées

Les données proviennent de [Football-Data.co.uk](https://www.football-data.co.uk/) et ont été nettoyées puis transformées sous Power Query.

Colonnes clés :
- `Date`, `HomeTeam`, `AwayTeam`, `FTHG`, `FTAG`
- Colonnes calculées : `Points`, `ButsPour`, `ButsContre`, `Résultat`, `CleanSheet`, `GoalAverage`, `Classement`, etc.

---

## 📁 Pages du rapport

### 📄 Page 1 – Vue synthétique
- Points par match, taux de victoire, taux de clean sheets
- Buts pour / contre
- Graphique de résultats mensuels

### 📄 Page 2 – Classements par saison
- Rang par saison
- Classement moyen
- Historique visuel avec colorisation automatique

### 📄 Page 3 – Analyse par équipe
- Choix libre d'une équipe
- Visualisation de ses performances globales
- Graphiques dynamiques et jauges

### 📄 Page 4 – Comparaison entre deux équipes
- Résultats directs
- Bilan des confrontations
- Comparatif visuel de stats clés

### 📄 Page 5 – Dynamique d’une saison
- Histogramme mensuel de résultats
- Courbe des points cumulés
- Analyse des phases fortes / faibles

---

## 🛠️ Outils utilisés

- **Power BI Desktop**
- **Power Query (ETL)**
- **DAX** (pour calculs de KPIs, classement dynamique, taux, etc.)

---

## ✅ Résultat

Ce tableau de bord permet d’explorer et de visualiser les performances des clubs anglais **de manière interactive et professionnelle**, dans une logique de storytelling analytique.

---

## 📎 Aperçu

![Aperçu page 1](lien_image_page1.png)
![Aperçu page 2](lien_image_page2.png)

---

## 📌 Auteur

**Florian S.** – Passionné par l’analyse de données et le football.  
📫 Contact : *[Ton adresse mail ou ton LinkedIn]*

---

## ⚠️ Remarques

- Le projet n’intègre pas les sanctions administratives (ex : retraits de points).
- L’ajout de saisons futures est possible par simple extension des données.

