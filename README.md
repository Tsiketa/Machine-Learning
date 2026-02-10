# 🤖 Machine Learning Projects

> Projets d'analyse de données et de Machine Learning réalisés dans le cadre de ma formation **ESIIA 4**.

---

## 👤 Auteur

| Champ | Info |
|-------|------|
| **Nom** | RAHARISON |
| **Prénom(s)** | Santatriniaina Tiantsoa |
| **Classe** | ESIIA 4 |

---

## 📁 Structure du Repository

```
machine-learning/
│
├── california-housing/
│   ├── pratique.ipynb
│   ├── resultats_regression.csv
│   
│
└── README.md
```

---

## 📊 Projet 1 — California Housing (Régression Linéaire)

### 🎯 Objectif
Prédire le **prix médian des logements en Californie** à partir de caractéristiques géographiques et démographiques.

### 📂 Dataset
- **Source** : `sklearn.datasets.fetch_california_housing`
- **Taille** : 20 640 observations × 9 variables
- **Variable cible** : `MedHouseVal` (prix médian en centaines de milliers de $)

### 🔧 Workflow
| Étape | Description |
|-------|-------------|
| 1 | Chargement et inspection des données |
| 2 | Nettoyage et suppression des outliers |
| 3 | Analyse exploratoire (EDA) |
| 4 | Ingénierie des variables |
| 5 | Séparation entraînement / test (80/20) |
| 6 | Construction du modèle de régression linéaire |
| 7 | Prédiction et évaluation |
| 8 | Visualisation des résultats |
| 9 | Export des résultats en CSV |
| 10 | Analyse et recommandations |

### 📈 Résultats

| Métrique | Valeur |
|----------|--------|
| **MSE** | 0.4560 |
| **RMSE** | 0.6753 |
| **MAE** | 0.4904 |
| **R²** | 0.6483 |

> ✅ Le modèle explique **64.83%** de la variance des prix avec une erreur moyenne de **~67 530 $**.

### 🛠️ Technologies utilisées

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-DataFrame-lightgrey?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualisation-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-teal)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)

### ▶️ Lancer le projet

1. Ouvrir le fichier `pratique.ipynb` sur [Google Colab](https://colab.research.google.com)
2. Exécuter toutes les cellules : `Exécution → Tout exécuter`

---

## 🚀 Projets à venir

- [ ] Classification (Logistic Regression)
- [ ] Arbre de décision (Decision Tree)
- [ ] Random Forest
- [ ] Deep Learning (Neural Networks)

---

## 📄 Licence

Ce repository est à usage éducatif dans le cadre de la formation ESIIA 4.
