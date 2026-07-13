# goit_data_Hw3

# Housing Price Prediction

This project is a practice implementation of linear regression.

The goal is to predict house prices using three features: area, number of bedrooms, and number of bathrooms.

The target variable is the house price.

## Data Preparation

First, I load the housing dataset and select the columns needed for the model.

The selected features are:

- area
- bedrooms
- bathrooms

The target variable is:

- price

## Data Visualization

Before building the model, I visualize the data to better understand the relationship between the selected features and the house price.

The first plot shows how the house price depends on the area.

## Linear Regression Idea

The model will try to describe the house price as a linear combination of the selected features.

In simple form:

price ≈ w0 + w1 × area + w2 × bedrooms + w3 × bathrooms

Here, w0 is the intercept, and w1, w2, w3 are the model parameters.

## Matrix Form

For vectorized linear regression, the data is represented as a feature matrix X and a target vector y.

The hypothesis can be written as:

h(x) = Xw

where X is the feature matrix, w is the parameter vector, and h(x) is the predicted price.
