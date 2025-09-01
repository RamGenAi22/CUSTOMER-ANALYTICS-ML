# Customer Analytics & Prediction Suite (Telco Dataset)

An end-to-end ML project covering Regression, Classification, and Clustering on the Telco Churn dataset.

## Features
- EDA & Preprocessing
- Regression: Ridge Regression to predict MonthlyCharges
- Classification: Random Forest (GridSearchCV tuned) to predict Churn
- Clustering: KMeans + PCA for customer segmentation
- Visualizations: correlation heatmap, ROC curve, confusion matrix, cluster plots

## Results
- Regression: R² = 0.998
- Classification: ROC AUC = 0.842
- Clustering: 4 distinct customer segments

## How to Run
1. Place dataset in `data/raw/`
2. Run notebooks in order (01 → 04)
3. Results stored in `reports/` and trained models in `models/`

## Tech Stack
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn