# ⚽️ Analyse Premier League 2023–2024 – Projet Power BI

Ce projet a pour objectif d’analyser la saison 2023–2024 de Premier League anglaise à travers un tableau de bord interactif conçu avec **Power BI**. Il permet d'explorer les performances des équipes, leurs dynamiques mensuelles, les comparaisons entre clubs et le classement global.

---

## 📁 Contenu du projet

| Dossier / Fichier           | Description                                                       |
|-----------------------------|-------------------------------------------------------------------|
| `PL23.pbix`                 | Fichier principal Power BI avec toutes les visualisations        |
| `data/PL23.csv`             | Fichier source contenant les données de matchs                   |
| `images/`                   | Captures d’écran des pages du dashboard                          |
| `README.md`                 | Présentation du projet (ce fichier)                              |

---

## 📊 Pages du rapport Power BI

### 1. **Accueil – Vue synthétique**
- Moyenne de points, taux de victoire et efficacité offensive par saison
- Graphique des **PPM** (points par match) et des **buts/match**
- Sélection dynamique d'équipe et de saison

### 2. **Classement par saison**
- Classement global par points, différence de buts
- Affichage dynamique par saison et lieu (domicile / extérieur)
- Jauge du **classement moyen**

### 3. **Analyse par équipe**
- Moyenne de buts pour / contre
- Points par mois
- Ratio victoires / nuls / défaites
- Taux de clean sheet

### 4. **Comparaison entre deux équipes**
- Comparaison côte à côte : % de victoire, buts pour/contre, points
- Sélection d'équipe A et B via slicer

### 5. **Dynamique d’une saison**
- Suivi mensuel de :
  - Buts pour vs contre
  - Points cumulés
  - Ratio résultats (victoire, nul, défaite)

---

## 🧾 Colonnes et mesures utilisées

### ✅ Colonnes clés :
- `Date`, `Lieu`, `Saison`, `Équipe`, `Adversaire`
- `ButsPour`, `ButsContre`, `Résultat`
- `Points`, `Rang`, `CleanSheet`

### 🧠 Mesures DAX créées :
- `Points / Match`, `PointsCumulés`
- `Taux de Victoire`, `Taux de Nul`, `Taux de Défaite`
- `TauxCleanSheet`, `ValeurMax`, `Classement_Moyen`

---

## 💾 Source de données

Le fichier source `PL23.csv` est disponible dans le dossier [`/data`](./data).  
Il contient les données match par match pour chaque équipe de Premier League.

> Pour actualiser les visuels dans Power BI, assurez-vous que le fichier `.csv` est placé dans le bon dossier.

---

## 🧠 Objectifs pédagogiques

- Valoriser mes compétences en **modélisation Power BI**  
- Créer un tableau de bord **intuitif, interactif et complet**  
- Réaliser un projet complet **de niveau Data Analyst Junior**

---

## 🧵 Auteur

**Florian Samar**  
📌 Passionné de football et de data. Ce projet Power BI mêle deux de mes centres d’intérêt et illustre mes compétences en visualisation et storytelling de données.
