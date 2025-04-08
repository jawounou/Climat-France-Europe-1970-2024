
metadata_content = """
# Fiche de métadonnées

## Titre
Évolution climatique France-Europe 1970–2024

## Sources
- Berkeley Earth
- EM-DAT (Emergency Events Database)
- NOAA, Copernicus

## Description
Données climatiques fusionnées à l’échelle annuelle sur la période 1970–2024. Le jeu croise des anomalies de température (France) avec des données de catastrophes naturelles (France uniquement).

## Variables
- Year
- Monthly_Anomaly
- Disaster_Count
- Total_Deaths
- Total_Damage

## Fréquence
Annuelle

## Couverture géographique
France

## Licence
Open Data Commons Attribution (ODC-BY)

## Formats disponibles
- CSV
- Notebook (.ipynb)
- Visualisations (PNG, HTML)

## Date de création
Avril 2025

Jennifer AWOUNOU (ESAIP - TP Données Ouvertes)

"""

with open("/mnt/data/metadata.md", "w") as f:
    f.write(metadata_content)

