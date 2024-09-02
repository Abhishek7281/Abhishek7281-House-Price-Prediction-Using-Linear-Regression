# Abhishek7281-House-Price-Prediction-Using-Linear-Regression

This repository contains a Jupyter Notebook that demonstrates how to predict house prices using linear regression. The project involves data preprocessing, model training, and evaluation using a dataset containing various features of houses.

# Project Overview
The goal of this project is to build a machine learning model that can predict house prices based on several features such as area, number of bedrooms, bathrooms, and more. The primary algorithm used for this prediction is Linear Regression.

# Dataset
The dataset used for this project contains various attributes related to houses, including:

price: The price of the house (target variable).

area: The area of the house in square feet.

bedrooms: The number of bedrooms.

bathrooms: The number of bathrooms.

stories: The number of stories.

mainroad: Whether the house is on the main road.

guestroom: Whether the house has a guest room.

basement: Whether the house has a basement.

# Steps Followed

# 1. Importing Libraries
The first step involves importing necessary libraries for data manipulation, visualization, and model building. Key libraries include:

pandas for data manipulation

numpy for numerical computations

matplotlib for data visualization

scikit-learn for model building and evaluation

# 2. Loading the Dataset
The dataset is loaded using pandas and explored to understand the structure and contents.

# 3. Data Preprocessing
Feature Scaling: Features are scaled using MinMaxScaler to ensure they are on a similar scale, which is important for linear regression.

Splitting the Data: The dataset is split into training and testing sets to evaluate the performance of the model.

# 4. Model Training
The linear regression model is trained using the training data.

# 5. Model Evaluation
The model is evaluated on the test set using the Mean Squared Error (MSE) metric to assess its accuracy.

# 6. Visualization
The relationship between the predicted and actual house prices is visualized to assess the model's performance.

# 7. Conclusion
The linear regression model provides a basic yet effective method for predicting house prices based on the given features. This model can be improved further with more complex algorithms or by incorporating additional features.

# Dependencies
To run the notebook, ensure you have the following dependencies installed:
pip install pandas numpy matplotlib scikit-learn
