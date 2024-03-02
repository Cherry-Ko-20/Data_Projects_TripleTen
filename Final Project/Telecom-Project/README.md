# Telecom Customer Churn Prediction Project

## Overview
This project focuses on predicting customer churn in a telecom industry setting. Customer churn refers to the phenomenon where customers discontinue their services with a company. The objective is to build machine learning models that can identify potential churners based on various features and characteristics.

## Project Structure
The project is organized into several key phases:

## Data Preprocessing:

Handle missing values and duplicates.

Standardize column names, handle unnamed columns.

Convert 'BeginDate' to datetime format.

Convert 'TotalCharges' to float type.

## Data Splitting:

Split the dataset into training and testing sets.

## Model Selection and Training:


Choose appropriate machine learning algorithms for classification (e.g., Random Forest, XGBoost).

Train more Gradient Boosting models.

Train the selected models using the training dataset.


## Model Evaluation and Fine-Tuning:

Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

Fine-tune hyperparameters to improve model performance.

Validate the model on the testing dataset.

## Interpretation and Reporting:

Generate insights on key factors influencing customer churn.
Prepare a comprehensive report with actionable recommendations.

## Project Files

## The project includes several datasets:

contract.csv: Contains information about customer contracts.

personal.csv: Includes personal details of customers.

internet.csv: Describes internet usage by customers.

phone.csv: Provides details about phone services.

The main project file is the Jupyter Notebook named telecom_churn_prediction.ipynb. It covers the entire data analysis, preprocessing, model training, and evaluation process.

## How to Use
Environment Setup:

Ensure you have Python and the required libraries installed. You can use the following command to install dependencies: pip install -r requirements.txt

Run the Notebook:

Execute the Jupyter Notebook telecom_churn_prediction.ipynb to reproduce the analysis and results.

## Explore Results:

Examine the model evaluation metrics, visualizations, and insights provided in the notebook.
Adaptation and Further Development:


## Libraries Used
pandas: Data manipulation and analysis.
numpy: Numerical operations.
matplotlib and seaborn: Data visualization.
scikit-learn: Machine learning tools and algorithms.
xgboost, lightgbm, catboost: Gradient boosting libraries.

## Results
The project achieves notable results in predicting customer churn, with models such as Random Forest and XGBoost demonstrating high accuracy and AUC-ROC scores. The detailed evaluation metrics and visualizations are available in the notebook.

## Conclusion
Telecom companies can leverage the insights gained from this project to identify potential churners early, allowing for proactive measures to retain customers and improve overall customer satisfaction.

Copyright © 2024 Cherry Ko. All rights reserved.

