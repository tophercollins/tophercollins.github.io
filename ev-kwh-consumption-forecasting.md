# Electric Vehicle kWh Consumption Forecasting > [Go to project](https://colab.research.google.com/drive/18l8vWPG6_6S0i_24RSqVNjoryDjeqC9x?usp=sharing)

## Aim

The aim of this project is to develop predictive models for forecasting daily kWh consumption for electric vehicle (EV) charging at a workplace. The goal is to create accurate forecasts to optimize energy usage and planning.

## Data

The data used in this project consists of daily kWh consumption records for EV charging. The dataset includes various features that capture the energy usage patterns over time.

## Process

1. Data Preprocessing: The dataset is cleaned and preprocessed to handle missing values, normalize data, and prepare it for model training.
2. Exploratory Data Analysis (EDA): Key patterns and trends in the data are explored using visualization techniques.
3. Model Development:
* Multiple models are developed, including simple neural networks and advanced gradient boosting models like LightGBM.
* The models use the previous 7 days of consumption data to predict the consumption for the subsequent day.
* Models are evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
4. Model Evaluation: The performance of each model is compared to identify the best-performing model based on evaluation metrics.

## Conclusion

The project concluded that while several models were developed, the Multivariate Dense Neural Network (Model 2) performed the best with a mean absolute error (MAE) of 11.26. Despite this, the accuracy of the predictions was not particularly high, indicating room for improvement. Surprisingly, gradient boosting models like LightGBM, which are typically strong performers in time series forecasting, did not perform well and appeared to overfit the data. Further investigation is needed to improve the model's accuracy and understand the underlying factors affecting model performance.
