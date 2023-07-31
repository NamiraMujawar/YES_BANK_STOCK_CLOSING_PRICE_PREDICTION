# YES_BANK_STOCK_CLOSING_PRICE_PREDICTION

![imgonline-com-ua-resize-IjZMc6w8sr8IrU](https://github.com/NamiraMujawar/YES_BANK_STOCK_CLOSING_PRICE_PREDICTION/assets/120715329/bf47bba7-e4b9-4a2c-906d-b7bc3fa08122)

The term **"YES BANK STOCK CLOSING PRICE PREDICTION"** refers to the process of using various methods and techniques to forecast or estimate the closing price of the stock of the company called YES BANK.

YES BANK is a well-known Indian private sector bank, and its stock is traded on stock exchanges. The closing price of a stock is the final trading price at which the stock is traded on a particular trading day. The prediction of this closing price involves using historical data, market trends, and various mathematical and statistical models to make an educated guess about what the stock's closing price might be at the end of a given trading day or a specific period in the future.

Predicting stock prices is a challenging task and is usually done by analysts, traders, and researchers who use various methods such as technical analysis, fundamental analysis, machine learning algorithms, and other financial models to make their predictions. However, it's important to note that stock price prediction is inherently uncertain and can be affected by various factors, including market sentiment, economic conditions, company performance, and unexpected events.

**It is essential to exercise caution and skepticism when dealing with stock predictions, as they are not guaranteed to be accurate and can carry inherent risks. Investors should conduct thorough research and seek advice from financial professionals before making any investment decisions based on stock price predictions.*

#**Problem Statement**
---
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

#**Dataset Information**

We have 185 rows and 4 columns in our dataset with no null values. Here our dependent variable will be Close, and independent variables are - Open, High and Low.

* **Date:** It denotes the month and year of the for a particular price.

* **Open:** Open means the price at which a stock started trading that month.

* **High:** refers to the maximum price that month.

* **Low:** refers to the minimum price that month.

* **Close:** refers to the final trading price for that month, which we have to predict using regression

![Screenshot (98)](https://github.com/NamiraMujawar/YES_BANK_STOCK_CLOSING_PRICE_PREDICTION/assets/120715329/55428b32-d75b-4482-b88a-0146b08346db)


**Conclusion**

* The target variable shows high dependence on input variables, indicating a strong relationship between them.

* Linear Regression achieved the best results with the lowest MAE, MSE, RMSE, and MAPE scores, suggesting accurate predictions with low errors.

* Ridge Regression reduced complexity and addressed multicollinearity, impacting evaluation metrics.

* Lasso Regression performed feature selection but was inferior to Ridge Regression, indicating all features' importance for accurate predictions.

* All models achieved over 90% accuracy, but other error metrics and data balance should be considered for comprehensive evaluation.

* KNN and XGBoost showed similar predictive capabilities, requiring consideration of interpretability, efficiency, and implementation ease for model selection.



