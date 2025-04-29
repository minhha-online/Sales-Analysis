# 🛒 Sales and Profit Analysis for a Retail Company

## 📚 Project Overview
This project analyzes the sales and profitability data of a retail company selling furniture, office supplies, and technology products.  
The goal is to uncover actionable insights that can help increase profitability, reduce loss-making transactions, and optimize operational strategies.

## 📂 Dataset
- Source: Sample - Superstore.csv
- Size: 9,994 rows × 20 columns after cleaning
- Key fields: Sales, Profit, Category, Region, Segment, Discount, Order and Ship dates

## 📋 Project Steps
1. **Data Loading and Cleaning**
   - Fixed encoding issues
   - Converted dates
   - Dropped irrelevant columns
2. **Feature Engineering**
   - Created Profit Margin (%), Shipping Delay, Discount Bucket, and Profitability Label
3. **Exploratory Data Analysis**
   - Sales are volume-driven; most orders < $3000
   - High variability in profits; discounting erodes margins
   - South region consistently loses money
4. **Modeling**
   - Logistic Regression model predicts profitable orders
   - Achieved 94.3% accuracy

## 📈 Key Findings
- South region drains profitability → needs strategic attention.
- Over-discounting is severely hurting profits.
- Technology and Copier subcategories bring highest margins.
- Focused customer targeting and smarter pricing are necessary.

## 🎯 Business Recommendations
- Tighten discount policies.
- Reassess South region sales strategy.
- Expand investment in profitable product lines (Copiers, Technology).
- Use predictive models to prioritize profitable orders in CRM/sales funnel.

## 🔮 Future Work
- Cohort analysis for customer retention
- Profit margin optimization simulations
- Predictive maintenance of profitable vs unprofitable product categories
