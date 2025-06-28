# Analyse énergétique: 
# Cartographie des Territoires à Potentiel de Flexibilité Énergétique
Ce projet, réalisé par l’équipe Data de FlexiMap Solutions (entreprise fictive créée dans lecadre de ce projet final de formation), vise à identifier les territoires en France métropolitaine où des actions de flexibilité énergétique (effacement, pilotage de la consommation) peuvent être stratégiquement déployées. Il combine analyse de données open-source, modélisation d'indicateurs de flexibilité et visualisation interactive.

# Objectifs du projet
Identifier les zones à forte consommation pilotable (secteurs tertiaire et industriel).

Calculer un indice de flexibilité croisant consommation et dépendance énergétique.

Visualiser ces zones sur une cartographie interactive à des fins d’aide à la décision.

# Outils utilisés
Python (Pandas, NumPy, Matplotlib)

Power BI pour la visualisation interactive

Jupyter Notebooks pour la documentation de l’analyse

# Jeux de données
Sources :

data.gouv.fr

opendata.reseaux-energies.fr

Fichiers :

conso-departement-annuelle.csv

conso-epci-annuelle.csv

# Méthodologie
## Prétraitement (Python)
Nettoyage des données brutes : valeurs nulles, renommage, uniformisation

Filtrage sur l’année la plus récente

Export des jeux nettoyés :

df_dept_nettoye.csv

df_epci_nettoye.csv

## Calcul des indicateurs (Python)
Indice de flexibilité : (Conso Industrie + Tertiaire) / Conso Totale

Ratio de dépendance : Conso Gaz / Conso Élec

Score d’opportunité : Indice de flexibilité × Ratio de dépendance

## Visualisation (Power BI)
Carte des départements (score de flexibilité)

Carte EPCI (bulles)

Scatter plots : flexibilité vs dépendance

Tableaux de classement dynamiques

Filtres régionaux et thématiques

## Aperçu visuel 
![image](https://github.com/user-attachments/assets/61738966-5559-4c51-ab7d-28072bc8afa5)
![image](https://github.com/user-attachments/assets/ec9c4551-945b-47cf-9f2e-26b505486de7)

# Résultats clés
Potentiel élevé identifié dans le Grand Est et les Hauts-de-France

Détection de zones mono-dépendantes (ex : Meuse, Aube)

Top 10 des zones prioritaires pour déploiement d’effacement énergétique

Dashboard interactif conçu pour les décideurs locaux et énergéticiens

# Recommandations
Déployer des dispositifs de flexibilité dans les zones prioritaires

Renforcer le pilotage énergétique dans les territoires mono-dépendants

Mettre à disposition des collectivités des outils d’analyse visuelle

Favoriser les synergies entre industriels et gestionnaires de réseau


# À propos
Data Analyst certifiée en Python, SQL, Power BI et Excel, avec un doctorat en géographie et 15 ans d’expérience en analyse de données.
Je transforme des données brutes en insights clairs et actionnables, quel que soit le secteur.
Spécialisée en nettoyage, visualisation, reporting et Machine Learning, je suis disponible pour des projets data, en présentiel ou en remote.
📩 baubebet.sandrine@yahoo.fr
