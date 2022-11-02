Project Name: House Price Prediction - Advanced Regression

Problem Statement:
    A US-based Surprise housing company has decided to enter the Australian market to start their business. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
    For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
    The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in the properties or not.
    The housing company wants to know:
    -Variables which are significant in predicting the price of a house
    -How well those variables describe the price of a house
    Also, determine the optimal value of lambda for ridge and lasso regression

Scope of Analysis:
   Build a regression model using regularisation to predict actual value of properties with the available independent variables. This model will be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market

Approach:
    Understanding and exploration of the data
    Data cleaning and visualizing
    Preparing the data for modelling
    Model building and evaluation
    Inference

Source of Data:
    Data are provided in the file “train.csv”. The "train.csv" file contains private data coming from the Surprise housing company. No additional details are expected to be analyzed as part of the study.

Regression Models:
    Ridge and Lasso Regression models were developed. Refer to Python coding file for details
  
Inference:
    Optimal Lambda value for Ridge and Lasso models are given below:
    Ridge model : 20, Lasso model : 0.001
    Mean Squared errors for Ridge and Lasso models are given below:
    Ridge model : 0.01266, Lasso model : 0.01267
    The Mean Squared Error of Ridge and Lasso is almost same.
    However, since Lasso helps in feature reduction (as the coefficient value of some of the feature became 0), Lasso is better than Ridge.
    The top ten variables which have impact on the target variable of Lasso model are shown above.
    In the Lasso model, the variables/features which have high impact on the Sale price of houses are Living area, Overall quality, Overall condition, Total basement area, Zone classification, Foundation type, Car Garage area to accommodate cars, Basement finished area and house built/remodelled year

Acknowledgemnts
    The project was assigned and guided by Upgrad

Contact
    Created by Suresh

