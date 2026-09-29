# 🛒 Olist — Segmentation clients e-commerce

> Segmentation non supervisée des clients d'une marketplace brésilienne pour personnaliser les actions marketing et améliorer la connaissance client.

---

## 🎯 Contexte

Olist est une solution brésilienne de vente sur les marketplaces en ligne. Face à une base clients hétérogène, l'enjeu est d'identifier des **segments d'utilisateurs homogènes** pour adapter les stratégies de communication et de fidélisation à chaque profil.

---

## ⚙️ Ce que fait le projet

- **Analyse exploratoire** — compréhension des comportements d'achat, distribution des variables, détection d'anomalies
- **Feature engineering** — construction de variables RFM (Récence, Fréquence, Montant) et comportementales
- **Modélisation non supervisée** — comparaison de plusieurs algorithmes de clustering
- **Simulation de stabilité** — estimation de la fréquence optimale de mise à jour du modèle pour maintenir sa pertinence dans le temps

---

## 🔍 Approches de clustering comparées

| Algorithme | Particularité |
|------------|--------------|
| K-Means | Référence, rapide, sensible aux outliers |
| DBSCAN | Détection de clusters de forme libre |
| CAH (Clustering Agglomératif) | Analyse hiérarchique |

---

## 🛠️ Stack

`Python` `Scikit-learn` `Pandas` `Matplotlib` `Seaborn` `Plotly` `K-Means` `DBSCAN` `CAH` `t-SNE` `UMAP`

---

## 📁 Structure du projet

```
├── notebooks/
│   ├── 01_exploration.ipynb          # Analyse exploratoire
│   ├── 02_modelisation.ipynb         # Essais de clustering
│   └── 03_simulation_stabilite.ipynb # Fréquence de mise à jour
└── README.md
```

---

## 📂 Données

Dataset public Olist — [Brazilian E-Commerce sur Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Plus de 100 000 commandes entre 2016 et 2018, avec informations clients, produits, paiements et avis.
