# Customer-Attrition


### Project Overview

Customer churn is a very important process in any firm. And the importance of Data Science here is never overstated.
The cost of customer retention is much higher than customer acquisition
To achieve this, its important to analyze the customer behaviour and run predictive analysis on these elements. In this project, we'll make a customer churn model.

### Data Sources

The dataset used is obtained from Kaggle website.
Here, we are using a dataset having columns Row number, Customer ID, Surname, Credit score, Geography, Gender, Age, Tenure, Balance, No of products, Has credit card, Active member, Estimated salary, Exited with 1000 entries.
To make this dataset a little more interesting, I took some values from certain columns so that the dataset would contain some missing values

### Tools

- Google Colab


### ML algorithm

- Artificial Neural Network(ANN)


### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. After analysing, we know, that there are categorical data and some missing values in the dataset.Thus, we’ll be using label encoder for 'Gender' column and one-hot 'Geography' column.
3. Handling missing values by replacing them with mean values in the particular column
4. Here, we perform feature scaling after splitting the train and test data, right before fitting the ML algorithm.


### Exploratory Data Analysis

EDA involved exploring the dataset to answer key questions, such as: 
- What is the overall customer distribution as per nationality?
- How many are credit card users?
- How many are active users?


### Data Analysis

First, we split the dataset into the Training set and Test set and then initialize ANN and build the customer churn predictor model and then, fitting the ANN to the Training set. And ultimately, use it to predict for both train and test data
Also check for performance metrics for both the training and testing data


### Results/Findings

- This dataset has more customers from France as compared to Germany and Spain
- More than 50% of the customers are credit card users
- Very few customers have applied for more than 2 products
- 50% of the customers are active members

An interesting note is that, the performance of the ANN model is better on this dataset (with some missing values) and then handling the missing values rather than when performed on the same dataset without any missing values ie. original dataset.


