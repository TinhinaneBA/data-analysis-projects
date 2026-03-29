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

### 📊 Seaborn Visualizations *(coming soon)*
Visualisations avancées avec Seaborn.

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