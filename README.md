# Ecommerce Sales Regression Analysis

## Project Overview

This project applies statistical analysis and machine learning techniques to an ecommerce sales dataset containing 5,000 observations. The objective is to examine the factors associated with sales revenue and develop regression models for predicting revenue.

The project follows a structured machine learning workflow, from data preparation and exploratory data analysis to model development, validation, hyperparameter tuning and evaluation.

## Dataset

- **Observations:** 5,000
- **Variables:** 12
- **Target variable:** Revenue
- **Format:** CSV

The dataset contains information on product categories, geographical regions, quantities sold, unit prices, discounts, delivery times, customer ratings and revenue.

## Methods and Models

The analysis includes:

- Data cleaning and quality assessment
- Exploratory data analysis (EDA)
- Correlation analysis and visualisation
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- 10-fold cross-validation
- GridSearchCV hyperparameter tuning
- Model evaluation using MAE, RMSE and R²

## Tools and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Git

## Project Structure

```text
Project_1_Regression/
├── data/
│   └── ecommerce_sales_analytics_5000.csv
├── Project_1_Regression.ipynb
├── README.md
└── .gitignore
```

## Important Modelling Note

Revenue in this dataset is mathematically determined by quantity, unit price and discount. Consequently, the strong predictive performance should be interpreted in the context of reconstructing this revenue calculation rather than forecasting independently generated future sales.

## Project Status

The primary regression analysis, model comparison, cross-validation and hyperparameter tuning have been completed. Documentation, version control and deployment-related learning extensions are ongoing.

## Author

Michael Faraday Otieno

This project is maintained under Git version control.
Git allows me to track changes and maintain a history of my project.