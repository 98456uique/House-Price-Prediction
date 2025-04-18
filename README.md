
# Boston Housing Price Prediction

This project predicts housing prices in Boston using machine learning (Linear Regression). It includes detailed data preprocessing, visualizations, model training, and evaluation. The goal is to build an interpretable and accurate model using the *Boston Housing Dataset*.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Libraries Used](#libraries-used)
- [Workflow](#workflow)
- [Data Visualization](#data-visualization)
- [Model Training & Evaluation](#model-training--evaluation)
- [Results](#results)
---

## Project Overview

Housing prices are influenced by a variety of features such as the number of rooms, crime rate, accessibility to highways, and more. This project uses *Linear Regression* to predict the *Median Value of Owner-Occupied Homes (MEDV)* in $1000s.

---

## Dataset Information

The dataset includes 506 rows and 14 columns. Each row represents a town in Boston, and each column is a feature influencing house prices.

Key features include:

- CRIM: Crime rate
- RM: Average number of rooms per dwelling
- LSTAT: % lower status of the population
- PTRATIO: Pupil-teacher ratio
- CHAS: Bounded by the Charles River (categorical)
- MEDV: Median home value (target variable)

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Workflow

1. *Load and Explore Dataset*
2. *Preprocess Data*
   - Handle missing values
   - Remove duplicates
   - Convert categorical features
   - Feature scaling using StandardScaler
3. *Data Visualization*
   - Histograms
   - Boxplots
   - Scatterplots
   - Correlation heatmap
4. *Train-Test Split* (80/20)
5. *Model Training* using Linear Regression
6. *Model Evaluation*
   - RMSE
   - R² Score
7. *Visualize Predictions*

---

## Data Visualization

- *Histogram*: Understand distribution of each feature
- *Boxplot*: Detect outliers
- *Correlation Heatmap*: Identify relationships between features
- *Scatterplots*: Show how features like RM and LSTAT relate to MEDV
- *Actual vs Predicted Plot*: Evaluate model accuracy visually

---

## Model Training & Evaluation

- *Model*: LinearRegression() from Scikit-learn
- *Train/Test Split*: 80/20
- *Evaluation Metrics*:
  - *Root Mean Squared Error (RMSE)*: Measures prediction error
  - *R² Score*: Measures how well the model fits the data

---

## Results

- The model performs well with a decent R² score.
- Visualizations show that features like RM, LSTAT, and PTRATIO are strong indicators of house prices.
- Prediction vs Actual plot shows a good linear fit.

---

