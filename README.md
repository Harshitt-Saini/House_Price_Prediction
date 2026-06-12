# House Price Prediction Using Linear Regression

## Project Overview

This project focuses on predicting house prices using Machine Learning. A Linear Regression model is trained on a housing dataset containing features such as area, number of bedrooms, bathrooms, stories, parking availability, and furnishing status. The model learns the relationship between these features and house prices to make accurate predictions.

## Objective

The main objective of this project is to build a regression model that can predict house prices based on housing characteristics and evaluate its performance using standard regression metrics.

## Dataset

The dataset contains the following features:

- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Loading
The housing dataset is loaded into a Pandas DataFrame for analysis and processing.

### 2. Exploratory Data Analysis (EDA)
- Examined dataset structure and statistics
- Checked data types
- Identified missing values
- Analyzed feature distributions

### 3. Data Visualization
- House Price Distribution Plot
- Correlation Heatmap

### 4. Data Preprocessing
- Checked for missing values
- Converted categorical features into numerical format using One-Hot Encoding
- Prepared input and target variables

### 5. Train-Test Split
The dataset was divided into:
- 80% Training Data
- 20% Testing Data

### 6. Feature Scaling
StandardScaler was used to normalize feature values for better model performance.

### 7. Model Training
A Linear Regression model was trained using the training dataset.

### 8. Prediction
The trained model was used to predict house prices on the test dataset.

### 9. Model Evaluation
The model was evaluated using:

- Mean Squared Error (MSE)
- R² Score

### 10. Result Visualization
A scatter plot was generated to compare actual and predicted house prices.

## Results

| Metric | Value |
|----------|----------|
| Mean Squared Error (MSE) | 1754318687330.6677 |
| R² Score | 0.6529242642153177 |

## Project Structure
