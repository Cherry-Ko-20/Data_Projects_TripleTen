# Oil Well Location Optimization for OilyGiant Mining Company

This project is an individual undertaking, meaning that it is being carried out by a single person working independently, without collaboration or group involvement.

## Project Description

At the OilyGiant mining company, the objective is to identify the optimal location for a new oil well. The process involves several key steps:

Collecting oil well parameters in the chosen region, specifically focusing on oil quality and volume of reserves.

Constructing a predictive model for estimating the volume of reserves in potential new wells.

Selecting the oil wells with the most favorable estimated values based on the predictive model.

Identifying the region with the highest overall profit potential by considering the selected oil wells.

## Project Instructions

-`Data Preparation`

-`Model Training and Testing` : Train and test the model for each region
  
- Split the data into a training set and validation set (75:25 ratio).
  
- rain the model and make predictions for the validation set.
  
- Save predictions and correct answers.
  
- Print the average volume of predicted reserves and model RMSE.
  
- Analyze the results.

  
-`Profit Calculation Preparation`: Prepare for profit calculation

- Store key values for calculations in separate variables.
  
- Calculate the volume of reserves sufficient for developing a new well without losses.
  
- Compare the obtained value with the average volume of reserves in each region.
  
- Provide findings about the preparation for profit calculation.
  
-`Profit Calculation Function` : Write a function to calculate profit from a set of selected oil wells and model predictions

- Pick the wells with the highest prediction values.
  
- Summarize the target volume of reserves.
  
- Provide findings and suggest a region for oil wells' development, justifying the choice.
  
- Calculate the profit for the obtained volume of reserves.
  
-`Risks and Profit Calculation`: Calculate risks and profit for each region

- Use the bootstrapping technique with 1000 samples.
  
- Find average profit, 95% confidence interval, and risk of losses.
  
- Provide findings, suggesting a region for oil wells' development and justifying the choice.

## Result

For a comprehensive understanding of the outcomes and insights derived from this project, it is highly recommended to review the detailed documentation provided in the accompanying Jupyter Notebook.




