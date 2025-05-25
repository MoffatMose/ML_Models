# House Rent Prediction Model

This project showcases a complete machine learning workflow for predicting house rental prices using real-world data.

## Problem Overview

The notebook addresses the challenge of accurately predicting house rent, considering factors such as:
- Size of the house
- Number of bedrooms (BHK)
- Number of bathrooms
- Location and locality
- Furnishing status
- Preferred tenant type

## Dataset

- **Source:** [Kaggle House Rent Prediction Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset)
- **Description:** Contains over 4,700 records of rental listings from various cities in India.

## Data Processing

- Comprehensive data cleaning confirms there are no missing or duplicate values.
- Exploratory analysis is performed to understand feature distributions and relationships.

## Feature Engineering

- Categorical variables (e.g., city, area type, furnishing status) are encoded numerically using label encoding for modeling efficiency and to avoid high dimensionality.

## Exploratory Data Analysis

- Visualizations (scatter plots) illustrate the relationships between rent prices and different features (size, BHK, bathrooms, etc.), highlighting influential factors.

## Model Development

- Multiple regression models are implemented, including Linear Regression, Decision Tree Regressor, XGboost regressor, Gradient Boosting Regressor and Random Forest.
- Pipeline includes train-test split, feature scaling, and model evaluation.

## Model Evaluation

- Uses standard evaluation metrics Mean Squared Error (MSE) and R² score for performance assessment.

## Summary

The notebook demonstrates end-to-end data science skills in data cleaning, feature engineering, visualization, and supervised machine learning applied to real estate price prediction.

**Notebook:** [`machine-learning-model-to-predict-house-rent.ipynb`](machine-learning-model-to-predict-house-rent.ipynb)
