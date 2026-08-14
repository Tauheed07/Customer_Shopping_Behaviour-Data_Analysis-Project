# Customer_Shopping_Behaviour-Data_Analysis-Project
# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** to uncover insights into customer spending patterns, product performance, subscription behavior, and purchasing trends. The analysis was performed using **Python, PostgreSQL, and Power BI** to support data-driven business decisions.

---

## Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Missing Values:** 37 (Review Rating)
* **Data Includes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Category, Item Purchased, Purchase Amount, Season)
  * Shopping behavior (Discounts, Purchase Frequency, Ratings, Shipping Type)

---

## Tools & Technologies

* **Python (Pandas)** – Data Cleaning & Feature Engineering
* **PostgreSQL** – Data Analysis
* **SQL** – Business Queries
* **Power BI** – Dashboard & Visualization

---

## Data Cleaning & Preparation

### Key Steps

* Loaded and explored data using Pandas.
* Handled 37 missing values in `review_rating` using category-wise median imputation.
* Standardized column names to snake_case.
* Created:

  * `age_group` for demographic analysis.
  * `purchase_frequency_days` for customer behavior analysis.
* Removed redundant column `promo_code_used`.
* Loaded the cleaned dataset into PostgreSQL for analysis.

---

## Business Analysis (SQL)

### Key Questions Answered

1. Revenue and average order value by gender.
2. Identification of high-spending customers who frequently use discounts.
3. Top-rated products vs top-selling products.
4. Purchase behavior across shipping methods.
5. Spending comparison between subscribers and non-subscribers.
6. Products most dependent on discounts.
7. Customer segmentation (New, Returning, Loyal).
8. Top 3 selling products in each category.
9. Subscription trends among repeat buyers.
10. Revenue contribution by age group.

---

## Key Insights

* Male customers generated more purchases, while average order value remained similar across genders.
* Some customers spend significantly more when discounts are offered.
* Top-rated products are not always the best-selling products.
* Express shipping orders have slightly higher average purchase values.
* Subscribers contribute revenue proportional to their customer share (~27%), indicating room for subscription growth.
* Loyal customers are less likely to subscribe than expected.
* Young Adults contribute the highest revenue among all age groups.

---

## Power BI Dashboard

The dashboard includes:

### KPI Cards

* Total Revenue
* Total Customers
* Average Purchase Amount
* Average Review Rating

### Visualizations

* Revenue by Category
* Product Performance
* Customer Segmentation
* Subscription Analysis
* Age Group Revenue Contribution

### Interactive Features

* Category Filters
* Age Group Filters
* Subscription Filters
* Shipping Type Filters

---

## Business Recommendations

* Increase subscription adoption through exclusive member benefits.
* Strengthen loyalty programs to retain repeat customers.
* Optimize discount strategies for discount-dependent products.
* Promote both top-rated and top-selling products.
* Target high-value age groups with personalized marketing campaigns.
* Encourage express shipping to increase average order value.

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
├── Python/
├── SQL/
├── PowerBI/
├── Images/
└── README.md
```

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, covering data cleaning, feature engineering, SQL-based business analysis, and Power BI dashboard development. The insights generated can help businesses improve customer retention, optimize product strategies, and drive data-informed decision-making.
