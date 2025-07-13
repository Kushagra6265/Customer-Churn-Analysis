# Customer Churn Analysis

## Project Overview

This project focuses on analyzing a customer churn dataset to identify the key factors that contribute to customer churn. By understanding these factors, a business can take proactive steps to retain customers.

## Dataset

The dataset used for this analysis is the **Telco Customer Churn** dataset, which can be found on Kaggle.

* **Kaggle Dataset Link:** [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset contains information about customers, including their demographics, the services they've signed up for, and their churn status.

## Data Preprocessing

The following data preprocessing steps were performed:

* **Handling Missing Values:** The `TotalCharges` column had some missing values represented as spaces. These were replaced with "0" and the column was converted to a float data type.
* **Data Type Conversion:** The `SeniorCitizen` column, which was originally an integer (0 or 1), was converted to a more descriptive "yes" or "no" string.
* **Duplicate Removal:** The dataset was checked for duplicate `customerID`s to ensure data integrity.

## Exploratory Data Analysis (EDA)

Several visualizations were created to understand the data and the relationships between different features and customer churn:

* **Correlation Heatmap:** A heatmap was generated to visualize the correlation between different numerical and encoded categorical features. This helps in identifying features that are strongly correlated with churn.
* **Churn Count:** A bar chart and a pie chart were created to show the count and percentage of customers who churned versus those who did not.
* **Churn by Gender:** A count plot was used to analyze the churn rate between male and female customers.

## Key Findings

* Approximately 26.25% of the customers in the dataset have churned.
* The analysis of churn by gender did not show a significant difference between male and female churn rates.

## How to Run the Project

To run this project, you need to have Python installed with the following libraries:

* pandas
* numpy
* matplotlib
* seaborn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
