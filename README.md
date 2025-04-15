# Data-Mining

# AI-Powered Movie Recommendation System

This repository contains an end-to-end machine learning pipeline that leverages various models to predict IMDb ratings and uncover insightful patterns within a movie dataset. The system is built to analyze movie metadata and generate intelligent recommendations based on user interactions and preferences.

---

## Project Structure

- `AI-Powered Movie Recommendation.py`: The complete pipeline from preprocessing to model evaluation and visualization.
- `Preprocessed Dataset.xlsx`: Dataset used after data cleaning and transformation.

---

## Features

- Data Cleaning & Preprocessing: Missing values handling, feature transformation, and normalization.
- Model Training: Linear Regression, Random Forest, XGBoost, LightGBM, and Neural Networks (MLP).
- Feature Engineering: Custom features such as movie age, language encoding, and interaction terms.
- Model Evaluation: MSE, R², cross-validation, and visual diagnostics (residuals, correlation heatmaps).
- Feature Importance Analysis: Across multiple models to identify the most influential factors.
- Visualizations: Boxplots, scatter plots, bar charts, and heatmaps for data insights.

---

## Highlights

- Multiple model comparisons on IMDb score prediction
- Permutation and tree-based feature importances
- Residual and correlation analysis for interpretability
- Scalable and extensible ML pipeline

---

## Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, LightGBM, TensorFlow/Keras
