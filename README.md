![202717555-9cf5d41a-ff4b-47c8-9a85-62ad5ef1a206](https://user-images.githubusercontent.com/111070329/211984610-09d1b583-8c80-41f8-bc13-25f21a03c98b.png)

# Bike-Sharing-and-Demand-Prediction

# Problem Statement

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour, and date information. Based on the given data we have to build a machine learning model which will be helping us to predict the number of bikes that must be made available by predicting the demand for bikes rented per day.

# Introduction

Currently, the bike-sharing scheme is well-received throughout the world. It is a shared bike service for individuals, which is free of charge and for a short- term basis at a minimal rate. Most bike- sharing systems permit people to borrow and return a bike from a bike station to another station that belongs to the same network. Bike-sharing gains a vast range of attention in recent years as part of initiatives to boost the use of cycles, improve the first mile/last mile link to other modes of transportation, and minimize the negative effect of transport activities on the environment. Bike-sharing has significant impacts on establishing a larger cycling community, increasing the use of transportation, minimizing greenhouse gas emissions, enhancing public health, and also traffic troubles.

# Objective

To predict the bike demands for the next day based on certain conditions like weather forecasting, holidays and active users in particular areas by analysing the previous data.

# Exploratory Data Analysis

Exploratory Data Analysis (EDA) plays a vital role in the analysis of the data variables which are important from the aspect of feature engineering. It will help us to distribute and relate between dependent and independent variables. We have gone through an analysis of every independent as well as the dependent variable to check which independent factor affects the dependent factor.

# Feature Engineering

# One Hot Encoding of categorical feature:

One hot encoding is useful for data that has no relationship to each other. Machine learning algorithms treat the order of numbers as an attribute of significance. In other words, they will read a higher number as better or more important than a lower number.

While this is helpful for some ordinal situations, some input data does not have any ranking for category values, and this can lead to issues with predictions and poor performance. That’s when one hot encoding saves the day.

One hot encoding makes our training data more useful and expressive, and it can be rescaled easily. By using numeric values, we more easily determine a probability for our values. In particular, one hot encoding is used for our output values, since it provides more nuanced predictions than single labels.



# Ordinal Encoding:
In ordinal encoding, each unique category value is assigned an integer value.
For example, “red” is 1, “green” is 2, and “blue” is 3.
This is called an ordinal encoding or an integer encoding and is easily reversible. Often, integer values starting at zero are used.

For some variables, an ordinal encoding may be enough. The integer values have a natural ordered relationship between each other and machine learning algorithms may be able to understand and harness this relationship.

# Machine Learning Algorithm

Four statistical models are used to predict the trip duration. (a) Linear regression (b) Decision Tree (c) Random Forest (RF). (d) Gradient boosting machines (e) Extreme Gradient Boosting (XGBoost)

# Conclusion:

The analysis is done with Seoul Bike data. Six regression techniques Linear Regression, Polynomial regression, Decision Tree, Random Forest, Gradient Boosting, XGB are used to predict the trip duration.This statistical data analysis shows interesting outcomes in prediction methods and also in an exploratory analysis.

The experimental results prove that the XGB model predicts best the trip duration with the highest R2 and with less error rate compared to Linear Regression, Decision Tree, Random Forest, Gradient Boosting.

