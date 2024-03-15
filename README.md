### 1. Introduction
Each step of the process has been complete in this Jupyter Notebook: 

#### 1.1 Project Overview
For this Kaggle competition, the objective is to predict customer churn within the banking sector, focusing on whether customers continue or terminate their accounts. The aim is to create a model that can predict the probability of a customer leaving the bank. This project is pivotal for strategic customer retention efforts, allowing for targeted interventions to enhance customer satisfaction and loyalty.

The task is to leverage a machine learning model to parse through customer data and predict churn probabilities. The model's performance will be evaluated based on the area under the Receiver Operating Characteristic (ROC) curve, assessing the model's ability to distinguish between the churned and retained customer categories across all possible thresholds. This measure will offer insights into the model's effectiveness at ranking predictions correctly and its viability for practical use in diverse real-world scenarios.


#### 1.2 Objective
The primary objective of this project is to predict the probability of a customer exiting the bank's services. The challenge is to employ machine learning techniques to process and analyze the data, ultimately developing a robust model capable of predicting churn. The evaluation metric, the area under the ROC curve, will guide the model optimization efforts, ensuring a focus on improving both the sensitivity and specificity of the predictions.


#### 1.3 Data Source
The dataset for this competition comprises both training and test sets, generated from a deep learning model trained on real-world customer churn data.

The training dataset (train.csv) includes various customer attributes along with the binary target variable Exited, indicating whether a customer has churned.

The test dataset (test.csv) contains similar customer attributes but requires participants to predict the probability of Exited.

Key attributes in the dataset include Customer ID, Surname, Credit Score, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, and the target, Exited.
