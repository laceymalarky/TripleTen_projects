# Forecasting Customer Churn
## Project Overview
A telecom operator would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. They provided access to some of their clientele's personal data, including information about their plans and contracts. I built a classification model to identify clients that will churn in the future and loyal customers that will not churn.

## Machine Learning Skills/Technologies
Classification models (Logistic Regression, Decision Tree, Random Forest, XGBoost, CatBoost), Cross-validation, Hyperparameter tuning, Feature Encoding, Feature Engineering, Upsampling (SMOTE)

## Project Conclusions
- Developed a predictive [classification model](https://github.com/laceymalarky/TripleTen_projects/blob/main/churn_classification/churn_model.ipynb) that resulted in a 12% improvement in performance, achieving a 0.93 AUC-ROC score and an accuracy of 88%, enabling the company to proactively address customer churn and retain valuable clients.
- Performed time series analysis to reveal that the churn rate increased from 8% to 47% over the past 6 years with monthly seasonal swings of 9%.
- Analyzed and pre-processed raw data, applied feature encoding and engineering to prepare features for modeling.

![image](https://github.com/laceymalarky/TripleTen_projects/assets/97048468/09977dad-87ff-4602-b58b-10d00895bc4b)
 
## Requirements
Python libraries: pandas, numpy, matplotlib, seaborn, statsmodels, imblearn, scikit-learn, xgboost, catboost

## Data Description:
- training and testing set containing 7,043 observations
