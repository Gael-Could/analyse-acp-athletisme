# Analyse-ACP-Athletisme
Contexte et Objectif de l'Étude : Cette ACP porte sur 55 pays et 8 épreuves d'athlétisme (100m, 200m, 400m, 800m, 1500m, 5000m, 10000m, Marathon). L'objectif est d'identifier les profils de performance des pays et les relations entre disciplines.

# Analyse en Composantes Principales - Records Athlétiques

## 📊 Description
Analyse statistique des records mondiaux d'athlétisme de 55 pays sur 8 épreuves (100m, 200m, 400m, 800m, 1500m, 5000m, 10000m, Marathon).

## 🎯 Objectif
Identifier les profils de performance des pays et les relations entre disciplines.

## 📁 Structure du Projet

### Données
- `data/track.csv` : Dataset des records par pays

### Analyses
- **R** (`R/`) : 
  - `analyse_acp.R` : Script principal
  - `analyse_acp.Rmd` : Rapport R Markdown
  
- **Python** (`python/`) :

### Résultats
- `output/figures/` : Graphiques (éboulis, cercle des corrélations, biplot)
- `output/tables/` : Tableaux de résultats

## 🔑 Résultats Principaux
- **Dim1** : 82,78% de variance (performance globale)
- **Dim2** : 10,97% de variance (spécialisation sprint/endurance)
- **Total** : 93,75% de variance expliquée

## 🛠️ Technologies Utilisées
- **R** : FactoMineR, factoextra, ggplot2
- **Python** : sklearn, pandas, matplotlib, seaborn

## 🚀 Utilisation

### Version R
```r
# Ouvrir le projet RStudio
# Installer les packages
install.packages(c("FactoMineR", "factoextra", "corrplot"))

# Exécuter l'analyse
source("R/analyse_acp.R")
```

### Version Python
```bash
# Installer les dépendances
pip install -r requirements.txt

# Lancer Jupyter
jupyter notebook python/analyse_acp.ipynb
```

## 👤 Auteur
Gael Kibiti - Université de Lille

## 📅 Date
Novembre 2025
```
