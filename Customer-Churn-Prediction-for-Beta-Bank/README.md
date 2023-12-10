# Customer Churn Prediction for Beta Bank

## Project Description

Beta Bank, a prominent financial institution, has been facing a growing issue - customers leaving the bank over time. As a cost-effective strategy, Beta Bank has decided to prioritize retaining existing customers over acquiring new ones. In order to achieve this, the bank aims to predict which customers are likely to leave soon. To tackle this challenge, we have access to historical data on customer behavior and contract terminations.

## Project Objectives

-`Predict Customer Churn`: Build a machine learning model that predicts whether a customer is likely to leave Beta Bank in the near future.

-`Maximize F1 Score`: Develop a model with the highest possible F1 score, aiming for a minimum F1 score of 0.59.

-`AUC-ROC Evaluation`: Measure the AUC-ROC (Area Under the Receiver Operating Characteristic) metric to assess the model's performance and compare it with the F1 score.

## Project Steps

-`Data Preparation`: Download and preprocess the dataset, handling missing values, encoding categorical features, and scaling numeric attributes.

-`Class Imbalance Analysis`: Examine the balance of classes in the dataset and understand the severity of the class imbalance.

-`Model Training without Balancing`: Train initial models without addressing class imbalance and evaluate their performance.

-`Improve Model Quality`: Apply at least two techniques to fix class imbalance, such as upsampling, downsampling, or using class weights. Select the best model parameters through hyperparameter tuning.

-`Model Training and Validation`: Train different models on training and validation sets, comparing their F1 scores and AUC-ROC values.

-`Select the Best Model`: Choose the model with the highest F1 score as the best-performing model.

-`Final Testing`: Evaluate the selected model on the test set and report the F1 score and AUC-ROC score.

By executing these steps, Beta Bank aims to identify customers at risk of churning and take proactive measures to retain them, ultimately improving customer retention and reducing costs associated with customer acquisition.


## Data description

-`Features`

-`RowNumber` : data string index

-`CustomerId` : unique customer identifier

-`Surname` : surname

-`CreditScore` : credit score

-`Geography` : country of residence

-`Gender` : gender

-`Age` : age

-`Tenure` : period of maturation for a customer’s fixed deposit (years)

-`Balance` : account balance

-`NumOfProducts` : number of banking products used by the customer

-`HasCrCard` : customer has a credit card

-`IsActiveMember` : customer’s activeness

-`EstimatedSalary` : estimated salary

-`Target`

-`Exited` : сustomer has left

## Result 
