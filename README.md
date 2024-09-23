Introduction

This project analyzes the Austin Bikeshare Trips dataset using Google BigQuery and focuses on predicting the duration of bike trips. It demonstrates various SQL and machine learning techniques for analyzing data and building predictive models using BigQuery ML. Key techniques applied include:

- Feature Engineering - Transforming time-based features such as the day of the week and hour of the day into more meaningful categories (e.g., weekday/weekend).
-  Linear Regression Modeling - Building a predictive model to estimate the duration of bike trips based on several input features.
- Model Evaluation - Evaluating the model’s performance using metrics such as mean squared error (MSE) to improve the model iteratively.
- Bucketizing Features - Transforming continuous variables (such as the hour of the day) into buckets to enhance model performance.
- Prediction - Making predictions about bike trip durations for future or unseen data points.
- Model Interpretation - Examining model weights to understand feature importance and how each feature contributes to predictions.

The project involves creating multiple machine learning models in BigQuery ML, starting with a basic linear regression model and improving it by refining features and adding techniques like bucketization. The models are evaluated for performance, and predictions are made for new data points based on the learned model. The project shows how SQL and BigQuery ML can be used together for data science and predictive modeling.

