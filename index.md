# Réécriture du fichier index.md avec correction de chemins relatifs clairs
index_content_fixed = """
# 🌍 Climat-France-Europe-1970–2024

Bienvenue sur cette page de présentation du projet TP3 sur l’impact du changement climatique en France.

## 📁 Données disponibles
- [📄 Jeu de données fusionné (CSV)](/TP3-CLIMAT-OPEN-DATA/data/donnees_fusionnees_france.csv)
- [📓 Notebook Jupyter phase par phase avec les visualisations](TP3-CLIMAT-OPEN-DATA)


## 📚 Objectif
Ce projet vise à étudier les corrélations entre les anomalies de température et les catastrophes naturelles en France, à travers un traitement exploratoire, spatial et prédictif des données ouvertes.

## 🧠 Méthodologie
- Données : Berkeley Earth + EM-DAT
- Fusion annuelle sur la période 1970–2024
- Analyse statistique et corrélation
- Scénarios prospectifs et solutions proposées

## 🔎 Fiche technique
- Format : CSV, HTML, Notebook
- Licence : ODC-BY
- Auteur : Jennifer AWOUNOU – ESAIP

> Pour plus de détails, consultez la [fiche de métadonnées](/TP3-CLIMAT-OPEN-DATA/Metadonne.md)
"""

# Sauvegarde du nouveau fichier corrigé
index_fixed_path = "/TP3-CLIMAT-OPEN-DATA/index.md"
with open(index_fixed_path, "w") as f:
    f.write(index_content_fixed)

index_fixed_path
