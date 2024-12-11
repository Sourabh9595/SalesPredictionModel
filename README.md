# SalesPredictionModel
A machine learning framework for predicting sales at potential store locations using demographic, competition, and store data. Combines PCA for feature reduction and Random Forest for prediction. Includes data preprocessing, model tuning, and visualizations to assist in strategic retail site selection and decision-making.
# Sales Prediction for Store Development

This repository contains a machine learning framework for predicting sales at potential store locations. The project uses PCA for feature selection and Random Forest for robust sales forecasting. It includes analysis of demographic data, competition distances, and store-specific features.

## Features
- **Demographic Analysis**: Incorporates data on population, income, housing, and more.
- **Competitive Insights**: Computes the distance to nearest competitors.
- **Feature Reduction**: Utilizes Principal Component Analysis (PCA) to reduce feature dimensions.
- **Modeling Techniques**: Implements Random Forest, XGBoost, and Linear Regression for predictions.
- **Visualization**: Offers insights through heatmaps, scatter plots, and histograms.

## Workflow
1. **Data Preprocessing**:
   - Handles missing values and scales features.
   - Calculates distances to competitors using geospatial data.
2. **Feature Selection**:
   - Applies PCA to retain 95% of variance with reduced dimensions.
3. **Model Training and Tuning**:
   - Trains models with cross-validation.
   - Performs hyperparameter tuning for Random Forest.
4. **Sales Prediction**:
   - Predicts sales for potential sites and saves results to CSV.
5. **Visualization**:
   - Displays insights like feature importance and sales distribution.

## Requirements
- Python 3.7 or above
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn, geopy, xgboost
