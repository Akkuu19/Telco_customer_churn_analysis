# Customer Churn Analysis

This repository contains a comprehensive analysis of customer churn using Python. The analysis aims to explore patterns in customer behavior and identify factors that contribute to churn.

## Project Overview

The project focuses on a telecommunications company's dataset, which includes information about customer demographics, services used, and churn status. We perform data cleaning, exploratory data analysis (EDA), and basic insights generation to understand customer retention.

## Key Features of the Analysis

- Data Cleaning:

   - Handled missing and erroneous values in the dataset.
   - Converted TotalCharges column to numeric format.
   - Addressed any duplicated entries.

  
- Exploratory Data Analysis (EDA):

   - Analyzed distributions of key variables like tenure, MonthlyCharges, and Contract.
   - Examined the relationships between features and churn.
   - Visualized churn patterns across different customer demographics and service usage.

  
- Feature Engineering:
  - Converted binary categorical columns (e.g., SeniorCitizen) for better interpretability.
 
## Tools and Libraries

   - Python 3.12.4
   - Pandas
   - Matplotlib/Seaborn for visualizations
   - NumPy

## Files

   - churn_analysis.ipynb: The Jupyter Notebook containing the complete analysis.
   - telco-Customer-Churn.csv: The dataset used for the analysis.


## Results and Insights

The analysis uncovers several important insights, including:

  - Customers with month-to-month contracts and higher monthly charges are more likely to churn.
  - Customers using fiber optic internet services show a higher churn rate compared to DSL users.
  - Additional services like TechSupport and OnlineSecurity play a significant role in reducing churn.

## Getting Started
Clone the repository:
       git clone https://github.com/yourusername/churn-analysis.git
       cd churn-analysis

Install required dependencies:
       pip install -r requirements.txt

Open the Jupyter notebook to explore the analysis:
      jupyter notebook churn_analysis.ipynb

## Data

The dataset used in this project is sourced from a telecommunications company and includes the following key columns:

- CustomerID: Unique identifier for each customer.
- Gender, SeniorCitizen, Partner, Dependents: Customer demographics.
- Tenure: Duration of customer association.
- Churn: Whether the customer has churned or not.
