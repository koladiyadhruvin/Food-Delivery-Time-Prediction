# Food Delivery Time Prediction

## Overview
This repository contains the EDA and prediction of delivery time using machine learning algorithms.

Food Delivery services like Zomato and Swiggy need to show the accurate time it will take to deliver your order to keep transparency with their customers. These companies use Machine Learning algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

## Description

To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.

So, for this task, we need a dataset containing data about the time taken by delivery partners to deliver food from the restaurant to the delivery location. I found an ideal dataset with all the features for this task.

## Dataset
[Food Delivery Time Prediction Dataset](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset?select=train.csv)

## Libraries used

- **Pandas** : For data manipulation and analysis.
- **Numpy** : For numerical operations on dataset.
- **Plotly** : For data visualization.
- **Scikit-Learn** : For building machine learning models.

## Regression Models used
- Linear Regression
- Ridge
- Decision Tree
- SVM (Support Vector Machine)
- Random Forest
- Gradient Boosting
- XBGRegreesor

## Screenshots
![Delivery Person Age](https://github.com/koladiyadhruvin/Food-Delivery-Time-Prediction/blob/main/delivery%20person%20age.png)

![Destination city count](https://github.com/koladiyadhruvin/Food-Delivery-Time-Prediction/blob/main/Destination%20city%20count.png)

![Time ordered hour](https://github.com/koladiyadhruvin/Food-Delivery-Time-Prediction/blob/main/time%20ordered%20hour.png)

![Models R2 Scores](https://github.com/koladiyadhruvin/Food-Delivery-Time-Prediction/blob/main/models%20r2%20Score.png)
