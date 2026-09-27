# 🏠 House Price Prediction

A Machine Learning project that predicts house prices based on different house features.

## 📌 Project Overview

The goal of this project is to build a Machine Learning model that can predict the price of a house using features such as area, number of bedrooms, bathrooms, parking, age of the house, and location.

This project was created as my first practical Machine Learning project.

## 📊 Dataset

The dataset contains 500 house records.

### Features

- `area_sqft` - Area of the house in square feet
- `bedrooms` - Number of bedrooms
- `bathrooms` - Number of bathrooms
- `parking` - Number of parking spaces
- `age_years` - Age of the house
- `location` - Location of the house

### Target

- `price` - House price

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Project Workflow

1. Load the dataset
2. Understand the dataset
3. Check missing values
4. Check duplicate values
5. Perform Exploratory Data Analysis (EDA)
6. Analyze feature correlations
7. Encode the categorical `location` feature using One-Hot Encoding
8. Separate features (`X`) and target (`y`)
9. Split the data into training and testing sets
10. Train a Linear Regression model
11. Make predictions
12. Evaluate the model

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression was used to predict house prices.

The dataset was split into:

- 80% training data
- 20% testing data

## 📈 Model Results

| Metric | Result |
|---|---:|
| RMSE | 174,416.46 |
| R² Score | 0.9966 |

The model achieved an R² score of approximately **99.66%** on the test dataset.

## 🧠 What I Learned

Through this project, I practiced:

- Data preprocessing
- Exploratory Data Analysis
- Correlation analysis
- One-Hot Encoding
- Train/Test Split
- Linear Regression
- Model prediction
- MSE
- RMSE
- R² Score
- Basic Machine Learning workflow

## 🚀 Future Improvements

- Try other regression algorithms
- Compare multiple models
- Perform hyperparameter tuning
- Deploy the model as a web application

## 👨‍💻 Author

**Gopi Nath**

B.Tech Artificial Intelligence & Data Science
