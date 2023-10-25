# Time Series Forecasting
## Introduction
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.

Goals:
- The RMSE metric on the test set should not be more than 48.

Data source:
- `taxi.csv`

Data description:
- `datetime` — timestamp
- `num_orders` — number of orders

Plan:
1. Download the data and resample it by one hour.
2. Analyze the data.
3. Train different models with different hyperparameters.
4. Test the data using the test sample and provide conclusions.
