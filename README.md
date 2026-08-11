# Customer Churn Prediction

A machine learning and neural network project for predicting customer churn using an e-commerce customer dataset.

## Project Overview

This project explores customer purchasing data to build classification models that predict whether a customer is likely to churn.

The project includes:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Categorical feature encoding
* Feature scaling
* Machine learning classification
* Neural Network classification
* Model evaluation and comparison

## Machine Learning Models

The following models were used for comparison:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Neural Network

The Support Vector Classifier (SVC) was considered but kept commented out because its training time was considerably longer with the large dataset.

## Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC AUC Score

Multiple metrics were considered because the dataset contains an imbalance between the Churn classes, making Accuracy alone insufficient to fully evaluate the model's ability to identify churned customers.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras
* Google Colab

