# Gold Price Prediction 

## Overview
A Machine Learning project that predicts gold prices using 
correlated stock market indicators. Built using Random Forest 
Regressor achieving an R-squared score of 0.98.

## Dataset
- Source: Kaggle
- Time Period: 2008-2018
- Size: 2290 rows, 6 columns
- Features: SPX, USO, SLV, EUR/USD, GLD (target)

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest Regressor)

## Workflow
1. Data Collection & Loading
2. Exploratory Data Analysis (EDA)
3. Correlation Heatmap Analysis
4. Train-Test Split (80-20)
5. Model Training (100 estimators)
6. Evaluation (R² Score)
7. Actual vs Predicted Visualization

## Results
- R-squared Score: **0.98**
- Strong positive correlation between GLD and SLV: **0.9**

## Key Findings
- Gold and Silver prices are strongly correlated (0.9)
- Gold and USO slightly negatively correlated
- Most gold prices concentrated around $120
