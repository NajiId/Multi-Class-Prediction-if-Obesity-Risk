# Obesity Prediction using Machine Learning

This repository contains code for predicting obesity levels using machine learning techniques. The dataset used for training and testing contains information about individuals' characteristics such as gender, age, height, weight, family history with overweight, and lifestyle habits. Various machine learning models are employed to predict the obesity level of individuals based on their attributes.

## Prerequisites

Make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Explore Data
### The dataset contains the following columns:

## Dataset Description

- **id:** Unique identifier for each individual
- **Gender:** Gender of the individual
- **Age:** Age of the individual
- **Height:** Height of the individual
- **Weight:** Weight of the individual
- **family_history_with_overweight:** Family history with overweight (yes/no)
- **FAVC:** Frequent consumption of high caloric food (yes/no)
- **FCVC:** Frequency of consumption of vegetables
- **NCP:** Number of main meals per day
- **CAEC:** Consumption of food between meals
- **SMOKE:** Smoking habit (yes/no)
- **CH2O:** Consumption of water daily
- **SCC:** Calories consumption monitoring
- **FAF:** Physical activity frequency
- **TUE:** Time using technology devices
- **CALC:** Consumption of alcohol
- **MTRANS:** Transportation used
- **NObeyesdad:** Obesity level (target variable)

## Transform Data

The data is preprocessed by encoding categorical variables using LabelEncoder and scaling numerical features using StandardScaler.

## Modeling

Several machine learning models are trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier
3. Gaussian Naive Bayes
4. Support Vector Classifier
5. XGBoost Classifier
6. Gradient Boosting Classifier

## Improve Results

GridSearchCV is utilized to tune hyperparameters for XGBoost Classifier and Gradient Boosting Classifier to improve model performance.

## Predictions

The best-performing model (Gradient Boosting Classifier) is used to make predictions on the test dataset.
