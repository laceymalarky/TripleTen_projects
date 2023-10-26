# Car Value Prediction using Gradient Boosting Models
## Project Overview
A used car sales service is developing an app to attract new customers. In that app, a customer can quickly find out the market value of a car. They provided access to historical data including technical specifications, trim versions, and prices. I will build a regression model to determine a car's value.

## Technologies
Regression models (Linear Regression, Decision Tree, Random Forest, XGBoost, LightGBM, CatBoost), Cross-validation, Hyperparameter tuning, Feature Encoding

## Project Conclusions
- Developed [boosting models](https://github.com/laceymalarky/TripleTen_projects/blob/main/gradient_boosting_methods/12_Numerical_Methods_Project.ipynb) to predict a car's value, achieving an 89% improvement in the evaluation metric (RMSE) from the baseline model.
- CatBoost is the recommended model since the RMSE is $304.52, just ~1.8% higher than LightGBM's but with a 70x faster prediction speed. The trade-off is a 70% longer training time than LightGBM, but it is still faster than the XGBoost model's traning time by about 25% and prediction time by 78%.
- Analyzed and pre-processed raw data, applied feature encoding to prepare features for modeling.
  
![image](https://github.com/laceymalarky/TripleTen_projects/assets/97048468/521addc2-1086-44f8-b895-c50284ef570b)
![image](https://github.com/laceymalarky/TripleTen_projects/assets/97048468/cb6b44c2-71e8-4ebf-b85d-34151cc8deb9)
 
## Requirements
Python libraries: pandas, numpy, matplotlib, sklearn, xgboost, lightgbm, catboost

## Data Description:
- training and testing set of 245,567 car records
  - `car_data.csv`
