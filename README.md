# Uber-Fare-Prediction

The objective is to predict Uber fare prices using Machine Learning.

The dataset has the following information:

key - a unique identifier for each trip  
fare_amount - the cost of each trip in USD
pickup_datetime - date and time when the meter was engaged
passenger_count - the number of passengers in the vehicle (driver entered value)
pickup_longitude - the longitude where the meter was engaged
pickup_latitude - the latitude where the meter was engaged
dropoff_longitude - the longitude where the meter was disengaged
dropoff_latitude - the latitude where the meter was disengaged


From there, more features were created based on the date and time at the start of the uber race, also getting the distance information from latitude and longitude using haversine distance formula.

The models used were: Linear Regression, Lasso, Ridge, Elastic Net, KNN, Random Forest.
The idea was to maximize the prediction capacity, but as in the end of the analysis, all models had similar performance metrics (MSE, MAE and R²), the preference was the Lasso model because it also has excellent interpretability.

Dataset: https://www.kaggle.com/datasets/yasserh/uber-fares-dataset
