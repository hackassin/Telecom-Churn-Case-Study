# Telecom-Churn-Case-Study
## Problem Statement

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this project, you will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

## Model Building & Business Problem Solving Steps

1. Preprocess data (convert columns to appropriate formats, handle missing values, etc.)

2. Conduct appropriate exploratory analysis to extract useful insights (whether directly useful for business or for eventual modelling/feature engineering).

3. Derive new features.

4. Reduce the number of variables using PCA.

5. Train a variety of models, tune model hyperparameters, etc. (handle class imbalance using appropriate techniques).

6. Evaluate the models using appropriate evaluation metrics. Note that is is more important to identify churners than the non-churners accurately - choose an appropriate evaluation metric which reflects this business goal.

7. Finally, choose a model based on some evaluation metric.

8. Use the best model to fit on the training data and deduce the topmost features that will influence the business decision for customer churn. 

## Learning Algorithms Used
1. Logistic Regression
2. Random Forest
3. XGBoost


## Insights
As per the analysis, we can conclude the following about model-building and evaluation:

1. Going for simpler models can alsp help us achieve satisfying results. Complex models in this case, don't exhibit a significant increase in performance.
2. Logistic regression for PCA dataset followed by a lasso-regression can help us in cross-evaluating model performance and feature selection in this scenario.
3. Classification report that highlights the F1-Score, Precision and Recall, along with AUC-Score seem to be good evaluation metrics.
