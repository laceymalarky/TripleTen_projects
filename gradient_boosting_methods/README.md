## Introduction

Rusty Bargain used car sales service is developing an app to attract new customers. In that app, a customer can quickly find out the market value of a car. We have access to historical data including technical specifications, trim versions, and prices. I will build a regression model to determine a car's value.

**Data source:**
- `car_data.csv`

**Data Description:**
- Features
    - `DateCrawled` — date profile was downloaded from the database
    - `VehicleType` — vehicle body type
    - `RegistrationYear` — vehicle registration year
    - `Gearbox` — gearbox type
    - `Power` — power (hp)
    - `Model` — vehicle model
    - `Mileage` — mileage (measured in km due to dataset's regional specifics)
    - `RegistrationMonth` — vehicle registration month
    - `FuelType` — fuel type
    - `Brand` — vehicle brand
    - `NotRepaired` — vehicle repaired or not
    - `DateCreated` — date of profile creation
    - `NumberOfPictures` — number of vehicle pictures
    - `PostalCode` — postal code of profile owner (user)
    - `LastSeen` — date of the last activity of the user
- Target
    - `Price` — price (Euro)

### Plan:
1. Exploratory Data Analysis
2. Data Preparation
3. Train Regression models with hyperparameter tuning and assess performance
    - Linear Regression (as a baseline)
    - Decision Tree
    - Random Forest
    - LightGBM
    - CatBoost
    - XGBoost
4. Compare models in terms of quality and speed of training and prediction