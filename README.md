# House Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting house prices using the California Housing dataset. Multiple machine learning regression models are implemented and compared to evaluate their performance.

## 📂 Dataset

* **Name:** California Housing Dataset
* **Type:** Regression
* **Target Variable:** `median_house_value`
* **Features:**

  * longitude
  * latitude
  * housing_median_age
  * total_rooms
  * total_bedrooms
  * population
  * households
  * median_income
  * ocean_proximity

## ⚙️ Data Preprocessing

* Handled missing values using mean imputation
* Converted categorical variable (`ocean_proximity`) into numerical format using one-hot encoding
* Feature scaling applied for KNN model

## 🤖 Machine Learning Models Implemented

1. Simple Linear Regression
2. Multiple Linear Regression
3. Polynomial Regression
4. Decision Tree Regressor
5. Random Forest Regressor
6. K-Nearest Neighbors (KNN) Regressor


## 🔀 Data Splitting

Two train-test splits were used:

* 70% Training and 30% Testing
* 80% Training and 20% Testing

## 📊 Evaluation Metrics

The performance of each model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

## 📈 Results & Comparison

* Random Forest Regressor achieved the best performance among all models
* KNN showed moderate performance after feature scaling
* Decision Tree performed well but showed signs of overfitting
* Linear and Polynomial models provided baseline results

## 🧠 Conclusion

The project demonstrates that ensemble methods like Random Forest provide better accuracy for complex datasets. Model comparison helps in selecting the most suitable algorithm for prediction tasks.


## 🚀 Future Improvements

* Hyperparameter tuning
* Feature selection
* Use of advanced models like Gradient Boosting
* Deployment using web frameworks
