# Heart Disease Data: Exploratory Visualisation

Exploratory analysis of a heart-disease dataset (`heart.csv`) to see which clinical factors relate to the presence of heart disease.

## What's covered

1. **Understanding the data:** structure, data types and summary statistics
2. **Outlier detection:** box plots with highlighted outliers for cholesterol, ST depression, number of coloured vessels and thalassemia
3. **Distributions:** count plots of patients by age, for the full dataset and a focused subset
4. **Heart disease vs. features:** how the presence of heart disease (`target`) is distributed across patient groups
5. **Correlations:** a feature-correlation heatmap, refined after cleaning

## Tech stack

Python, pandas, NumPy, Matplotlib, Seaborn

## How to run

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Data_Visualization_Assignment.ipynb
```

Place `heart.csv` in the same folder as the notebook.
