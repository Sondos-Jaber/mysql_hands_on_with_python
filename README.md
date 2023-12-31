# Airline Passenger Satisfaction Prediction
##  Overview
This analysis targets to understanding and enhancing passengers' satisfaction within the context of our dataset. The objectives are as follows:

## 1. Connecting a MySQL database with Python.
   The focus is on efficiently importing data from the database into the Python enviroment for dataanalysis purposes.

## 2. Feature Relevance Evaluation
### 2.1 Categorical Features
I assess the significance of categorical features by employing statistical methods such as chi-squared and mutual information statistics.

### 2.2 Numerical Features
The importance of numerical features is determined through Pearson's coefficient analysis.

## 3. Cleaning data and outlier Detection
A statistical approach, specifically Boxplot analysis, is utilized to identify outliers within the dataset.

## 4. Customer Satisfaction Modeling
The ultimate goal is to create a model for predicting customer satisfaction applying ***SVM (Support Vector Machine) classifier***. This involves:
Utilizing both categorical and numerical inputs.
Employing a binary classification target variable.
### 4.1 Algorithm Selection
I apply the Linear Support Vector Classification (Linear SVC) algorithm from the scikit-learn library for the classification task.

# Data Sources
The dataset used in this analysis is sourced from Kaggle and revolves around airline customer satisfaction. The dataset, available at Airline Passenger Satisfaction Dataset, has been divided into training and testing sets.

Training Data: The analysis primarily focuses on the training dataset, leveraging a comprehensive set of 23 features encompassing both categorical and numerical attributes.
Explore the dataset on Kaggle for a detailed overview and documentation of the features (https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction).

# Prerequisites
Ensure you have the following prerequisites installed before running the project:

Python: Version 3.11.4 is required. You can download the latest version from the official Python website (https://www.python.org/downloads/).

Python Libraries:

Pandas
Matplotlib
SQLAlchemy
scipy.stats
NumPy
seaborn
scikit-learn (klearn)
