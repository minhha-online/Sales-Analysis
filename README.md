# 🛒 Sales and Profit Analysis for a Retail Company

## 📚 Project Overview

In this project, I analyzed sales and profitability data from a retail company selling furniture, office supplies, and technology products.  
The goal was to uncover actionable insights that improve profit margins, reduce loss-making transactions, and support data-driven decision-making for sales strategy, discounting, and regional operations.

This end-to-end analysis includes:
- Data cleaning and transformation
- Feature engineering
- Exploratory data analysis (EDA)
- A basic classification model to predict order profitability
- Final strategic business recommendations

---

## 📂 Dataset

- **Source:** Sample Superstore Dataset (CSV)
- **Rows:** 9,994 transactions
- **Key columns:** Sales, Profit, Discount, Category, Region, Segment, Ship Mode, Dates
- **Tools Used:** Python, pandas, matplotlib, scikit-learn

---

## 🧹 Data Cleaning

- Converted order and shipping dates into datetime format
- Removed irrelevant serial column (`Row ID`)
- Verified that no missing values existed

---

## 🛠 Feature Engineering

Created the following new fields:
- **Profit Margin (%):** Profit relative to sales per transaction
- **Shipping Delay (Days):** Difference between order and ship date
- **Discount Bucket:** Categorized discounts into strategic bands
- **Profitability Label (0/1):** Indicates if an order was profitable

These features supported deeper analysis and enabled a simple predictive model.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Sales & Profit Distribution
- Sales are heavily right-skewed — most orders are below \$3,000.
- Profit distribution shows many low-profit orders and a notable number of **loss-making** transactions.

### 🔹 Regional Performance
- **West and East** regions perform well.
- **South** generates sales but contributes to **net loss**, indicating inefficiency or pricing issues.

### 🔹 Discounting Impact
- Strong **negative correlation** between discount rate and profit.
- High-discount orders are often **unprofitable**, even with high sales.

---

## 🤖 Predictive Modeling

### 🔹 Objective
Predict whether a new order will be profitable using basic transaction features.

### 🔹 Model
- **Algorithm:** Logistic Regression (binary classification)
- **Features Used:** Sales, Discount, Shipping Delay, Category, Region, Segment, Discount Bucket
- **Accuracy:** ~94.3% on test data
- **Precision & Recall:** High performance, especially on profitable orders

---

## 🎯 Final Business Recommendations

1. **Reevaluate South Region Strategy:** Audit operations or pricing in this loss-leading area.
2. **Tighten Discounting Policy:** Avoid over-discounting in low-margin segments.
3. **Invest in High-Margin Products:** Focus on categories like Technology & Copiers.
4. **Use Predictive Model:** Deploy classifier in sales tools to prioritize high-profit opportunities.
5. **Optimize for Small Transactions:** Since most orders are small, focus on efficiency and bundling tactics.

---

## 🔮 Future Work

- **Cohort analysis** for customer lifetime value
- **Simulations** of pricing and margin scenarios
- **Product-region profitability matrix**
- **Time-series forecasting** of revenue and margin
- **Real-time alert system** for risky or loss-prone orders

---

## ✅ Outcome

This project demonstrates how data analysis, simple modeling, and strong business interpretation can lead to meaningful strategic decisions — even without advanced machine learning.

Great for early-stage analysts and portfolio demonstration.
