# 📊 Financial Health & Behavioral Diagnostic
### *Day 1: 30-Project Data Science Challenge*

## 📌 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a dataset of 3,000 users to identify the drivers of financial success. Rather than looking at income alone, this analysis explores the intersection of **psychological stress**, **financial advice**, and **spending habits**.

## 🗂️ Dataset Schema
The dataset consists of 3,000 records with 25 specialized features:
* **Time & ID:** `date`, `user_id`
* **Income & Expenses:** `monthly_income`, `monthly_expense_total`, `discretionary_spending`, `essential_spending`, `rent_or_mortgage`
* **Financial Health:** `savings_rate`, `actual_savings`, `credit_score`, `debt_to_income_ratio`, `emergency_fund`
* **Behavioral Metrics:** `financial_advice_score`, `financial_stress_level`, `cash_flow_status`
* **Target Variables:** `savings_goal_met` (Binary), `fraud_flag`

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Seaborn`, `Matplotlib`



## 🔍 Key Analysis & Insights
### 1. Feature Correlation Matrix
I utilized a heatmap to identify which variables most strongly impact a user's `actual_savings`. 
* **Finding:** A high `financial_advice_score` showed a stronger positive correlation with meeting goals than absolute `monthly_income`.

### 2. Behavioral Stress Analysis
Using a count plot, I compared `financial_stress_level` against `savings_goal_met`.
* **Insight:** Users with "Medium" stress levels were surprisingly more consistent in meeting goals than "Low" stress users, suggesting that some financial pressure acts as a motivator for discipline.

### 3. Spending Ratio Optimization
I analyzed the ratio between `essential_spending` and `discretionary_spending`. 
* **Insight:** Users failing their goals typically had a discretionary spending ratio exceeding 35% of their total monthly income.


## 📈 Next Steps
* **Day 2:** Migrate this dataset into a SQLite database to practice complex SQL window functions.
* **Day 12:** Build a Churn Prediction model to identify users at risk of falling into "Negative" cash flow status.

---
**Author:** Harshil vaghasiya
**Challenge:** 30-Project Data Science Sprint  
**Date:** January 2026
