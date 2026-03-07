# Regression

# California Housing Price Prediction using Regression Models

## Project Overview

This project demonstrates the application of **supervised machine learning regression techniques** to predict housing prices using the **California Housing dataset** available in the Scikit-learn library. The goal is to analyze the dataset, preprocess the data, implement multiple regression algorithms, and compare their performance using standard evaluation metrics.

By applying different regression models, this project highlights how machine learning can be used to **predict continuous numerical values** and determine the most effective model for a given dataset.

## Objective

The primary objective of this project is to evaluate the performance of different **regression algorithms** and understand their suitability for predicting housing prices based on various features such as income, population, and housing statistics. 

## Dataset

The dataset used in this project is the **California Housing dataset**, which contains information collected from the 1990 California census. It includes multiple housing-related features and the median house value for each district.

The dataset is loaded using the **`fetch_california_housing()`** function from the **Scikit-learn** library.

## Project Workflow

### 1. Data Loading and Preprocessing

* Loaded the California Housing dataset using Scikit-learn
* Converted the dataset into a **Pandas DataFrame** for easier data manipulation
* Checked for missing values and handled them if present
* Applied **feature scaling (standardization)** to normalize numerical features and improve model performance

### 2. Regression Model Implementation

The following regression algorithms were implemented and trained:

* **Linear Regression**
* **Decision Tree Regressor**
* **Random Forest Regressor**
* **Gradient Boosting Regressor**
* **Support Vector Regressor (SVR)**

Each model was trained on the dataset to learn the relationship between housing features and median house prices.

### 3. Model Evaluation

To measure the performance of each regression model, the following evaluation metrics were used:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **R-squared Score (R²)**

These metrics help evaluate prediction accuracy and compare model performance.

### 4. Model Comparison

All regression models were compared based on their evaluation scores to determine:

* The **best-performing model** with the highest predictive accuracy
* The **least effective model** with lower predictive performance

This comparison helps identify which algorithm is most suitable for housing price prediction.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

## Results

The project provides insights into how different regression models perform on real-world housing data. Through model evaluation and comparison, the most effective regression algorithm for predicting housing prices can be identified.

## Conclusion

This project demonstrates the importance of **data preprocessing, model selection, and performance evaluation** in building effective regression models. By comparing multiple algorithms, it provides a practical understanding of how machine learning techniques can be used for **real-world price prediction problems**.
