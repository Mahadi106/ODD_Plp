# ODD_Plp IA pour le developpement durable
 
## Objectif du projet

Ce projet s’inscrit dans le cadre de l’**Objectif de Développement Durable (ODD) 13 – Action pour le climat** des Nations Unies. Il vise à concevoir un modèle d’apprentissage automatique capable de **prédire les émissions de CO₂** à partir de données ouvertes (énergie, PIB, population, etc.). L’objectif est d’aider les décideurs à anticiper les impacts climatiques et à élaborer des politiques plus durables.

 ## Approche ML

- *Type d’apprentissage* : Apprentissage supervisé
- *Algorithmes envisagés* : Régression linéaire, forêt aléatoire, XGBoost
- *Objectif du modèle* : Prédire une variable continue (émissions de CO₂)

## Données utilisées

Les données seront extraites de sources ouvertes telles que :
- [Banque mondiale – Indicateurs climatiques](https://databank.worldbank.org/source/climate-data)
- [Base ODD de l’ONU](https://unstats.un.org/sdgs)
- [Kaggle – CO₂ Emissions Dataset](https://www.kaggle.com/datasets)

## Outils et technologies

- *Langage* : Python  
- *Librairies* : Pandas, Scikit-learn, Matplotlib, Seaborn  
- *Plateforme* : Google Colab  
- *Optionnel* : Streamlit pour une démo interactive

## Structure du projet

 
ODD_Plp/ │ ├── data/                  # Données brutes et nettoyées ├── notebooks/             # Notebook principal (Colab ou Jupyter) ├── scripts/               # Scripts Python (.py) ├── images/                # Graphiques et visualisations ├── README.md              # Ce fichier └── requirements.txt       # Librairies nécessaires
 
## Réflexion éthique

Le projet prendra en compte les biais potentiels liés aux données incomplètes ou inégales entre pays. Une attention particulière sera portée à la transparence, à l’équité et à l’impact social du modèle.

## Auteur

Mahadi – PLP Academy | Projet IA pour le développement durable 🌱 
