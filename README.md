# Credit Card Fraud Detection

## Overview
This project focuses on analyzing a credit card transaction dataset for fraud detection. The dataset is loaded from a CSV file (`creditcard.csv`), and various exploratory data analysis (EDA) techniques are applied to understand feature distributions and relationships. Machine learning models are then implemented to classify transactions as legitimate or fraudulent.

## Dataset
The dataset consists of:
- **Features (X):** Various numerical features representing transaction attributes.
- **Target Variable (y):** A binary classification label (0: Legitimate, 1: Fraudulent).

The dataset is highly imbalanced, with the majority of transactions being legitimate.

## Project Structure
The project is organized as follows:
- `creditcard.csv`: The dataset file.
- `EDA with SQL.ipynb`: Jupyter Notebook for exploratory data analysis using SQL queries.
- `Machine Learning Prediction.ipynb`: Jupyter Notebook for implementing and evaluating machine learning models.
- `README.md`: Project documentation.

## Steps in the Notebooks

### 1. Data Loading
- Reads `creditcard.csv` using pandas.
- Displays basic statistics and dataset structure.

### 2. Exploratory Data Analysis (EDA)
- Generates summary statistics.
- Plots histograms for all features.
- Visualizes distributions to identify patterns.
- Uses SQL queries to perform data analysis.

### 3. Machine Learning Model
- Implements various machine learning models for fraud classification.
- Trains and evaluates the models.
- Tests the models' accuracy and performance.
- Uses techniques like oversampling and undersampling to handle class imbalance.

## Dependencies
Ensure you have the necessary Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- sqlite3
- prettytable
- ipython-sql

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn sqlite3 prettytable ipython-sql