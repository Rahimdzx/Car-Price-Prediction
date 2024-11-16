# Car Price Prediction Using Multiple Linear Regression

This project aims to predict car prices using **Multiple Linear Regression**. The dataset contains various features such as car make, model, mileage, engine size, etc., which are used to train the model. Outliers in the dataset are handled using the **Interquartile Range (IQR)** method to ensure better model accuracy and stability.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Technologies Used](#technologies-used)


## Overview
The goal of this project is to predict car prices based on various car attributes. **Multiple Linear Regression** is used to model the relationship between the features and the target variable (car price). Outliers in the dataset are identified and removed using the **Interquartile Range (IQR)** method to improve the quality of predictions.

## Dataset
The dataset contains the following features:
- **Make**: The brand of the car.
- **Model**: The specific model of the car.
- **Year**: The year the car was manufactured.
- **Mileage**: The total distance the car has traveled.
- **Engine Size**: The size of the engine in liters.
- **Fuel Type**: The type of fuel the car uses (e.g., Petrol, Diesel).
- **Transmission**: The type of transmission (e.g., Automatic, Manual).
- **Price**: The target variable, i.e., the price of the car.

## Model
**Multiple Linear Regression** is used to predict the car price based on the above features. The model assumes a linear relationship between the dependent variable (price) and the independent variables (features).



## Technologies Used
- **Python**: Programming language
- **scikit-learn**: For building and evaluating the regression model
- **pandas**: For data manipulation and analysis
- **NumPy**: For numerical computations
- **Matplotlib & Seaborn**: For data visualization


