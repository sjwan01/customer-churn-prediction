# Amazon Customer Churn Prediction Challenge

## Background

Customer churn refers to the loss of customers for any reason. When business lose customers, they simultaneously lose sources of revenue, and to mitigate that loss, they have to invest extra resources coming up with solutions to attract more customers. Hence, it is essential for business to understand customer churn and deal with it at the very beginning.

Machine learning models is a tool for business to explain customer's churning behavior. They could predict whether a customer is about to stop their subscription and further explain what factors lead to the decision given the available data. With these insights, business can improve their services and marketing strategies accordingly and thus retain their customers.

In this project, we assume the role of a marketing analyst in the marketing department of a mobile phone operator. Given the service usage and other customer behavior data, we aim to identify customers potentially at risk of churning and explain why they would leave.

## Data

The dataset is in this repository, and it can also be found in this [__*AWS Machine Learning Blog*__](https://aws.amazon.com/blogs/machine-learning/predicting-customer-churn-with-no-code-machine-learning-using-amazon-sagemaker-canvas/).

This is a synthetic dataset from a telecommunications mobile phone carrier. It contains 5,000 records with 21 features describing the customer profile. The full description of these features can be found in the blog.

The `Churn?` variable is the target feature to be predicted.

## Goals

In the blog, the synthetic dataset is used as an example to showcase the power of [__*Amazon SageMaker Canvas*__](https://aws.amazon.com/sagemaker/canvas/?sagemaker-data-wrangler-whats-new.sort-by=item.additionalFields.postDateTime&sagemaker-data-wrangler-whats-new.sort-order=desc). Canvas provides a simple interface which allows users to build a customer churn machine learning model without any programming. The blog states that the model could score a 97.9% accuracy on this synthetic dataset at its best - although it takes 2-4 hours to train and select the best model. Through data analysis, we want to explore:
- __*Can our choice of model score a similar accuracy rate?*__
- __*Which features are the most influencial in determining whether a customer will churn?*__
