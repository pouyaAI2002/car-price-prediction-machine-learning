# Car Price Prediction Using Machine Learning

This project focuses on predicting car prices using machine learning techniques.

## Project Overview

The goal of this project is to explore a car dataset, analyze the relationships between vehicle characteristics and price, preprocess the data, and build a machine learning model for car price prediction.

A Random Forest Regression model is used to predict car prices based on the available vehicle features.

## Objectives

- Explore and understand the dataset
- Perform exploratory data analysis (EDA)
- Preprocess numerical and categorical features
- Train a Random Forest Regression model
- Evaluate model performance
- Analyze feature importance
- Check model generalization and residuals

## Dataset

The dataset contains information about different cars and their characteristics, including features such as:

- Engine size
- Curb weight
- Horsepower
- Car width
- Car length
- Highway MPG
- City MPG
- And other vehicle specifications

The target variable is:

`price`

## Methodology

The project follows these main steps:

1. Data Loading and Inspection
2. Exploratory Data Analysis
3. Data Preprocessing
4. Random Forest Regression
5. Model Evaluation
6. Feature Importance Analysis
7. Conclusion

## Model

The main machine learning algorithm used in this project is:

**Random Forest Regressor**

The model is evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Results

The Random Forest model achieved a test R² score of approximately **0.94**, indicating strong predictive performance on the test dataset.

Feature importance analysis showed that **engine size (`enginesize`)** and **curb weight (`curbweight`)** were among the most influential features used by the model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Structure

```text
car-price-prediction/
│
├── Car_Price_Prediction.ipynb
├── CarPrice_Assignment.csv
├── README.md
│
└── images/