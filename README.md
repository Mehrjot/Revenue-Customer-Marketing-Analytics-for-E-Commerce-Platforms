End-to-End Revenue, Customer & Marketing Analytics

#Project Overview

This project delivers an end-to-end analytics solution for an e-commerce business, focusing on revenue performance, customer behavior, retention, and promotion effectiveness.

The objective is to transform raw transactional data into actionable business insights using Python, SQL, and Power BI, and to provide data-driven recommendations that support strategic decision-making.

---

## Business Problem

The business experienced fluctuating revenue growth and wanted to understand:

* Which product categories drive revenue
* How customer retention affects business performance
* Whether discounts and promotions are effective
* How customer purchasing behavior changes over time

---

## Project Objectives

* Analyze overall revenue trends and category-level performance
* Identify high-value and repeat customers
* Evaluate the impact of coupons and promotions
* Perform cohort analysis to understand customer retention
* Provide actionable business recommendations with estimated impact

---

## Tech Stack and Tools

* Python for data cleaning, feature engineering, and analysis
* SQL (SQLite) for business-driven querying
* Power BI for dashboarding and visual storytelling
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for data visualization
* Kaggle as the analysis environment

---

## Dataset Description

The dataset consists of multiple relational tables:

* Customers Data containing customer-level information
* Online Sales containing transaction-level order data
* Marketing Spend containing category-wise monthly marketing investment
* Discount Coupons containing promotional discount details
* Tax Amounts containing category-level tax information

This multi-table structure enables realistic, enterprise-style analytics.

---

## Data Modeling Approach

* Fact Table: Online Sales (transaction-level data)
* Dimension Tables:

  * Customers
  * Marketing Spend
  * Discount Coupons
  * Tax Information

A star-schema style analytical model was followed to support scalable analysis.

---

## Data Cleaning and Feature Engineering

Key engineered features include:

* Gross Revenue derived from quantity, price, and delivery charges
* Customer Tenure in days
* Repeat Customer Flag
* Order Month for time-based analysis
* Coupon Usage Indicator

These features convert raw transactional data into business-ready analytics data.

---

## SQL Analysis

SQL was used to answer real-world business questions, including:

* Monthly revenue trends
* Top-performing product categories
* Revenue contribution by repeat versus one-time customers
* Average Order Value
* Top customers by lifetime revenue
* Impact of coupon usage on revenue and order value
* Customer ranking using window functions

---

## Python Insights and Cohort Analysis

Python-based analysis was used to:

* Visualize revenue trends and seasonality
* Analyze category-level performance
* Compare repeat versus one-time customer behavior
* Perform cohort analysis based on first purchase month to study retention patterns

---

## Power BI Dashboard

An executive-level Power BI dashboard was created with four pages:

1. Business Performance Overview
2. Revenue and Category Performance
3. Customer Value and Retention Insights
4. Discount and Promotion Effectiveness

The dashboard allows stakeholders to quickly identify trends, risks, and growth opportunities.

---

## Key Business Insights

* Revenue is concentrated in a small number of product categories
* Repeat customers contribute significantly higher revenue than one-time customers
* Coupon usage increases order volume but does not consistently increase average order value
* Revenue shows clear seasonal patterns
* A small group of customers contributes a large share of total revenue

---

## Strategic Recommendations

* Focus inventory and marketing efforts on top-performing categories
* Invest in customer retention through loyalty and personalization initiatives
* Optimize discount strategies by targeting price-sensitive segments
* Align marketing campaigns with seasonal demand patterns
* Create exclusive engagement strategies for high-value customers

---

## Expected Business Impact

Implementing these recommendations could potentially:

* Increase overall revenue by 5 to 8 percent
* Improve repeat customer contribution by 8 to 12 percent
* Reduce unnecessary discount spend by 5 to 10 percent

---

## Repository Structure

```
data/
  clean_sales_data.csv
notebooks/
  ecommerce_analytics.ipynb
sql/
  business_queries.sql
dashboards/
  powerbi_dashboard_screenshots/
README.md
```

---

## Key Takeaways

This project demonstrates strong data analytics fundamentals, the ability to work with relational datasets, business-focused SQL querying, executive-level dashboard design, and the translation of data insights into strategic business decisions.

---

## Contact

Feel free to connect with me on LinkedIn or explore more projects on my GitHub profile.
