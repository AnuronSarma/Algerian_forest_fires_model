# Algerian Forest Fire Classification Model

## Project Overview
This project focuses on building a machine learning model to classify forest fire occurrences in Algeria based on meteorological and environmental data. The goal of this model is to predict whether there is a fire or not based on input features such as temperature, humidity, wind speed, and others.

The dataset used for this project includes data from two regions of Algeria: **Bejaia Region** and **Sidi Bel-Abbes Region**, during the summer season of 2012.

## Dataset
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset+). It contains meteorological data collected from multiple sensors and the target label, which indicates the presence or absence of a fire. The dataset has the following features:

- **Temperature (Celsius)**
- **Relative Humidity (%)**
- **Wind Speed (km/h)**
- **Rain (mm)**
- **Fine Fuel Moisture Code (FFMC)**
- **Duff Moisture Code (DMC)**
- **Drought Code (DC)**
- **Initial Spread Index (ISI)**
- **Buildup Index (BUI)**
- **Fire Weather Index (FWI)**

The target variable is:
- **Fire Occurrence:** Binary classification (1 = Fire, 0 = No Fire).

## Objective
The objective of this project is to develop a classification model that can predict whether a forest fire will occur based on the input meteorological data. The model will assist in early fire detection and prevention strategies.

## Project Steps
1. **Data Preprocessing**
   - Handling missing values.
   - Splitting the dataset into training and testing sets.
   - Normalizing and scaling the features.
   - Encoding categorical variables (if any).

2. **Exploratory Data Analysis (EDA)**
   - Statistical analysis of features.
   - Correlation analysis to understand relationships between variables.
   - Visualizations to understand data distribution and feature importance.

3. **Model Selection**
   - Multiple classification algorithms are used to develop the model, including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
     - k-Nearest Neighbors (k-NN)
     - XGBoost
   - Hyperparameter tuning to improve model performance.

4. **Model Evaluation**
   - Model evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC curve.
   - Comparison of different models to identify the best-performing one.

5. **Deployment (Optional)**
   - The model can be deployed using a Flask application for real-time predictions based on new data.

## Results
- The best-performing model achieved an accuracy of **X%** on the test set.
- Precision, recall, and F1-score were also calculated to ensure a balanced model performance.
- Feature importance analysis indicated that temperature and relative humidity are the most critical factors in predicting forest fire occurrence.
