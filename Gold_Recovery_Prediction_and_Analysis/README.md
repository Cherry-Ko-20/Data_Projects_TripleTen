# Gold Recovery Prediction and Analysis

This project is an individual undertaking, meaning that it is being carried out by a single person working independently, without collaboration or group involvement.


# Project Goal 

This project focuses on predicting the gold recovery process in a mining industry context. The goal is to develop a predictive Machine Learning model that estimates the efficiency of the gold recovery process at different stages and provides insights into the concentrations of various metals.

# Project Description

The data is stored in three files:

gold_recovery_train.csv — training dataset 

gold_recovery_test.csv — test dataset 

gold_recovery_full.csv — source dataset 

The data is provided by TripleTen, who took it from Kaggle and modified it.


The project revolves around the prediction and analysis of gold recovery in a mining process. The data used for this project is stored in three files: gold_recovery_train.csv (training dataset), gold_recovery_test.csv (test dataset), and gold_recovery_full.csv (source dataset). The data is indexed by date and time of acquisition. It is observed that parameters measured closely in time are often similar. However, certain parameters may not be available in the test dataset, and the source dataset contains both training and test data with all features. The raw data is provided, which needs to be processed and validated before building the prediction model.

# Approaches for Gold Recovery Prediction

Prepare the Data:

1.1. Open and examine the data in the provided files.

1.2. Validate the correctness of the recovery calculation. Calculate recovery for the rougher.output.recovery feature in the training set and find the Mean Absolute Error (MAE) compared to the feature values.

1.3. Analyze features not present in the test set and determine their types.

1.4. Perform data preprocessing to clean and prepare the data.

Analyze the Data:

2.1. Investigate how metal concentrations (Au, Ag, Pb) change at various purification stages.

2.2. Compare the feed particle size distributions between the training and test sets to ensure accurate model evaluation.

2.3. Examine the total concentrations of all substances at different stages and identify and eliminate any abnormal values that could affect the analysis.


Build the Model:

3.1. Develop a function to calculate the final sMAPE (Symmetric Mean Absolute Percentage Error) value.

3.2. Train different models, evaluate their performance using cross-validation, select the best model, and test it using the test sample. Provide detailed findings based on the evaluation metrics.

# Results 

For a comprehensive understanding of the outcomes and insights derived from this project, it is highly recommended to review the detailed documentation provided in the accompanying Jupyter Notebook.
