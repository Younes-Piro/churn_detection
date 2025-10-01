# Churn Prediction Project

## Problem Statement

Customer churn is a critical issue in the banking industry, as acquiring new clients is significantly more expensive than retaining existing ones. 
Understanding the factors that influence a customer's decision to leave the bank enables organizations to design effective retention strategies and loyalty programs.

Churn for this use case is defined as follows:
> A churning customer is a whether or not the customer left the bank

The goal of this project is to develop a predictive model that can accurately identify which customers are likely to churn. 
By analyzing demographic, financial, and behavioral data—such as credit score, age, account balance, tenure, activity status, 
and satisfaction score—we aim to uncover patterns that differentiate loyal clients from those at risk of leaving.

Proactively detecting potential churners will help the bank:

- Reduce customer attrition rates
- Improve customer satisfaction and engagement
- Optimize targeted retention campaigns
- Increase overall profitability through long-term customer loyalty

## Introduction

Enclosed in this folder, there can be found my analysis that I did to this 
data provided that contain their client's listening behavior as well as their personal information. I have used
`seaborn` and `matplotlib` for generating the graphs. 

As for the feature engineering part, I have used : `pandas`. 

As for the modeling part, I have used `scikit-learn` , `XGBoost` and `CatBoost`. `scikit-learn` provides most of the implementations 
of state-of-the-art models (especially in supervised learning using tabular data).

### Motivation
The use of machine learning and data mining techniques has exploded during the last few years due the fact they enable
the business decisions takers to make wise decisions by taking into consideration the insights generated from them.

I have also made predictive models that are able to accurately predict which clients are more
likely to churn <br>
You can find the notebook of the modeling phase <a href="https://github.com/Younes-Piro/churn_detection/blob/main/Modelisation.ipynb">here</a>.

An extra step has been also made, which is the Clustering of the clients (also called Clients Segmentation),
where the goal is to group together clients that have the same profile / behavior. <br>
The notebook for the Clustering phase can be found <a href="https://github.com/Younes-Piro/churn_detection/blob/main/clustring.ipynb">here</a>.

Having access to both EDA and the predictive model is very useful for the company to make intelligent decisions 
about what they should do in order to keep their customers.

