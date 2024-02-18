# Taxi Demand Forecasting for Sweet Lift: A Time Series Prediction Project



## Project Description

Sweet Lift Taxi company aims to predict the amount of taxi orders for the next hour to attract more drivers during peak hours. The historical data on taxi orders at airports is available in the `taxi.csv` file.

## Project Instructions

1. **Data Preparation:**
   - Download the data and resample it by one hour.
   
2. **Data Analysis:**
   - Explore and analyze the data.
   
3. **Model Training:**
   - Train different models with different hyperparameters.
   - Use a test sample that represents 10% of the initial dataset.
   
4. **Model Testing:**
   - Evaluate the models using the test sample.
   - Ensure that the RMSE metric on the test set is not more than 48.

## Data Description

The dataset (`taxi.csv`) includes the number of taxi orders, with the target variable labeled as '*num_orders*'.

## Project Execution

1. **Preparation:**
   - Imported necessary libraries.
   - Loaded and resampled the data by one hour.
   - Conducted data exploration and visualization.

2. **Analysis:**
   - Performed train-test split.
   - Conducted decomposition and ACF/PACF plots for time series analysis.
   - Implemented an AutoRegressive (AR) model and visualized results.

3. **Training:**
   - Trained various models, including SARIMA, Exponential Smoothing, Random Forest, and ARIMA.
   - Evaluated models using RMSE.
   - Applied the optimal ARIMA model based on analysis.

4. **Testing:**
   - Chose the best-performing model based on RMSE.
   - Provided predictions for the next hour.
   - Compared predictions with actual taxi orders through visualization.

## Results and Conclusion

The Exponential Smoothing model emerged as the best performer with an RMSE of 41.21, meeting the project requirement. The predicted number of taxi orders for the next hour is 117. The project has been successfully completed.

---



