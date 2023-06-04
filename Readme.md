# Title
Telecom Churn Prediction

# Description
A leading telecom firm from Southeast Asia has collected customer-level data pertaining to the use of its services for a span of four consecutive months encoded as 6, 7, 8 and 9.

The goal of the analytics project is to
- predict customer churn in the 9th month using data from the preceding 3 months, and
- identify the important predictors of customer churn.

The findings will be used to develop strategies to manage customer churn.

# Approach to Analysis
Analysis is performed as per the following steps:

**Data Cleaning, Feature Engineering & EDA**
- Data Understanding & Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Preparation

**Prediction**
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Model Selection

**Inference**
- Model Building
- Model Evaluation
- Model Interpretation

**Strategies to Manage Churn**

# Results
The XGBoost classifier is finalised from among the 3 prediction models because it has the best cross-validation ROC-AUC and Recall scores of 0.895 and 0.78.

The multiple logistic regression model finalised for inference has 19 explanatory variables and the following performance metrics:
| Metric | Training | Test |
|--------|----------|------|
| Accuracy | 0.837102 | 0.832408 |
| Precision | 0.328202 | 0.319862 |
| Recall | 0.845730 | 0.834190 |