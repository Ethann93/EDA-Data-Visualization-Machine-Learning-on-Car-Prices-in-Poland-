# EDA, Data Visualization & Machine Learning on Car Prices in Poland

## Overview

This project involves Exploratory Data Analysis (EDA), Data Visualization, and Machine Learning to predict car prices in Poland using the dataset that can be found in Kaggle through the following link: https://www.kaggle.com/datasets/aleksandrglotov/car-prices-poland/data

## Stages

### Stage 1: Data Preparation

1. Import necessary libraries, including pandas, numpy, and visualization libraries.
2. Load the dataset using `pd.read_csv('Car_Prices_Poland_Kaggle.csv')`.

### Stage 2: Data Exploration

1. Display the dataset.
2. Check the dataset's shape.
3. Display summary statistics.
4. Examine data types.
5. List the columns.

### Stage 3: Data Cleaning

1. Drop unnecessary columns: 'Unnamed: 0' and 'generation_name'.
2. Check for and handle missing values.
3. Check for and remove duplicates.
4. Explore unique values for car makes ('mark') and fuel types ('fuel').

### Stage 4: Data Visualization

1. Create a correlation heatmap to understand relationships between variables.
2. Plot the distribution of car years.
3. Generate a scatter plot of mileage vs. price.
4. Create a bar chart of average prices by car make.
5. Generate a box plot of car prices and identify the upper 3rd quartile.
6. Create a bar chart of the top 10 most common car models.
7. Generate a scatter plot of engine size vs. price.
8. Create a bar chart of the count of cars in each city.
9. Generate a pie chart showing the maximum engine size by fuel type.

### Stage 5: Feature Engineering

1. Define the target variable 'price'.
2. Select features and drop unnecessary columns.
3. Convert categorical values into numeric using label encoding.
4. Split the data into training and testing sets.
5. Standardize the feature values.

### Stage 6: Model Building

1. Apply three machine learning models: Linear Regression, Support Vector Machine (SVM), and Random Forest Regressor.
2. Evaluate each model's performance using various metrics, such as mean absolute error, root mean squared error, and R-squared.

## Conclusion

The analysis provides valuable insights into the relationships between car attributes and prices. The machine learning models enable price predictions based on the chosen features. The choice of the best model may depend on factors like dataset characteristics and desired accuracy levels.



