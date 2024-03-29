![202717555-9cf5d41a-ff4b-47c8-9a85-62ad5ef1a206](https://user-images.githubusercontent.com/111070329/211984610-09d1b583-8c80-41f8-bc13-25f21a03c98b.png)

# Bike-Sharing-and-Demand-Prediction

# Problem Statement

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour, and date information. Based on the given data we have to build a machine learning model which will be helping us to predict the number of bikes that must be made available by predicting the demand for bikes rented per day.

# Objective

To predict the bike demands for the next day based on certain conditions like weather forecasting, holidays and active users in particular areas by analysing the previous data.

# Data Set Description:

Date : year-month-day 

Rented Bike count - Count of bikes rented at each hour Hour 

Hour of the day Temperature-Temperature in Celsius Humidity 

% Windspeed - m/s Visibility - 10m 

Dew point temperature - Celsius 

Solar radiation - MJ/m2 

Rainfall - mm 

Snowfall - cm 

Seasons - Winter, Spring, Summer, 

Autumn Holiday - Holiday/No holiday 

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Factors Affecting:

Seasons : Bike rental is high during the summer and least during the Spring season.

Temperature : As the temperature increases the bike count is gradually increases .

Hours : We observed that there is a peak in the bike rentals counts at around 8am morning and at around 5pm evening.

Weather : When the weather is clear or sunny the bike rental is high where as in the heavy rain and snowfall the bike rental is very low.

Working Day : Bike rental counts on working and non-working days and we observed that the outliers are present in working day.

Holiday : Bike rental counts on holidays and non-holidays. Holidays correspond to non-working days. Also outliers are present in non holidays.

# Steps Involved:

## Exploratory Data Analysis :
After loading and reading the dataset in notebook, we performed EDA. Comparing target variable which is bike rentals counts with other independent variables. This process helped us figuring out various aspects and relationships among the target and the independent variables and also we observed the distribution of variables. It gave us a better idea that how feature behaves with the target variable.

## Preprocessing data :
Dataset contains a no null values also no duplicate values are found to disturb the accuracy . Changing column names for easy handling. Dropping the unwanted columns from the dataset.

## Features selection :
With the help of exploratory data analysis we analyzed the categorical as well as numerical features in the dataset.

## One hot encoding : 
In this dataset some categorical variables like seasons, holiday and function day, we change it with numerical database.

## Correlation Analysis : 
We plot the heatmap to find the correlation between both dependent variable and independent variables.

## Train test Split : 
In train test split we take ‘x’ as dependent variables and ‘y’ take as independent variable then train the model.


# Correlation Analysis

<img width="943" alt="202718861-d1828049-e67d-4efb-9b70-5d370a79ca93" src="https://user-images.githubusercontent.com/111070329/211995443-5a89384a-86fd-40b6-97d0-0942832b2ac3.png">



# Conclusion:

Bike rental count is mostly correlated with the time of the day as it is peak at 10 am morning and 8 pm at evening. We observed that bike rental count is high during working days than non working day. We see that people generally prefer to bike at moderate to high temperatures. We observed highest rental counts between 32 to 36 degrees Celsius. It is observed that highest number bike rentals counts in Autumn/fall Summer Seasons and the lowest in Spring season. We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day. We observed that with increasing humidity, the number of bike rental counts decreases. Hour of the day holds most importance among all the features for prediction of dataset.

# 📜 Credits
Kedar Patil | Data Science Enthusiast

www.linkedin.com/in/kedarpati24


# 📚 References 

1. GeekforGeeks (https://www.geeksforgeeks.org/removing-stop-words-nltk-python/?ref=lbp)

2. Kaggle (https://www.kaggle.com/)

3. Analytics Vidya
