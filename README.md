# Airline Passenger Evaluation
This project focuses on predicting passenger satisfaction and loyalty within the airline industry using data mining techniques. The analysis is conducted using the Orange Data Mining tool, with a primary emphasis on understanding and predicting customer satisfaction and churn risk.

## Project Overview
The objective of this project is to develop a predictive model that classifies airline passengers based on their satisfaction level and loyalty. By leveraging data mining techniques, it  aims to provide actionable insights that can help airlines improve customer retention and enhance service quality.
### Key Objectives
*Classify Passengers*: Accurately classify passengers based on their satisfaction with the airline service.
*Predict Churn Risk*: Estimate the likelihood of passengers discontinuing their services with the airline.
*Targeted Customer Segmentation*: Segment customers based on loyalty to provide personalized experiences.

## Business Problem
● One of the leading causes of customer service decline in air travel is that more customers are demanding compensation for delays and poor service. Due to an increase in customer expectations, airlines are dealing with more and more customers contacting them.

● Airlines operate in a fiercely competitive environment where customer experience is utmost important. Unfortunately, many airlines struggle with high customer churn, meaning passengers who stop flying with them. 

● This churn translates to lost revenue and a weakened brand image. To stay ahead, airlines need to understand the factors that most influence customer satisfaction and loyalty. This 
project aims to identify these key factors so airlines can make data-driven decisions to improve their services, retain passengers by increasing customer satisfaction and reduce 
customer churn.

## Data Understanding and Exploration
### Data Source: The files attached above were leveraged from [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
The dataset used in this project is sourced from Kaggle and contains 25 features with approximately 130,000 data points. The data provides a comprehensive view of various factors influencing passenger satisfaction.
### Exploratory Data Analysis (EDA)
The project includes a Jupyter notebook (.ipynb file) that covers all the necessary data visualizations for EDA. This analysis helps in uncovering insights and extracting relevant features required for building the predictive models.

## Data Mining and Modelling
In this project, we employed multiple classification models to predict two key aspects of airline passengers.
### Classification - 1: Passenger Satisfaction
A comparison was conducted between six different classification models to classify passengers into two categories: satisfied and neutral/dissatisfied. The models compared include:
Logistic Regression
Random Forest
k-Nearest Neighbors (kNN)
Neural Networks
Naive Bayes
Support Vector Machine (SVM)

### Classification - 2: Passenger Loyalty
For predicting passenger loyalty, five different classification models were used to classify passengers into two categories: loyal and disloyal. The models compared include:
Logistic Regression
Random Forest
k-Nearest Neighbors (kNN)
Neural Networks
Naive Bayes

These models were evaluated based on their accuracy, precision, recall, and F1 score to determine the most effective approach for each classification task. Below is the outline of the process done on Orange.
![image](https://github.com/user-attachments/assets/f3715c5d-3137-4410-8240-e9b78e246080)

Orange: 3.36.2
Python: 3.9.12
