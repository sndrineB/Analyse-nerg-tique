# Analyse énergétique: 
# Cartographie des Territoires à Potentiel de Flexibilité Énergétique
Ce projet, réalisé par l’équipe Data de FlexiMap Solutions (entreprise fictive créée dans le cadre de ce projet final de formation), vise à identifier les territoires en France métropolitaine où des actions de flexibilité énergétique (effacement, pilotage de la consommation) peuvent être stratégiquement déployées. Il combine analyse de données open-source, modélisation d'indicateurs de flexibilité et visualisation interactive.


# 🎯 Objectifs du Projet
🗺️ Identifier les zones à forte consommation pilotable
‣ Secteurs concernés : tertiaire et industriel
🧮 Calculer un indice de flexibilité
‣ Basé sur la consommation énergétique et la dépendance énergétique
🌍 Visualiser ces zones sur une cartographie interactive
‣ Objectif : aider à la décision via une interface claire et dynamique

# 🧰 Outils & Technologies Utilisés
🐍 Python
‣ 📦 Pandas, 🔢 NumPy, 📊 Matplotlib
📊 Power BI
‣ Visualisation de données interactive et tableaux de bord dynamiques
📓 Jupyter Notebooks
‣ Documentation pas à pas de l’analyse et visualisations intégrées

# Jeux de données
https://odre.opendatasoft.com/explore/embed/dataset/conso-departement-annuelle/table/?disjunctive.libelle_region&disjunctive.libelle_departement&disjunctive.g_operateurs&disjunctive.e_operateurs&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJjb25zb3RvdGFsZSIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLWN1c3RvbSJ9XSwieEF4aXMiOiJhbm5lZSIsIm1heHBvaW50cyI6bnVsbCwic29ydCI6IiIsInRpbWVzY2FsZSI6InllYXIiLCJzZXJpZXNCcmVha2Rvd24iOiJsaWJlbGxlX3JlZ2lvbiIsImNvbmZpZyI6eyJkYXRhc2V0IjoiY29uc28tZGVwYXJ0ZW1lbnQtYW5udWVsbGUiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLmxpYmVsbGVfcmVnaW9uIjp0cnVlLCJkaXNqdW5jdGl2ZS5saWJlbGxlX2RlcGFydGVtZW50Ijp0cnVlLCJkaXNqdW5jdGl2ZS5nX29wZXJhdGV1cnMiOnRydWUsImRpc2p1bmN0aXZlLmVfb3BlcmF0ZXVycyI6dHJ1ZX19fV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9&location=3,18.52732,-2.98469&basemap=jawg.light

https://odre.opendatasoft.com/explore/embed/dataset/conso-epci-annuelle/table/?disjunctive.e_operateurs&disjunctive.g_operateurs&disjunctive.libelle_epci&disjunctive.libelle_departements&disjunctive.libelle_regions&sort=-annee

# Méthodologie
## 🧹 Prétraitement (Python)
🧼 Nettoyage des données brutes
‣ Traitement des valeurs nulles, renommage des colonnes, uniformisation des formats
📅 Filtrage temporel
‣ Sélection des données de l’année la plus récente
💾 Export des jeux de données nettoyés
df_dept_nettoye.csv
df_epci_nettoye.csv

## 📊 Calcul des Indicateurs (Python)
🧮 Indice de flexibilité
‣ (Conso Industrie + Conso Tertiaire) / Conso Totale
🔌 Ratio de dépendance énergétique
‣ Conso Gaz / Conso Électricité
🎯 Score d’opportunité
‣ Indice de flexibilité × Ratio de dépendance

## 🌍 Visualisation (Power BI)
🗺️ Cartographie des départements
‣ Affichage du score de flexibilité par zone
🧩 Cartographie EPCI
‣ Bulles proportionnelles selon les indicateurs
📈 Scatter plots
‣ Relation flexibilité vs dépendance
📊 Tableaux de classement dynamiques
‣ Hiérarchisation des zones selon les scores
🎚️ Filtres interactifs
‣ Régionaux et thématiques pour affiner l’analyse

## 🖼️ Aperçu Visuel 
![image](https://github.com/user-attachments/assets/61738966-5559-4c51-ab7d-28072bc8afa5)
![image](https://github.com/user-attachments/assets/ec9c4551-945b-47cf-9f2e-26b505486de7)

# 🏁 Résultats Clés 
Potentiel élevé identifié dans le Grand Est et les Hauts-de-France
Détection de zones mono-dépendantes (ex : Meuse, Aube)
Top 10 des zones prioritaires pour déploiement d’effacement énergétique
Dashboard interactif conçu pour les décideurs locaux et énergéticiens

# 💡 Recommandations 
Déployer des dispositifs de flexibilité dans les zones prioritaires
Renforcer le pilotage énergétique dans les territoires mono-dépendants
Mettre à disposition des collectivités des outils d’analyse visuelle
Favoriser les synergies entre industriels et gestionnaires de réseau


# ℹ️ À propos 
Data Analyst certifiée en Python, SQL, Power BI et Excel, avec un doctorat en géographie et 15 ans d’expérience en analyse de données.
Je transforme des données brutes en insights clairs et actionnables, quel que soit le secteur.
Spécialisée en nettoyage, visualisation, reporting et Machine Learning, je suis disponible pour des projets data, en présentiel ou en remote.
📩 baubebet.sandrine@yahoo.fr
