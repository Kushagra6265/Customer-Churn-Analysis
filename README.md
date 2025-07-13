# 📉 Customer Churn Analysis with Python

This project presents a detailed analysis of customer churn using the **Telco Customer Churn dataset** from Kaggle. The goal is to uncover patterns and identify the most influential factors that lead to customer churn, enabling businesses to develop proactive retention strategies.

By leveraging **Pandas**, **NumPy**, and **Seaborn/Matplotlib**, the project performs data preprocessing, exploration, and visualization to highlight critical insights such as churn percentages, service-based churn risks, and demographic influences.

Whether you're aiming to reduce customer loss, understand churn demographics, or analyze service impact, this project offers a strong foundation for customer behavior analysis using Python.

---

## 📔 Interactive Notebook Preview

To explore the full analysis and visualizations, open the 👉 `customer_churn_analysis.ipynb` notebook.

---

## 🔍 Key Insights Uncovered

### 🧍‍♂️ Customer Demographics & Churn Behavior
- Around **26.25%** of customers have churned.
- **Gender** does not significantly impact churn rates.
- Churn is more related to **contract types, payment methods, and service usage** than demographics alone.

### 📊 Service & Subscription Patterns
- Customers with **month-to-month contracts** are more likely to churn.
- Those without **online security or tech support** show higher churn rates.
- **Fiber optic** internet service users have higher churn compared to DSL.

---

## 🧹 Data Preprocessing & Cleaning

- Converted `TotalCharges` to `float` after handling missing (space-filled) values.
- Transformed the `SeniorCitizen` field to a descriptive categorical variable (`Yes`/`No`).
- Verified **unique `customerID`s** to ensure no duplicate records.

---

## 📈 Visualizations Included

- 🔥 **Correlation heatmap** showing relationships between numerical and encoded categorical features.
- 📊 **Bar & pie charts** visualizing overall churn distribution.
- 📉 **Count plots** for churn analysis by gender and other features.

---

## 🌐 Dataset Source

**Telco Customer Churn Dataset on Kaggle**  
📎 [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 💻 How to Run This Project

Ensure Python is installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn

