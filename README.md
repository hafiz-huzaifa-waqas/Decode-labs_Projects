# Decode-labs_Projects

# E-Commerce Sales Analytics & Revenue Prediction

## Overview

This project analyzes an e-commerce sales dataset to uncover business insights and build machine learning models capable of predicting order revenue (`TotalPrice`).

The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, visualization, preprocessing, and regression model training.

## Dataset Features

The dataset contains information related to:

* Orders and products
* Payment methods
* Order status
* Referral sources
* Coupon usage
* Quantity and pricing information
* Order dates

## Project Workflow

1. Load and inspect the dataset
2. Handle missing values
3. Check for duplicate records
4. Perform exploratory data analysis (EDA)
5. Extract date-based features
6. Encode categorical variables
7. Scale numerical features
8. Train regression models
9. Compare model performance

## Visual Analysis

The project explores:

* Sales trends over time
* Yearly and monthly revenue trends
* Weekday sales patterns
* Revenue by product
* Revenue by referral source
* Revenue by order status
* Payment method spending behavior
* Feature correlations

## Machine Learning Models

The following regression models were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

## Results

| Model                   | R² Score   |
| ----------------------- | ---------- |
| Linear Regression       | 0.8902     |
| Decision Tree Regressor | 0.9989     |
| Random Forest Regressor | **0.9997** |

### Best Performing Model

**Random Forest Regressor** achieved the highest accuracy with an R² score of **99.97%**, making it the most effective model for predicting sales revenue in this dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Conclusion

The analysis reveals key sales patterns and customer behavior trends while demonstrating that ensemble learning techniques, particularly Random Forest, provide highly accurate revenue predictions for this e-commerce dataset.
