# Credit Card Approval Project

## Introduction

This project focuses on building a credit card approval system using customer data. The goal is to create a model that can effectively predict whether a credit card application should be approved or rejected. The project includes data preprocessing, exploratory data analysis, addressing class imbalance, and applying a logistic regression model for predictions.

## Dataset

The dataset used in this project contains customer data, including features such as income, age, employment history, and a custom variable "positive_status," which indicates a positive application status (1) or possible rejection (0).

## Imbalance Issue

During the exploratory analysis, we discovered a significant imbalance in the "positive_status" variable. There are very few cases of possible rejections (0), making it essential to address this imbalance to ensure the model's performance.

## Exploratory Data Analysis

We conducted an exploratory data analysis (EDA) to gain insights into the dataset. Key observations include:
- Gender imbalance: More applications from women are approved.
- Ownership of property: Applications from individuals who own property are more likely to be approved.
- Approval Criteria: We learned that a positive status (1) is a vital factor in credit card approval. We also considered other desirable characteristics.

## Approval Criterion

To create a robust approval criterion, we considered various characteristics such as income, positive status, years of employment, and more. The criterion was designed based on domain knowledge and research in the area.

## Logistic Regression Model

We implemented a logistic regression model to make predictions about credit card applications. The model achieved an F-score of 0.78, indicating good performance.

## Conclusion

In conclusion, this project addresses the challenge of building a credit card approval system from customer data. By tackling the class imbalance, conducting exploratory analysis, defining an approval criterion, and applying a logistic regression model, we've made significant progress towards building an effective credit card approval system.

For more details, check the Jupyter Notebook and source code included in this repository.

Feel free to explore the project and provide feedback!

## Author

Tomas Alejandro Sierra Cano

## Info

The data used in this project was extracted from: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction
