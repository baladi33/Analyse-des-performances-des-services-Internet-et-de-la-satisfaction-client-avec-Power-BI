# 📊 Analyse des performances des services Internet et de la satisfaction client

## 📌 Description

Ce projet consiste à concevoir un tableau de bord interactif avec **Power BI** afin d'analyser les performances des services Internet, d'évaluer la qualité des réseaux et de mesurer la satisfaction des clients.

L'objectif est de transformer les données en informations exploitables pour aider les décideurs à identifier les points forts, les faiblesses et les axes d'amélioration des services Internet.

---

## 🎯 Objectifs du projet

- Analyser les performances des réseaux Internet.
- Évaluer la satisfaction des clients.
- Comparer les fournisseurs d'accès Internet.
- Étudier l'impact de la vitesse, de la latence et de la stabilité sur la satisfaction.
- Fournir des recommandations basées sur les données.

---

## 🛠️ Technologies utilisées

- Power BI
- Power Query
- DAX
- SQL
- Python (Pandas, NumPy, Matplotlib)
- Modélisation en étoile (Star Schema)

---

# 📂 Structure du projet

```
📁 Data
│
├── Dataset Internet.csv
│
📁 Power BI
│
├── Internet Performance Dashboard.pbix
│
📁 Images
│
├── Page_Garde.png
├── Executive_Dashboard.png
├── Network_Performance.png
└── Customer_Satisfaction.png
│
└── README.md
```

---

# 📈 Modèle de données

Le projet repose sur une modélisation en étoile composée de :

### Table de faits

- Fact Table

### Tables de dimensions

- Dim Country
- Dim Provider
- Dim Network
- Dim Region
- Dim Gender

Cette modélisation facilite les analyses multidimensionnelles et améliore les performances du tableau de bord.

---

# 📊 Structure du Dashboard

## 📄 Page de garde

Présentation du projet avec :

- Titre
- Boutons de navigation
- Présentation générale

---

## 📄 Page 1 — Tableau de bord exécutif

Vue d'ensemble des performances.

### KPI

- Total Clients
- Satisfaction moyenne
- Vitesse moyenne de téléchargement
- Vitesse moyenne d'envoi
- Latence moyenne
- Stabilité moyenne

### Visualisations

- Carte des performances par pays
- Treemap de satisfaction par pays
- Classement des fournisseurs
- Répartition des technologies réseau
- Tableau récapitulatif par pays

---

## 📄 Page 2 — Analyse des performances réseau

Analyse technique des réseaux.

### KPI

- Signal moyen
- Vitesse moyenne de téléchargement
- Vitesse moyenne d'envoi
- Latence moyenne
- Stabilité moyenne

### Visualisations

- Vitesse de téléchargement par fournisseur
- Vitesse de téléversement par technologie
- Stabilité par pays
- Latence par technologie réseau
- Nuage de points (Téléchargement vs Téléversement)
- Intensité du signal par technologie

---

## 📄 Page 3 — Analyse de la satisfaction client

Analyse détaillée de la satisfaction des utilisateurs.

### KPI

- Clients satisfaits
- Clients insatisfaits
- Satisfaction moyenne
- Coût mensuel moyen
- Revenu total

### Visualisations

- Répartition des niveaux de satisfaction
- Satisfaction par tranche d'âge
- Satisfaction par type de région
- Coût mensuel vs satisfaction
- Consommation de données vs satisfaction
- Répartition des clients par genre

---

# 📊 Principales analyses

Le tableau de bord permet notamment de :

- Comparer les performances des fournisseurs Internet.
- Identifier les pays offrant la meilleure qualité de service.
- Mesurer l'impact de la vitesse Internet sur la satisfaction.
- Étudier l'influence de la latence sur l'expérience utilisateur.
- Comparer les technologies réseau (2G, 3G, 4G, 5G et Fibre).
- Analyser les segments de clients les plus satisfaits.

---

# 💡 Principaux enseignements

- Les réseaux Fibre et 5G offrent les meilleures performances.
- Une faible latence améliore significativement l'expérience utilisateur.
- La satisfaction augmente avec la vitesse de téléchargement jusqu'à un certain seuil.
- Les fournisseurs présentent des niveaux de performance différents selon les pays.
- Les régions urbaines bénéficient généralement d'une meilleure qualité de connexion.

---

# 📸 Aperçu du Dashboard

## 📄 Page de garde

*(Ajouter une capture d'écran)*

---

## 📊 Tableau de bord exécutif

*(Ajouter une capture d'écran)*

---

## 🌐 Analyse Performance du réseau

*(Ajouter une capture d'écran)*

---

## 😊 Analyse de la satisfaction des clients

*(Ajouter une capture d'écran)*

---

# 🚀 Compétences mises en œuvre

- Nettoyage et transformation des données
- Modélisation de données (Star Schema)
- Création de mesures DAX
- Power Query
- Data Visualization
- Storytelling
- Analyse décisionnelle
- Conception d'un tableau de bord interactif

---

# 👨‍💻 Auteur

**Baladi Zoubair**

Data Analyst | Business Intelligence

LinkedIn : https://www.linkedin.com/in/zoubair-baladi/

GitHub :  https://github.com/baladi33 

---

# ⭐ Remerciements

Projet réalisé dans le cadre de la formation **Data Analyst**.

Merci pour votre visite !

N'hésitez pas à laisser une ⭐ si ce projet vous a été utile.
