# Building-a-Robust-Model-for-Classifying-Film-Reviews-

## Project Structure
Initialization and Data Loading:

Import necessary libraries and load IMDb movie reviews dataset.

## Exploratory Data Analysis (EDA):

Visualize the number of movies and reviews over the years.
Analyze the distribution of reviews per movie.
Explore the distribution of ratings in the training and test sets.
Investigate the distribution of negative and positive reviews over the years.

## Evaluation Procedure:

Create a generic evaluation routine to assess the performance of classification models.

## Normalization:

Normalize the text data for consistent processing by models.

## Train/Test Split:

Divide the dataset into training and test sets based on the provided 'ds_part' flag.

## Model Development:

Model 0 (Baseline): Dummy Classifier with a constant prediction strategy.
Model 1: Logistic Regression with TF-IDF vectorization.
Model 3: Logistic Regression with spaCy text preprocessing and TF-IDF vectorization.
Model 4: LightGBM Classifier with spaCy text preprocessing and TF-IDF vectorization.

## Model Evaluation:

Evaluate each model's performance using the generic evaluation routine.

## Review Predictions:

Apply trained models to custom movie reviews and analyze predicted probabilities.

## Conclusions:

Summarize key findings and insights from the project. Check the project for the conclusion.
