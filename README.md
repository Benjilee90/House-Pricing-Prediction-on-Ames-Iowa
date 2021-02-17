# Project 2 - Ames Housing Data and Kaggle Challenge

## Introduction

The Ames Housing Data Set from the Ames Assessor’s Office used in computing the value of individual residential properties sold in Ames, Iowa from 2006 to 2010. Predict the price of homes at sale for the Aimes Iowa Housing dataset.<br><br>
The data set contains information for more than 2900 properties. The data dictionary outlines more than 75 descriptive variables. Some are nominal (categorical), meaning they are non-numerical and lack clear-cut order (Examples: Neighborhood, Type of roofing). Some are ordinal, meaning they are categorical but have a clear order (Example: Heating Quality (Excellent, Good, Average, Poor)). Some are discrete, meaning they are numerical but at set intervals (Year Built, Number of Fireplaces). The rest are continuous, meaning they are numerical and can theoretically take any value in a range (1st Floor Square Feet).<br><br>

## Problem Statement
The aim is to predict the sales price for each house by creating a regression model based on the Ames Housing Dataset (2006 - 2010).<br><br>


## Executive Summary

There are three Jupyter notebooks in this research: (1)Data cleaning and EDA, (2)Preprocessing and Feature Engineering, and (3)Model Tuning and Conclusion.<br>

1. In the EDA and data cleaning notebook:<br>
- There are columns with null values in total in both Categorical and Numerical Data<br>
- There are a few with typo error with the data set<br>
- These features contains common rating<br>
- Features who has the incorrect data type<br>
- Some data points can be combined to give a better correlation to sale price<br>

2. In the Preprocessing and Feature Engineering:<br>
- Cleaning of Data<br>
- Get dummies for data<br>
- Correlation of cleaned dataset<br>

3. In Model Tuning and Conclusion:<br>
- Preparation of data for evaluation<br>
- Predict pricing of housing<br>

## Conclusion and Recommendation

Between the three regression model, Lasso performs in terms of predicting the Ames housing price. Of note, Elastic Net Regression Model have yet to be tested but it should perform better than Lasso.<br>

Among all the features within the dataset, features with condition, area or age gives a better predictor as compared to other features. With the predictor, the relationship between additional amenities (e.g. basement/garage) and the price becomes very prominent. The age of the building on the other hand shows that as the building ages, the price gradually decreases.<br>

For existing homeowners looking to increase the value of their house, they can consider (1) Improving the quality of condition of basic amenities(e.g. house condition, kitchen) or (2) adding additional amenities within the house (e.g. garage, fireplace, pool).<br>

However, people using the model to purchase the house should note that the model is based on dataset from 2006 - 2010 and the model may not hold as there may be changes in the past ten year (current year 2020). There may be other factors like government and external influence (e.g. pandemic or disasters) were not taken into consideration. Apart from that, this dataset is only done based on Ames, USA. Hence, it may not be applicable overseas let alone other states of US. Other factors like FOMO (Fear of Mission Out) will also cost a shift in saleprice and it is hard to predict at times.<br>

In order to overcome the limitation, more data is required considering longer timeframe or other states or countries. More specialised consideration can be included like government's or external influence which may explain potential outliers within the data set.<br>

## Data Description

Link(http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)
