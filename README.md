# BrainStation Capstone Project

## BikeShare Toronto Analysis

This project consists of 4 parts:
Part 1 - Data Cleaning and EDA
Part 2 - Machine Learning Model
Part 3 - Time Series Analysis
Part 4 - Network Analysis


### Part 1 - Data Cleaning and EDA
Gathered data from several sources, cleaned it by imputation and/or removed any null values then combined the datasets together as my main working dataset. Afterwards I completed exploratory data analysis (EDA) to gain some basic insights into the cleaned dataset.

### Part 2 - Machine Learning Model
Created Logistic Regression Machine Learning models on the cleaned dataset to see if I can answer the question of whether `we can predict if a bikeshare user is going to bring the bike back late`. Before I create and fit logistic regression model, I needed to do some feature engineering on the dataset and create a binary classifier for our dependent variable. Then I undersampled the the data because it was imbalanced with over 94% of data being negative after the binary cliassifer was created. Once the model was made and the optimal scaler was used, I received a test accuracy of 95.3% using a subsampled dataset. The F1 score for both positive and negative classes were 0.95

### Part 3 - Time Series Analysis
Created a prediction model using an Auto-Regressive, Integrated, Moving Average (ARIMA) Model and then evaluating the model by taking the Root Mean Square Error (RMSE).

### Part 4 - Network Analysis
Completed a network analysis on the cleaned dataset to gain insights into the relationship between each station in the network created by bikeshare users.
