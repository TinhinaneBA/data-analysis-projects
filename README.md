# Data Analysis Projects 📊

A collection of data analysis projects built while learning
Python, Pandas, and data visualization.

**Tools & libraries**
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter`

---

## Projects

### 🚢 Titanic — Survival Analysis
Exploratory data analysis on the Titanic dataset.
Who survived ? Why ? Insights by sex, class and age.

| Notebook | Description | Status |
|---|---|---|
| `02_titanic_pandas.ipynb` | Data loading, exploration, survival analysis | ✅ Done |

**Key findings :**
- Taux de survie global : 38.4%
- Femmes : 74% de survie · Hommes : 19%
- 1ère classe : 63% · 2ème : 47% · 3ème : 24%
- Enfants prioritaires sur les adultes
- Pire profil : homme en 3ème classe (~13%)

---

### 🧹 Data Cleaning — Pandas Techniques
Nettoyage complet d'un dataset "sale" avec Pandas.

| Notebook | Description | Status |
|---|---|---|
| `03_data_cleaning.ipynb` | Doublons, valeurs manquantes, types, formats | ✅ Done |

**Techniques appliquées :**
- `drop_duplicates()` · `dropna()` · `fillna()`
- `pd.to_numeric(errors='coerce')`
- `str.capitalize()` · `str.contains()`
- Filtrage par plage : `between()`

---

### 📊 Seaborn Visualizations
Visualisations avancées avec Seaborn sur le dataset Titanic.

| Notebook | Description | Status |
|---|---|---|
| `04_seaborn_viz.ipynb` | Heatmap, boxplot, violinplot, pairplot | ✅ Done |

**Graphiques produits :**
- `heatmap` — matrice de corrélation entre variables numériques
- `boxplot` — distribution de l'âge par classe
- `violinplot` — distribution âge/classe selon la survie
- `countplot` — survivants vs décédés par classe
- `pairplot` — relations entre toutes les variables

**Key insights :**
- Fare et Pclass sont les variables les plus corrélées à la survie
- Les jeunes de 3ème classe (~22 ans) ont le taux de décès le plus élevé
- L'âge seul influence peu la survie — c'est la combinaison classe + sexe qui compte
---

## Structure
```
data-analysis-projects/
├── titanic-eda/
│   ├── data/titanic.csv
│   └── notebooks/02_titanic_pandas.ipynb
├── data-cleaning/
│   └── notebooks/03_data_cleaning.ipynb
└── seaborn-visualizations/ *(coming soon)*
```

---
*Updated regularly as I progress — open to collaboration !*