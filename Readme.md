# Bangalore House Prediction Project using Linear Regression

![Banglore](https://github.com/ishikawa-yui/Bangalore_house_price_pred_using_LinearRegression/assets/71602299/228e47c3-21b2-4c02-97f1-99e892e7c25f)
(Using LinearRegression)

This project aims to predict house prices in Bangalore using linear regression. The dataset contains various features related to houses in Bangalore, and the goal is to build a predictive model to estimate the price of a house based on its characteristics. In this README file, we'll provide an overview of the project, the dataset, and the key steps involved.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Prediction Function](#prediction-function)
- [Results](#results)

## Project Overview
In this project, we use linear regression to predict house prices in Bangalore. The dataset includes information about different houses in Bangalore, such as area type, availability, location, size, society, total square feet, number of bathrooms, number of balconies, and the price. With this data, we aim to create a predictive model that can estimate house prices with reasonable accuracy.

## Dataset
The dataset contains the following fields:
- `area_type`: The type of area (e.g., Super built-up Area, Plot Area, Built-up Area).
- `availability`: Availability status of the property.
- `location`: The location of the property in Bangalore.
- `size`: The size of the property (e.g., 2 BHK, 3 BHK).
- `society`: The name of the society or housing association.
- `total_sqft`: The total square footage of the property.
- `bath`: The number of bathrooms.
- `balcony`: The number of balconies.
- `price`: The price of the house.

The dataset contains a total of 13,320 entries.

## Data Preprocessing
In the data preprocessing phase, several custom functions were created to clean the data, handle missing values, and perform feature engineering. Outliers were also identified and removed to improve the quality of the dataset.

## Exploratory Data Analysis
To gain insights from the data, various data visualization techniques were employed, including:
- Correlation matrix to understand the relationships between variables.
- Scatterplots to visualize the relationships between different features and the target variable (price).
- Box plots and histograms to identify potential outliers and the distribution of numerical features.

## Model Training
A linear regression model was trained on the preprocessed data. The dataset was split into training and testing sets, using an 80/20 split, to evaluate the model's performance. The model was fitted to the training data and tested on the testing data to assess its predictive accuracy.

## Prediction Function
A custom function was developed based on the trained linear regression model. This function takes input parameters such as location, square footage, number of bathrooms, and BHK (Bedroom-Hall-Kitchen) size, and it predicts the price of a house in Bangalore. The function achieved an accuracy of 85%, indicating its reliability for price prediction.

## Results
This project successfully demonstrates the use of linear regression for house price prediction in Bangalore. The custom functions for data preprocessing, feature engineering, and outlier removal contribute to the reliability of the model. The prediction function can be a valuable tool for individuals looking to estimate house prices based on specific characteristics.
