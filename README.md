# Project Name
> Linear Regression Model - For Boom Bikes Sharing Co.


## General Information

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Business Goal

Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Data Set

In the dataset provided, noticed that there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. 
The model should be built taking this 'cnt' as the target variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Holidays attract more customers.
- Top 3 significant contributers are temp, summar and sep
- YearOnYear growth is visible.
- Weathers like rain & snow declines the count.
- Between April to Novemeber the count stays on higher side.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- import numpy as np
- import pandas as pd
- from math import sqrt
- import matplotlib.pyplot as plt
- import seaborn as sns
- import statsmodels.api as sm
- from sklearn.linear_model import LinearRegression
- from sklearn.model_selection import train_test_split
- from sklearn.feature_selection import RFE
- from sklearn.preprocessing import MinMaxScaler
- from sklearn.metrics import r2_score
- from sklearn.metrics import mean_squared_error
- from sklearn.metrics import mean_absolute_error
- from statsmodels.stats.outliers_influence import variance_inflation_factor
- from sklearn import preprocessing
- from sklearn.preprocessing import LabelEncoder

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sameepmishra] - feel free to contact me!