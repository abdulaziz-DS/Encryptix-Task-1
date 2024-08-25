# Encryptix Task 1: Movie Rating Prediction

## Overview
This project focuses on building a predictive model that estimates the rating of movies based on various features such as genre, director, and actors. The primary goal is to analyze historical movie data and develop a machine-learning model that accurately predicts movie ratings as given by users or critics.

## Dataset
The dataset used in this project is based on Indian movies and includes features such as movie titles, genres, directors, actors, and corresponding user ratings. The dataset was provided in CSV format, and the necessary preprocessing steps were applied to prepare it for modeling.

## Project Structure
- **Data Preprocessing**: The dataset was cleaned and preprocessed to handle missing values, categorical variables, and irrelevant columns. One-hot encoding was used for categorical features like genre, director, and actors.
- **Feature Engineering**: Additional features were created where necessary to improve model performance. For instance, genres were split and treated as individual binary features.
- **Modeling**: A regression model was built to predict movie ratings. The model was trained using historical data and then evaluated on a test set.
- **Evaluation**: The model's performance was assessed using the Root Mean Squared Error (RMSE) metric.

## Model and Results
The model used was a regression model that was trained and evaluated on the preprocessed data. The performance of the model was measured using the RMSE metric, and the results are as follows:

- **Root Mean Squared Error (RMSE)**: `1.2348`

### Insight:
- The RMSE of `1.23` suggests that, on average, the predicted movie ratings deviate from the actual ratings by approximately 1.23 units on a scale of 1 to 10.
- This level of error indicates that the model has a reasonable predictive ability but also leaves room for further improvement.
