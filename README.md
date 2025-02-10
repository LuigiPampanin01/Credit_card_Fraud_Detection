# Fraud Detection Analysis

## Overview
This project focuses on analyzing a credit card transaction dataset for fraud detection. The dataset is loaded from a CSV file (`creditcard.csv`), and various exploratory data analysis (EDA) techniques are applied to understand feature distributions and relationships.

## Dataset
The dataset consists of:
- **Features (X):** Various numerical features representing transaction attributes.
- **Target Variable (y):** A binary classification label (0: Legitimate, 1: Fraudulent).

## Steps in the Notebook
1. **Data Loading**
   - Reads `creditcard.csv` using pandas.
   - Displays basic statistics and dataset structure.

2. **Exploratory Data Analysis (EDA)**
   - Generates summary statistics.
   - Plots histograms for all features.
   - Visualizes distributions to identify patterns.

3. **Machine Learning Model**
   - Implements a machine learning model for fraud classification.
   - Trains and evaluates the model.
   - Tests the model's accuracy and performance.

## Dependencies
Ensure you have the necessary Python libraries installed.
## How to Run
1. Download the dataset (`creditcard.csv`).
2. Open the Jupyter Notebook (`anlaysis_fraud_detection.ipynb`).
3. Run the notebook cells sequentially.

## Future Work
- Improve feature selection and dimensionality reduction.
- Experiment with anomaly detection techniques.
- Tune hyperparameters for better model performance.

## Author
Luigi Pampanin

