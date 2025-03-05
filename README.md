Bike Demand Prediction - Multiple Linear Regression
Overview
This project aims to build a Multiple Linear Regression model to predict the demand for shared bikes based on various independent factors. The dataset is provided by BoomBikes, a bike-sharing service provider, to understand demand patterns and optimize their business strategy post-pandemic.
Dataset Information
The dataset (day.csv) consists of daily records of bike rentals and includes features such as:
•	Season, Weather Conditions, Temperature, Humidity, Wind Speed, etc.
•	Casual Users and Registered Users (summed into the target variable cnt)
•	Working Day and Holiday indicators
Objective
The goal is to:
1.	Identify significant variables affecting bike demand.
2.	Build a regression model to predict the total rental count (cnt).
3.	Evaluate model performance using R-squared Score and Mean Squared Error (MSE).
Steps Followed
1.	Data Preprocessing
o	Load and inspect the dataset.
o	Convert categorical variables (season, weathersit) into dummy variables.
o	Remove unnecessary columns (instant, dteday, casual, registered).
2.	Exploratory Data Analysis (EDA)
o	Check data distribution and correlations.
o	Visualize demand trends across seasons, weather conditions, etc.
3.	Model Building
o	Perform train-test split (80-20 ratio).
o	Train a Multiple Linear Regression model using sklearn.
4.	Model Evaluation
o	Compute R² Score and Mean Squared Error (MSE).
o	Perform Residual Analysis to check model assumptions.
Results
•	R² Score: Measures how well the model explains variance in demand.
•	MSE: Indicates the average error in predictions.
•	Residual Analysis: Ensures model assumptions are met.

