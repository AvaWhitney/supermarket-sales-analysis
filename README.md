# Supermarket Sales Analysis (EDA)

A data-driven exploration of customer behavior, branch performance, and sales trends across three supermarket locations.

## Overview
This project analyzes three months of transactional data from a supermarket chain with branches in three cities. The dataset captures customer demographics, product categories, purchase amounts, payment methods, and customer satisfaction ratings.

The goal of this exploratory data analysis (EDA) was to uncover actionable insights related to customer preferences, branch performance, shopping trends, and operational optimization.

## Objectives
1. **Branch Comparison**<br>
Evaluate total sales, customer satisfaction, and category-level performance across branches.
2. **Customer Behavior**<br>
Explore differences in behavior based on gender, membership type, and payment preferences.
3. **Sales Trends**<br>
Identify peak shopping days and hours, and analyze how product lines perform throughout the day.
4. **Operational Recommendations**<br>
Use data-driven insights to inform stocking schedules, staffing, and promotions.

## Tools & Libraries Used
* **Python**
* **Pandas, NumPy** – Data wrangling and manipulation
* **Matplotlib, Seaborn** – Data visualization
* **Statsmodels, Scipy** – Statistical analysis (ANOVA, hypothesis testing)
* **Jupyter Notebook** – Interactive development environment

## Key Findings
* Saturday is the busiest shopping day, followed by Tuesday. Mondays are typically the slowest.
* Branch C had the highest average customer rating (7.07), while Branch B rated lowest (6.82).
* No statistically significant difference in transaction amount between e-wallet, cash, and credit card users (p = 0.92).
* Customers across all branches typically purchase 3–7 items per transaction, regardless of product category.
* Product preferences and peak shopping hours vary by branch, offering opportunities for branch-specific strategy.

## Recommendations
* Align shelf restocking schedules with branch-specific product demand and time-of-day trends.
* Target female members in Branch C with promotions in fashion and beauty categories.
* Encourage e-wallet use for smoother checkout and reduced handling costs.
* Optimize staffing schedules based on hourly foot traffic by branch.
* Launch promotions on Saturdays and Tuesdays, leveraging peak traffic windows.<br>
[See full recommendations →](#-recommendations)


## Repository Structure
📂 supermarket-sales-analysis/<br>
│-- 📄 README.md<br>
│-- 📄 supermarket_sales_eda.ipynb<br>
│-- 📂 data<br>
│ │-- 📄 supermarket_sales.csv<br>
│ │-- 📄 supermarket_sales_clean.csv<br>
│ │-- 📄 pct_of_sales_by_time_and_branch.csv<br>


## Dataset Source
This dataset is publicly available on [Kaggle](https://www.kaggle.com/) and includes synthetic transaction data for educational use.
