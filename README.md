# Capstone-2_Regression_Project
Yes Bank stock closing price prediction 
![image](https://user-images.githubusercontent.com/120714922/227891206-a6772957-b8ce-43e9-bfb4-2e956a058292.png)

# Capstone2-
# YesBank stock closing price prediction 

# PROBLEM STATEMENT

Yes Bank Limited is an Indian private sector bank headquartered in Mumbai, India and was founded by Rana Kapoor and Ashok Kapur in 2004. It offers wide range of differentiated products for corporate and retail customers through retail banking and asset management services. On 5 March 2020, in an attempt to avoid the collapse of the bank, which had an excessive amount of bad loans, the Reserve Bank of India (RBI) took control of it.

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

# Algorithm used 
1.Linear regression

2.lasso regression

3.Ridge regression

4.ElasticNet regression

5.SVR

6.XGBoost

# *features (Column)*:

 *1) Open* : Opening price of the stock of particular day

 *2) High* : It's the highest price at which a stock traded during a period

 *3) Low* : It's the lowest price at which stock traded during a period

 *4) Close* : Closing price of a stock at the end of a Trading Day

*5) Date* : In our data its monthly observation of stock since it listed

# Conclusion

*   Exploratory Data Analysis 
1. from 2016 to 2018 stock closing price increase but after year 2018 it started decreasing because of Rana Kapoor case
2. same pattern of observations for the opening price also .
3. And according to above two reason the point that the stock price of yes bank falls down after 2018 and it is not beneficial for investors to invest
4. after plotting distplot we got to know that data for dependent and indepent variables are rightly skewed for that we applied log transformation.
5. next we got to know that independent features are highly correlated after plotting scatter plots.
6. after using heat map we also get that independent features are highly correlated  this cuase high multicollinearity
7. after calculating vif we get that all the available features are most important for closing price prediction so will not drop it from data set.




*   dependent variable strongly dependent on independent variables


*  we get highest accuracy of 99.99%

*   ridge and lasso has near about same R2 score 
*   where as elastic net shows lowest R2 score and high MSE ,RMSE,MAE,MAPE values

* XGBoost Regressor end up with Highest r2 value and the predicted values are nearly equal to the actual values as we got 99 % accuracy.
