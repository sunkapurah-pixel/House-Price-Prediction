# House Price Prediction

## Overview

This project aims to build a Machine Learning regression model to predict house prices based on various housing features such as location, median income, total rooms, population, and other attributes.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, evaluation, and prediction.

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/bhanupratapbiswas/house-price-prediction

The dataset contains housing information collected from different regions and includes several numerical and categorical features.

### Features

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity

### Target Variable

* Median House Value

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

* Loaded the housing dataset using Pandas.

### 2. Exploratory Data Analysis (EDA)

* Dataset inspection
* Missing value analysis
* Correlation analysis
* House price distribution visualization

### 3. Feature Engineering and Transformation

* Handled missing values
* Log transformation
* One-Hot Encoding for categorical variables
* Feature Scaling using StandardScaler

### 4. Model Building

The following regression algorithms were implemented and compared:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

### 5. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Residual Analysis

Residual plots were generated to analyze model performance and prediction errors.

### 7. Best Model Selection

The best-performing model was selected based on evaluation metrics.

### 8. Model Saving

The trained model was saved using Joblib for future predictions.

## Results

The best model achieved good predictive performance on the test dataset with low RMSE and MAE values.
<img width="972" height="787" alt="image" src="https://github.com/user-attachments/assets/58fbfc48-0e4e-46d8-b5c9-6c3d5d2413ba" />

<img width="695" height="437" alt="image" src="https://github.com/user-attachments/assets/503bba9f-e6a5-4819-8522-ebb2fcd03da4" />

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Deployment using Flask or Streamlit

## Author

Hanumakshi
