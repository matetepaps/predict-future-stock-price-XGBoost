# predict-future-stock-price-XGBoost

### **A Regression Project Using XGBoost to forecast stock prices based on historical dataset from yfinance**

In this project we did the following:
- We collect data by downloding the historical dataset price from Yahoo finance.
- Data preprocessing, by cleaning, transforming and enconding features. Spliting the dataset into training and test sets.
- We train an XGBoost regression model on the training data. Tune hyperparameters using grid search techniques to find the optimal model parameters.
- We print the best optimal parameters for the model
- We evaluate the trained model's performance on both the training and testing datasets using metrics such as Mean squared error (MSE) root mean squared error (RMSE), and R-squared (R2) score. Afterward we analyze the bias-variance tradeoff to ensure the model generalizes well to unseen data.
- We visualize the model's predictions against the actual stock prices to assess its accuracy and identify any patterns or trends.

