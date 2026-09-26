# ✈️ Flight Fare Analysis & Prediction

## 📌 Overview

This project focuses on analyzing flight fare data and developing
machine learning models to predict flight ticket prices.

The project includes data preprocessing, exploratory data analysis,
feature engineering, model development, and hyperparameter tuning.

## 🎯 Objectives

- Analyze factors affecting flight ticket prices
- Perform data preprocessing and cleaning
- Explore relationships between flight attributes and fares
- Perform feature engineering
- Build and compare multiple regression models
- Improve model performance through feature engineering and tuning

## 📊 Dataset

Flight Fare Dataset

Dataset source: 
[Kaggle - Flight Fare Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

## Dataset Overview

The dataset contains information about airlines, journey dates,
routes, duration, stops, additional information, and flight prices.

![Dataset Information](images/Information%20Regarding%20Dataset.png)

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🔄 Project Workflow

1. Dataset inspection
2. Missing-value detection
3. Duplicate-value detection
4. Data preprocessing
5. Outlier detection and removal
6. Exploratory Data Analysis
7. Feature encoding
8. Feature engineering
9. Model training
10. Hyperparameter tuning
11. Model comparison

## 🤖 Machine Learning Models

- Linear Regression
- Decision Tree Regression
- KNN Regression
- Random Forest Regression
- XGBoost Regression

## 📈 Feature Engineering

Feature engineering was performed to improve model performance.
Log transformation was also evaluated as part of the modeling process.

## 📈 Model Comparison

The performance of multiple regression models was evaluated using
RMSE, MAE, R² score, and accuracy.

![Model Comparison Results](images/Model_comparison_results%20.png)

## 🏆 Results

The project found that feature engineering and log transformation
improved model performance.

Ensemble models such as Random Forest and XGBoost performed better
than traditional regression models in the experiments.

The project identified Random Forest Regression with log transformation
as the selected approach based on the evaluated results.

## 📁 Repository Structure

```text
flight-fare-analysis/
│
├── flight-fare-analysis.ipynb
├── README.md
└── Flight_Fare_Analysis_Presentation.pptx
```
