# Property Price Prediction Website

This project provides a step-by-step process of building a Property price prediction website. The aim is to create a model using scikit-learn and linear regression, using the Bangalore Property prices dataset from Kaggle. The project also involves developing a Python Flask server to serve HTTP requests and a website built with HTML, CSS, and JavaScript for user interaction.

# Property Price Prediction with Linear Regression

Linear regression is a supervised machine learning algorithm used for predicting a continuous target variable based on one or more input features. It assumes a linear relationship between the input variables and the target variable. In other words, it aims to find the best-fitting line that minimizes the difference between the predicted and actual values.

## Problem Statement

In this project, we aim to predict property prices based on various features such as the area, number of bedrooms, number of bathrooms and Location. By using linear regression, we can build a predictive model that estimates the property price based on these features.

## Dataset

We have a large dataset from that we need these fetures for extracting information for several properties:

- Area (in square feet)
- Number of bedrooms
- Number of bathrooms
- Location

## Implementation

To implement property price prediction with linear regression, we can follow these steps:

1. Load the dataset and split it into input features (X) and target variable (y).
2. Create a linear regression model using a library like scikit-learn.
3. Train the model by fitting it to the training data.
4. Use the trained model to make predictions on new data.
5. Evaluate the performance of the model using suitable metrics such as mean squared error or cross validation.

Feel free to customize the code provided in this repository to fit your specific needs and incorporate it into your project.


## Project Overview

The project follows the following steps:

1. Building a model using scikit-learn and linear regression with the Bangalore home prices dataset from [Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data).
2. Writing a Python Flask server that uses the trained model to serve HTTP requests.
3. Creating a website using HTML, CSS, and JavaScript that allows users to enter home square footage, bedrooms, etc., and retrieves the predicted price by calling the Flask server.

The model building process covers various data science concepts such as data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, hyperparameter tuning using GridSearchCV, and k-fold cross-validation.

## Technology and Tools

The project uses the following technologies and tools:

1. Python
2. NumPy and Pandas for data cleaning
3. Matplotlib for data visualization
4. scikit-learn for model building
5. Jupyter Notebook, Visual Studio Code, and PyCharm as IDEs
6. Python Flask for the HTTP server
7. HTML/CSS/JavaScript for the user interface

## Output

The image below shows an example output of the prediction:

![Prediction Output](https://github.com/sdrahmath/Property-Price-Prediction/blob/main/BHP/output.png)


## Conclusion

Linear regression is a powerful algorithm for property price prediction. By leveraging the relationships between input features and property prices, we can create a model that accurately estimates the price of a property based on its characteristics.

This project provides a practical implementation of building a Property price prediction website. By following the step-by-step process and utilizing the mentioned technologies and tools, you can create your own website for property price prediction. Feel free to explore the provided code and make further enhancements as desired.
For more details and implementation examples, refer to the documentation and resources available in this repository.


## Kaggle Data set link
(https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
