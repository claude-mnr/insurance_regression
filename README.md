# 📊 Prédiction des frais médicaux — Régression Linéaire

Ce projet a pour objectif de prédire les frais d’assurance médicale à l’aide d’un modèle de **régression linéaire**, basé sur des données démographiques et médicales. Il a été réalisé dans le cadre de ma montée en compétences en Data Science.

## 📁 Données utilisées

- Source : [Kaggle - Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Variables :
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

## ⚙️ Méthodologie

1. **Nettoyage des données**
   - Encodage des variables catégorielles (`sex`, `smoker`, `region`)
   - Détection et traitement des valeurs manquantes (aucune ici)

2. **Exploration des données (EDA)**
   - Analyse de la distribution des variables
   - Visualisation des corrélations

3. **Modélisation**
   - Régression linéaire avec `scikit-learn`
   - Séparation en `X_train` / `X_test`
   - Évaluation via :
     - **MSE** (Mean Squared Error)
     - **MAE** (Mean Absolute Error)
     - **R² Score**

4. **Résultats**
   - MSE = `33 596 915.85`
   - MAE = `4 181.19`
   - R² = `0.7835`

## 🖼️ Visualisations
- Corrélation entre variables
- Répartition des charges
- Comparaison des prédictions et valeurs réelles

## 🧰 Librairies utilisées
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## 🚀 Résumé
Ce projet démontre ma capacité à :
- Analyser un jeu de données
- Construire un pipeline de régression linéaire
- Évaluer et interpréter un modèle
- Visualiser les résultats de manière claire

## 🧠 Auteur
Réalisé par [Claude MOUNIROU] — Apprenant Data Scientist
