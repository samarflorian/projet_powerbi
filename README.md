# ⚽️ Analyse Premier League (2019–2025) – Projet Power BI

Ce projet Power BI explore les **6 dernières saisons de Premier League** (2019–2020 à 2024–2025) afin d’en tirer des insights sur les performances des clubs anglais.  
L’objectif est de créer un tableau de bord complet, interactif, et accessible à tout utilisateur souhaitant comparer ou analyser la dynamique d’un club.

---

## 📁 Contenu du projet

| Fichier / Dossier                      | Description                                                       |
|----------------------------------------|-------------------------------------------------------------------|
| `Analyse_PL_2019_2025.pbix`            | Rapport Power BI complet (5 pages interactives)                  |
| `PL1925.csv`                           | Jeu de données avec tous les matchs entre 2019 et 2025           |
| `images/`                              | Dossier contenant les captures du rapport                        |
| `README.md`                            | Ce fichier de présentation                                       |

---

## 📊 Pages du tableau de bord Power BI

### 1. **Page 1: Accueil – Vue synthétique**
- Résumé des performances globales d’une équipe sur 6 saisons
- Moyenne de points, taux de victoire, buts / match
- Graphiques PPM (points par match) et buts / match

### 2. **Page 2: Classement par saison**
- Classement général avec couleur automatique :  
  🟢 Ligue des Champions | ⚪ Maintien | 🔴 Relégation
- Jauge de **classement moyen**
- Filtrage dynamique par saison et lieu

### 3. **Page 3: Analyse par équipe**
- Moyennes offensives et défensives par saison
- Ratio victoire / nul / défaite (camembert)
- Taux de clean sheet
- Points par mois et histogramme des buts pour / contre

### 4. **Page 4: Comparaison entre deux équipes**
- Comparaison côte à côte sur :
  - Pourcentage de victoires / nuls / défaites
  - Total de buts pour / contre
  - Points par match
- Sélection dynamique des équipes A et B

### 5. **Page 5: Dynamique d’une saison**
- Évolution mensuelle :
  - Buts pour / contre (barres empilées)
  - Résultats mensuels (victoires, nuls, défaites)
  - Points cumulés par mois

---

## 🧾 Structure des données

### ✅ Données principales (`PL1925.csv`)
- `Date`, `Saison`, `Lieu`, `Équipe`, `Adversaire`
- `ButsPour`, `ButsContre`, `Résultat`
- `Points`, `Rang`, `CleanSheet`

### 🧠 Mesures DAX utilisées
- `Points / Match`
- `Taux de Victoire`, `Taux de Nul`, `Taux de Défaite`
- `TauxCleanSheet`
- `Classement_Moyen`, `ValeurMax`, `ValeurMin`
- `PointsCumulés`, `PireClassement`, etc.

---

## 🧠 Objectifs pédagogiques

- 🎯 Présenter mes compétences en **Power BI** (nettoyage, modélisation, visualisation)
- 📊 Créer un tableau de bord **complet et interactif**
- 🧠 Valoriser ma capacité à **analyser des données sportives dans le temps**

---

## 📎 Pour lancer le projet

1. Ouvrir le fichier `Analyse_PL_2019_2025.pbix` dans Power BI Desktop  
2. Vérifier le chemin d’accès au fichier CSV `PL1925.csv`  
3. Rafraîchir les données si nécessaire  
4. Naviguer entre les 5 pages pour explorer tous les visuels

---

## 🧵 Auteur

**Florian Samar**  
*Passionné de football, de Power BI et de storytelling par la donnée.  
Ce projet est une synthèse de mes compétences en Data Analysis sur un sujet que j’adore.*  
📍 Pour toute question : n’hésitez pas à me contacter ou à visiter mon profil GitHub.

---
