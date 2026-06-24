# SaaS / E-Commerce Cohort Retention & Customer Lifetime Value (CLTV) Analysis

## Project Overview

This project performs **Cohort Retention Analysis** and **Customer Lifetime Value (CLTV) Analysis** on transactional data from an e-commerce business. The goal is to understand customer retention patterns, identify churn, and estimate the long-term value of customers.

Instead of focusing only on customer acquisition, this project analyzes how many customers return after their first purchase and how much revenue they generate over time.

---

## Business Problem

Acquiring a new customer is significantly more expensive than retaining an existing one. Businesses need to understand:

- When customers stop purchasing (customer churn)
- Which customer cohorts have the highest retention
- Which customer segments generate the highest revenue
- The expected lifetime value of customers

These insights help companies improve retention strategies, optimize marketing budgets, and increase profitability.

---

## Objectives

- Clean and preprocess transactional data
- Build customer cohorts based on first purchase month
- Calculate monthly customer retention
- Generate a cohort retention matrix
- Visualize retention using heatmaps and retention curves
- Calculate Customer Lifetime Value (CLTV)
- Provide business recommendations based on customer behavior

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```
SaaS-Cohort-CLTV-Analysis/
│
├── data/
│
├── notebooks/
│   └── Cohort_Analysis.ipynb
│
├── outputs/
│   ├── cohort_matrix.csv
│   ├── retention_matrix.csv
│   ├── retention_heatmap.png
│   └── retention_curve.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Workflow

### Week 1 – Data Cleaning & Wrangling

- Loaded transactional dataset
- Removed duplicate records
- Handled missing Customer IDs
- Removed cancelled/refunded transactions
- Removed invalid quantities and prices
- Created Revenue column
- Calculated each customer's first purchase date
- Generated Cohort Month and Transaction Month

---

### Week 2 – Cohort Retention Analysis

- Calculated Cohort Index
- Built customer cohort matrix
- Calculated monthly retention percentages
- Generated retention heatmap
- Plotted customer retention curve
- Derived initial business insights

---

### Week 3 – Customer Lifetime Value (CLTV)

- Calculate Average Order Value (AOV)
- Calculate Purchase Frequency
- Estimate Customer Lifetime
- Compute Customer Lifetime Value
- Segment customers based on CLTV

---

### Week 4 – Business Insights & Visualization

- Customer segmentation
- CLTV comparison charts
- Strategic recommendations
- Final dashboard and documentation

---

## Sample Outputs

- Cohort Retention Matrix
- Customer Retention Heatmap
- Retention Decay Curve
- CLTV Analysis
- Customer Segmentation

---

## Business Insights

This project helps answer questions such as:

- Which customer cohorts have the highest retention?
- When do customers churn?
- Which customer segments generate the highest revenue?
- What is the estimated lifetime value of customers?
- How can retention be improved?

---

## Future Improvements

- Interactive Power BI Dashboard
- Predictive CLTV using Machine Learning
- Churn Prediction Model
- Customer Segmentation using RFM Analysis

---

## Author

**Vedant Shinde**

B.Tech Information Technology

IIIT Allahabad