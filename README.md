# Python Campaign Performance Modeling

This project applies regression modeling to campaign performance data to predict conversions based on paid media metrics. The goal is to explore how campaign variables relate to conversion outcomes and evaluate whether machine learning models can support performance analysis and optimization decisions.

## Project Objective

The main objective of this project is to build and evaluate regression models that predict campaign conversions using historical performance data.

This project focuses on:

- Cleaning and preparing campaign performance data
- Exploring key performance metrics
- Treating missing values and outliers
- Building regression models
- Comparing model performance
- Generating conversion predictions from new input values

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Dataset

The project uses campaign performance data with metrics related to paid media performance. The dataset includes variables such as campaign metrics, cost-related fields, and conversion outcomes.

Sensitive or client-specific information should be removed before sharing publicly.

## Workflow

### 1. Data Loading

The dataset is loaded into the notebook and inspected to understand available columns, data types, and missing values.

### 2. Data Cleaning

The data preparation process includes:

- Removing irrelevant columns
- Cleaning numeric fields
- Handling missing values
- Removing duplicate rows
- Converting variables to numeric format
- Preparing the dataset for modeling

### 3. Exploratory Data Analysis

Exploratory analysis is used to better understand the distribution of campaign metrics and identify potential outliers.

Visualizations include:

- Histograms
- Boxplots
- Distribution checks

### 4. Outlier Treatment

Outliers are reviewed and treated where appropriate using statistical methods such as the interquartile range (IQR).

### 5. Model Development

The project tests multiple regression models:

- Linear Regression
- Ridge Regression
- Lasso Regression

### 6. Model Evaluation

Models are evaluated using regression performance metrics such as:

- Mean Squared Error (MSE)
- R-squared (R²)

### 7. Prediction

The notebook includes a prediction step where new input values can be used to estimate expected conversions.

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Regression modeling
- Feature preparation
- Outlier detection
- Model evaluation
- Campaign performance analysis
- Applied machine learning for marketing analytics

## Project Value

This project demonstrates how machine learning can be applied to campaign performance data to identify patterns, estimate conversion outcomes, and support more data-driven optimization decisions.

## Notes

This project is intended for learning and portfolio purposes. Results depend on dataset quality, available variables, and model assumptions.
