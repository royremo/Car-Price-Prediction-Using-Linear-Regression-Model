# Car-Price-Prediction-Using-Linear-Regression-Model

This project aims to predict car prices based on various features using a linear regression model. The dataset used for this project contains information about different cars such as make, model, year, mileage, engine size, fuel type, transmission type, and number of previous owners.

Dataset
The dataset used for this project can be found in data.csv file. It consists of the following columns:

Make: The brand or manufacturer of the car.
Model: The specific model of the car.
Year: The manufacturing year of the car.
Mileage: The total distance the car has been driven (in miles).
Engine Size: The size of the car's engine (in liters).
Fuel Type: The type of fuel used by the car (e.g., petrol, diesel).
Transmission Type: The type of transmission in the car (e.g., manual, automatic).
Number of Previous Owners: The number of previous owners the car has had.
Price: The price of the car (target variable).
Approach
Data Preprocessing: The dataset is preprocessed to handle missing values, encode categorical variables, and normalize numerical features.
Feature Selection: Relevant features are selected based on correlation analysis and domain knowledge.
Model Training: A linear regression model is trained using the preprocessed data.
Model Evaluation: The model's performance is evaluated using metrics such as mean squared error (MSE) and R-squared.
Deployment: The trained model can be deployed for making price predictions for new car listings.
