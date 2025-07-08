# 🧠 Naziha Boussemaha – Data Analysis Portfolio  
🧰 Compétences clés : Python · SQL · Power BI · Knime · Scikit-learn  
🎓 Projets réalisés dans le cadre de la formation Data Analyst (OpenClassrooms)  
📍 Yvelines | France entière | Full Remote  
📧 nboussem81@outlook.fr  
🔗 [GitHub](https://github.com/Nha-Bssha) · [LinkedIn](https://www.linkedin.com/in/nabdb2a441200/)

## 🗂️ Sommaire des projets  
🛠 Outils & langages utilisés : Python · SQL · Power BI · Knime · Scikit-learn  
1. Analyse du marché immobilier en France (SQL, SQLite)  
2. Analyse FAO : sous-nutrition dans le monde (Python)  
3. Optimisation et automatisation des données produits e-commerce (Python)  
4. Comportement de consommation des clients e-commerce (Python)  
5. Automatisation de reporting RH (Knime)  
6. Analyse de l’attrition client Telco (Power BI, DAX)  
7. Lancement activité agro-alimentaire à l'international (Python, ML non supervisé)  
8. Modèle prédictif de faux billets (Python, ML supervisé)

---

## 🇫🇷 Projets Data Analyse

### 1. 🏡 Analyse du marché immobilier en France  
- **Thématique** : Immobilier / Données publiques  
- ❓ **Problématique** : Comment structurer une base de données relationnelle fiable pour suivre l’évolution du marché immobilier français ?  
- 🎯 **Objectif** : Mettre à jour et améliorer une base de données relationnelle pour analyser les transactions immobilières et foncières en France.  
- 🛠 **Stack** : SQLite Studio, SQL, MCD, 3FN  

- 📊 **Résultats clés** :
  - Structuration de la base selon les 3FN avec dictionnaire, MCD, MLD et modèle physique
  - Ajout des régions et population aux communes pour analyses croisées
  - 12 requêtes SQL pour explorer le marché : prix au m², écarts F2/F3, communes les plus dynamiques, évolution trimestrielle, etc.

🔗 [Slides PowerPoint projet 1](https://1drv.ms/p/c/d3757a171cf8daaf/Edu7qRL-cuNGgrbz9s31lHoB9QK8PjmlpftPv1M82DIFWw?e=jtEdKW)

---

### 2. 🌍 Analyse FAO : sous-nutrition dans le monde  
- **Thématique** : Humanitaire / Agriculture / Économie mondiale  
- ❓ **Problématique** : Quels déséquilibres expliquent la persistance de la sous-nutrition à l’échelle mondiale malgré une production alimentaire suffisante ?  
- 🎯 **Objectif** : Explorer les inégalités structurelles d’accès à l’alimentation à travers une analyse géopolitique, économique et nutritionnelle.  
- 🛠 **Stack** : Python, GeoPandas, Matplotlib  

- 📊 **Résultats clés** :
  - Analyse de données FAO et géopolitiques (production, import/export, conflits, aide alimentaire)
  - Étude de cas : Thaïlande, Égypte, Autriche, Syrie, Yémen, Soudan, etc.
  - Mise en évidence du paradoxe surabondance/sous-nutrition

🔗 [Slides PowerPoint projet 2](https://1drv.ms/p/c/d3757a171cf8daaf/ERM9pDYi4KtLm-8ryKa-tloBGqTwpW7YM8smzrIcSWLaIg?e=IbZb88)

---

### 3. 🛒 Optimisation et automatisation des données d'un e-commerce  
- **Thématique** : E-commerce / Intégration & qualité des données  
- ❓ **Problématique** : Comment fiabiliser et automatiser la gestion des données entre un ERP interne et un CMS e-commerce ?  
- 🎯 **Objectif** : Nettoyer, croiser et automatiser l'intégration des données produits et ventes pour améliorer le pilotage de l'activité.  
- 🛠 **Stack** : Python (Pandas), ERP, CMS, analyse univariée, jointures, méthode IQR, Z-score  

- 📊 **Résultats clés** :
  - Nettoyage et structuration des exports ERP & CMS : renommage, filtrage, dédoublonnage, traitement des colonnes vides et des valeurs manquantes  
  - Jointure interne fiable avec contrôle d’unicité et harmonisation des clés  
  - Détection des outliers (prix) entre vins courants et vins de prestige  
  - Pipeline de contrôle qualité pour fiabiliser les analyses internes  

🔗 [Slides PowerPoint projet 3](https://1drv.ms/p/c/d3757a171cf8daaf/EczkDKtx-rFJhpm1URMrOSYBAgJVyZE680VFzo2wJ3Zi9g?e=8KQDmG)

### 4. 📦 Comportement de consommation des clients e-commerce (Python)
- **Thématique** : Segmentation / Comportement client
-❓**Problématique** : Quels sont les profils d’acheteurs les plus fréquents sur un site e-commerce ?
- 🎯 **Objectif** : Réaliser une segmentation client par clustering (K-Means) et interpréter les comportements selon le genre, l’âge, le type de clientèle (B2B/B2C), et les périodes de l’année.
- 🛠 **Stack** : Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

- 📊 **Résultats clés** :
- 2 types de clients : BtoB et BtoC ; parité chez les B2C mais déséquilibre chez les B2B
- +23,66 % de chiffre d'affaires entre 2021 et 2022
- 7,36 % du CA en 2022 généré par seulement 4 clients B2B → forte concentration (Courbe de Lorenz)
- Corrélations négatives modérées entre l’âge et : total des achats, fréquence, taille du panier moyen
- Inégalité d’accès aux catégories produits selon le genre

🔗 [Slides PowerPoint projet 4](https://1drv.ms/p/c/d3757a171cf8daaf/EfNRC9xh8odImIVZrTACIKwBWySPgi7UjRvJsPMEnw4tug?e=9Wv5LW)
