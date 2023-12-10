# Megalines Mobile Plan Recommendation System

This project is an individual undertaking, meaning that it is being carried out by a single person working independently, without collaboration or group involvement.

## Project description

Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. 

## Goal

Megaline, a leading mobile carrier, initiated a project to enhance subscriber satisfaction by recommending personalized mobile plans. The objective was to develop a model with the highest possible accuracy to predict whether subscribers should switch to either the 'Smart' or 'Ultra' plan based on their behavior.

## Project Objectives:

- Develop a machine learning model that can accurately predict whether a subscriber should switch to the 'Smart' or 'Ultra' mobile plan based on their usage behavior.

- Achieve a model accuracy threshold of at least 75% on the test dataset.

- Perform comprehensive model evaluation, including precision, and recall to ensure the reliability of the recommendation system.

- Conduct a sanity check to confirm the fairness and effectiveness of the model's predictions.

- Provide insights into feature importance, allowing for data-driven decisions and plan optimization.

- Offer actionable recommendations to Megaline for improving plan recommendations and subscriber satisfaction.



## Project Workflow:

- Data Loading and Exploration: Explore and preprocess the dataset, including handling missing values and encoding categorical variables.

- Data Splitting: Split the dataset into training, validation, and test sets to facilitate model development and evaluation.

- Model Development: Implement and fine-tune classification models, including Decision Tree, Random Forest, and Logistic Regression.

- Model Evaluation: Evaluate model performance on the test set using accuracy, precision, and recall.

- Sanity Check: Ensure model fairness and effectiveness by examining prediction distributions.

- Feature Importance Analysis: Analyze feature importances to understand the factors influencing plan recommendations.



## Data description

Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 

-`сalls` : number of calls,

-`minutes` : total call duration in minutes,

-`messages` : number of text messages,

-`mb_used` : Internet traffic used in MB,

-`is_ultra` : plan for the current month (Ultra - 1, Smart - 0).

## Result

For a comprehensive understanding of the outcomes and insights derived from this project, it is highly recommended to review the detailed documentation provided in the accompanying Jupyter Notebook.
