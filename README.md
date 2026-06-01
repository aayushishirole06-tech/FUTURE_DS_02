# FUTURE_DS_02 – Customer Churn Analysis & Retention Dashboard

## Overview

This project focuses on analyzing customer churn behavior and retention trends using customer subscription data.

The objective of this project is to identify why customers leave, understand churn patterns, analyze retention behavior, and provide actionable business recommendations through data analysis and visualization.

This project was completed as part of the **Future Interns Data Science & Analytics Internship – Task 2 (2026)**.

---

## Project Objective

The primary goal of this project is to analyze customer churn and answer important business questions such as:

- Why are customers leaving the service?
- Which customer groups are most likely to churn?
- What factors influence customer retention?
- How do contract type, payment methods, and monthly charges impact churn?
- What actions can improve customer retention?

---

## Tools & Technologies Used

- **Python (Google Colab)** – Data cleaning and exploratory data analysis  
- **Pandas** – Data manipulation and preprocessing  
- **Matplotlib** – Data visualization  
- **Power BI** – Interactive dashboard development  
- **CSV Dataset** – Customer churn data source  

---

## Dataset Used

### Telco Customer Churn Dataset

The dataset contains customer subscription and behavioral information such as:

- Customer ID
- Gender
- Senior Citizen Status
- Partner & Dependents
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

### Dataset Summary

| Metric | Value |
|--------|------|
| Total Records | 7,043 |
| Total Features | 21 |
| Missing Values | None |
| Churn Rate | 26.54% |

---

## Data Cleaning & Preprocessing

Before analysis, the dataset was cleaned and prepared using Python.

The following preprocessing steps were performed:

- Imported dataset into Google Colab
- Checked dataset shape and dimensions
- Verified missing values
- Inspected data types
- Converted `TotalCharges` column into numeric format
- Performed churn distribution analysis
- Prepared cleaned dataset for Power BI dashboard creation

The cleaned dataset was exported and used in Power BI.

---

## Exploratory Data Analysis (Python)

Python was used to perform churn analysis and identify customer behavior patterns.

The following analyses were conducted:

### Churn Distribution
Analyzed the percentage of customers who stayed vs churned.

### Churn by Contract Type
Identified how contract duration impacts churn.

### Churn by Internet Service
Compared churn behavior across internet service categories.

### Churn by Payment Method
Analyzed payment methods associated with high churn.

### Monthly Charges vs Churn
Examined relationship between pricing and customer churn.

### Senior Citizen Churn Analysis
Studied churn behavior across age demographics.

### Customer Tenure Analysis
Analyzed how long customers remain before leaving.

---

## Power BI Dashboard Features

The dashboard includes the following components:

### KPI Cards
- Total Customers
- Churned Customers
- Churn Rate
- Average Customer Tenure

### Visual Analysis
- Churn by Contract Type
- Churn by Internet Service
- Churn by Payment Method
- Monthly Charges vs Churn
- Churn by Senior Citizen
- Customer Tenure Analysis

### Interactive Features
The dashboard contains slicers for:

- Contract Type
- Internet Service
- Payment Method

These slicers allow interactive exploration of customer churn behavior.

---

## Key Insights

### 1. Month-to-Month Contracts Have Highest Churn
Customers with month-to-month contracts showed the highest churn rates.

### 2. Fiber Optic Users Churn More
Fiber optic customers experienced significantly higher churn compared to DSL users.

### 3. Electronic Check Customers Are High-Risk
Customers using electronic check payment methods were more likely to churn.

### 4. Early Subscription Period Is Critical
Most customer churn occurred during the first few months of subscription.

### 5. Higher Monthly Charges Increase Churn
Customers with higher monthly charges demonstrated greater churn probability.

### 6. Senior Citizens Show Higher Churn Risk
Senior citizen customers showed relatively higher churn behavior.

---

## Business Recommendations

Based on the analysis, the following recommendations are suggested:

- Promote long-term contracts through discounts and loyalty programs
- Improve customer experience for fiber optic users
- Encourage auto-payment methods through incentives
- Strengthen onboarding for new customers
- Optimize pricing for high monthly charge customers
- Create retention campaigns for high-risk segments

---

## Dashboard Preview

Add your dashboard screenshot here.

Example:

```md
![Dashboard Screenshot](Customer_Churn_Analytics.png)
```

---

## Project Files Included

```text
FUTURE_DS_02/
│── Customer_Churn_Analysis.ipynb
│── cleaned_churn_data.csv
│── Customer_Churn_Analytics_Dashboard.pbix
│── Customer_Churn_Analytics_Dashboard.pdf
│── Customer_Churn_Analytics.png
│── Customer_Churn_Analysis_Report.docx
│── README.md
```

---

## Conclusion

This project demonstrates how customer churn analysis can help businesses understand customer behavior, reduce churn, and improve long-term retention.

By combining Python for exploratory data analysis and Power BI for business visualization, this project provides meaningful business insights and supports data-driven decision-making.

---

## Author

**Aayushi Shirole**  
BTech Computer Science Student  
Aspiring Data Science & Analytics Professional