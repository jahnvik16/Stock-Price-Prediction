Stock Price Prediction Using Linear Regression
Project Overview
This project involves building a stock price prediction model using linear regression. The model is designed to predict the closing prices of Google's stock for the next 5 days based on historical data. The process includes data preparation, feature engineering, model training, and evaluation.

Features and Techniques
Data Preparation and Feature Engineering:

Loaded historical stock data from a CSV file.
Selected the 'Close' price column as the feature for prediction.
Created a new column 'label' which is the 'Close' price shifted by 5 days (forecast_out = 5).
Scaled the feature data using sklearn.preprocessing.scale to normalize the input values.
Split the data into training and testing sets using train_test_split with a test size of 20%.
Model Development:

Used LinearRegression from the sklearn.linear_model library to train the model on the prepared dataset.
Evaluated the model using the R-squared score to measure the goodness of fit.
Prediction:

Predicted the closing prices for the next 5 days.
Achieved a test score (R-squared value) of 0.876, indicating a good fit of the model to the data.

Results
Test Score: The R-squared value of the model on the test data is 0.876, indicating that the model explains approximately 87.6% of the variance in the test data.
Forecasted Prices: The predicted closing prices for the next 5 days are as follows:
Day 1: 1461.03
Day 2: 1452.70
Day 3: 1460.30
Day 4: 1483.58
Day 5: 1478.65
Conclusion
This project demonstrates the practical application of linear regression for stock price prediction. By using historical data, the model provides a reasonable estimate of future stock prices, showcasing the power of machine learning in financial analysis.


