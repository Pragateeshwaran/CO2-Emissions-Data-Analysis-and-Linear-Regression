# CO2 Emissions Data Analysis and Linear Regression


This project involves the analysis of CO2 emissions data and the development of a linear regression model to predict CO2 emissions based on various vehicle features. The dataset used in this project contains information about vehicle specifications and their corresponding CO2 emissions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Linear Regression Model](#linear-regression-model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction

In this project, we aim to understand the relationship between vehicle specifications and their carbon dioxide (CO2) emissions. We use a linear regression model to predict CO2 emissions based on features such as engine size, number of cylinders, fuel consumption, and vehicle make.

## Dataset

The dataset used for this project is named "CO2 Emissions.csv" and contains the following columns:

- Make
- Model
- Vehicle Class
- Engine Size (L)
- Cylinders
- Transmission
- Fuel Type
- Fuel Consumption City (L/100 km)
- Fuel Consumption Hwy (L/100 km)
- Fuel Consumption Comb (L/100 km)
- Fuel Consumption Comb (mpg)
- CO2 Emissions (g/km)

## Exploratory Data Analysis

We start by performing exploratory data analysis (EDA) to gain insights into the dataset. Key EDA tasks include summary statistics, data types, and checking for missing values.

## Data Preprocessing

In the data preprocessing phase, we perform the following tasks:

- Handling categorical data: Encoding the "Fuel Type" column based on CO2 emissions ranking.
- Data filtering: Removing outliers from the dataset.
- Feature selection: Selecting relevant features for the regression model.

## Linear Regression Model

We build a linear regression model to predict CO2 emissions using the selected features. The steps include:

- Data splitting: Splitting the data into training and testing sets.
- Model creation: Developing a linear regression model using the scikit-learn library.
- Model training: Training the model on the training data.
- Model evaluation: Assessing the model's performance using various metrics, such as R-squared, MAE, MSE, and RMSE.

## Evaluation

The model evaluation results are as follows:

- R-squared (R^2): 0.8831
- Adjusted R-squared: 0.8826
- Mean Absolute Error (MAE): 13.15
- Mean Squared Error (MSE): 402.40
- Root Mean Squared Error (RMSE): 20.06

These metrics provide insights into the model's goodness of fit and accuracy in predicting CO2 emissions.

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or find issues, please create a pull request or open an issue.


