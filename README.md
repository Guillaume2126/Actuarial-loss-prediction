# Actuarial-loss-prediction

Ce projet a pour objectif de prédire le coût final d’un sinistre (Ultimate Incurred Claim Cost) à partir de données d’assurance liées aux accidents du travail. Le challenge initial est le suivant: https://www.kaggle.com/competitions/actuarial-loss-estimation/overview

Le pipeline complet comprend :

Analyse exploratoire des données (EDA)
Nettoyage et pré-processing
Feature engineering
Entraînement et comparaison de plusieurs modèles de Machine Learning

```project/
│
├── notebooks/
│   ├── 1.Data_visualization_and_analysis.ipynb
│   ├── 2.Data_cleaning_and_processing.ipynb
│   └── 3.Entrainement du modèle.ipynb
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── sample_submission.csv
│   ├── X_train.npz
│   ├── X_test.npz
│   ├── y_train.csv
│   └── lgb_submission.csv -> Output
│
├── requirements.txt
└── README.md```

## Installation des dépendances

pip install -r requirements.txt
