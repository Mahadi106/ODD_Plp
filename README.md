# ODD_Plp IA pour le developpement durable
 
## Objectif du projet

Ce projet s’inscrit dans le cadre de l’**Objectif de Développement Durable (ODD) 13 – Action pour le climat** des Nations Unies. Il vise à concevoir un modèle d’apprentissage automatique capable de **prédire les émissions de CO₂** à partir de données ouvertes (énergie, PIB, population, etc.). L’objectif est d’aider les décideurs à anticiper les impacts climatiques et à élaborer des politiques plus durables.

 ## Approche ML

- *Type d’apprentissage* : Apprentissage supervisé
- *Algorithmes envisagés* : Régression linéaire, forêt aléatoire, XGBoost
- *Objectif du modèle* : Prédire une variable continue (émissions de CO₂)

  ## Données utilisées

Le fichier principal utilisé dans ce projet est `co2_plp.csv`, situé dans le dossier `data/`.  
Il contient des données sur :

- Les émissions de CO₂ par pays et par année

Ces données ont été extraites et nettoyées pour servir de base à l’entraînement d’un modèle de régression.  
 
[Voir le fichier co2_plp.csv](data/co2_plp.csv)
Ces variables permettent d’entraîner un modèle de régression pour prédire les émissions de CO₂, dans le cadre de l’Objectif de Développement Durable (ODD) 13 : 
**Action pour le climat**.

Le fichier est stocké dans le dossier `data/` du dépôt GitHub.

## Outils et technologies

- *Langage* : Python  
- *Librairies* : Pandas, Scikit-learn, Matplotlib, Seaborn  
- *Plateforme* : Google Colab  
- *Optionnel* : Streamlit pour une démo interactive

  ## Structure du projet

ODD_Plp/
│
├── data/                  # Données brutes et nettoyées  
├── notebooks/             # Notebook principal : carbon_plp.ipynb  
├── scripts/               # Scripts Python (.py)  
├── images/                # Graphiques et visualisations  
├── README.md              # Ce fichier  
└── requirements.txt       # Librairies nécessaires

## Réflexion éthique

Le projet prendra en compte les biais potentiels liés aux données incomplètes ou inégales entre pays. Une attention particulière sera portée à la transparence, à l’équité et à l’impact social du modèle.

 ## Modèle entraîné

Le modèle de régression linéaire a été entraîné avec succès pour prédire les émissions de CO₂.  
Le modèle entraîné est stocké dans `scripts/carbon_model.pkl`.  
Il peut être rechargé pour effectuer des prédictions sans réentraîner le modèle.

 ## Évaluation du modèle

- *MSE* : 46 324.67  
- *R²* : 0.859

Le modèle explique environ **86% de la variance** des émissions de CO₂, ce qui montre une bonne capacité prédictive.  
L’erreur quadratique moyenne indique que les écarts entre les prédictions et les valeurs réelles restent raisonnables à l’échelle globale.

## Visualisations :
Des graphiques ont été générés pour comparer les prédictions aux valeurs réelles et analyser les erreurs.

## Notebook principal

Le notebook `carbon_plp.ipynb` contient tout le code d’entraînement, d’évaluation et de visualisation du modèle.  
[Voir le notebook](notebooks/carbon_plp.ipynb)


## Auteur

Mahadi – PLP Academy | Projet IA pour le développement durable 🌱 
