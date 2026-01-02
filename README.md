# Customer Shopping Behavior Analysis

## Project Overview
This project is an end-to-end data analytics case study analyzing customer shopping behavior using transactional retail data. The goal is to uncover insights into spending patterns, customer segments, product performance, and subscription behavior, and to communicate those insights through analysis, visualization, and storytelling.

This project was created as part of my data analytics portfolio to practice a complete workflow from data cleaning to dashboarding and reporting.

---

## Business Questions
The analysis focuses on answering the following questions:

- How does revenue differ by gender?
- Do subscribers spend more than non-subscribers?
- Which products perform best within each category?
- How are customers distributed across new, returning, and loyal segments?
- Does shipping type affect purchase amounts?
- Which age groups generate the most revenue?
- Which products are highly dependent on discounts?

---

## Dataset Summary
- **Rows:** 3,900
- **Columns:** 18
- **Data Types:**
  - Customer demographics (age, gender, location, subscription status)
  - Purchase details (item, category, amount, season, size, color)
  - Behavioral metrics (discount usage, previous purchases, review ratings, shipping type)

**Data Quality Notes:**
- 37 missing values in the review rating column
- Missing values were handled during the data cleaning stage

---

## Tools & Technologies
- **Python (Pandas):** Data cleaning, feature engineering, exploratory analysis
- **SQL (MySQL):** Business analysis and aggregations
- **Tableau:** Interactive dashboard and data visualization
- **GitHub:** Project documentation and version control

---

## Data Preparation (Python)
Key preparation steps included:
- Standardizing column names to snake_case
- Handling missing review ratings using category-level medians
- Creating new features such as:
  - Age groups
  - Purchase frequency
- Identifying and removing redundant columns
- Loading the cleaned dataset into MySQL for SQL analysis

---

## Analysis (SQL)
SQL was used to answer business-focused questions, including:
- Revenue by gender
- Subscriber vs non-subscriber spending behavior
- Customer segmentation (new, returning, loyal)
- Top products by category
- Shipping type impact on average purchase amount
- Discount-dependent products
- Revenue by age group

SQL queries used in the analysis are included in this repository.

---

## Dashboard
An interactive Tableau dashboard was created to visualize key insights and allow exploration of the data across different customer segments and product categories.

**Dashboard features include:**
- Revenue trends
- Customer segmentation
- Product performance
- Discount and shipping behavior

👉 *(Tableau Public link included in the repository)*

---

## Key Insights
- Loyal customers make up the majority of the customer base and drive most purchases
- Subscribers tend to have higher average spending
- Express shipping users show higher average purchase amounts
- Certain products rely heavily on discounted sales
- High product ratings do not always correlate with the highest sales volume

---

## Business Recommendations
- Promote subscriptions to frequent and high-value customers
- Implement loyalty programs to retain returning customers
- Review discount strategies to balance revenue growth and margins
- Highlight top-rated and best-selling products in marketing campaigns
- Focus marketing efforts on high-revenue age groups

---

## Limitations & Next Steps
**Limitations:**
- Dataset represents a limited time range
- Profit and margin data not available

**Next Steps:**
- Add cohort and retention analysis
- Incorporate profitability metrics
- Develop predictive models for customer lifetime value

---

## Files in This Repository
- [Python Notebook – Data Cleaning & EDA](./Cleaning_customer_trends.ipynb)
- [SQL Analysis Queries](./Customer%20trends%20sql%20analysis.sql)
- [Dashboard (PDF Export)](./Customer%20Behaviour%20Dashboard.pdf)
- [Project Report](./Project%20Report.docx)
