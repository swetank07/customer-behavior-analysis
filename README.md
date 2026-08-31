# 📊 Customer Behavior Analysis

## 📝 Project Overview

**Customer Behavior Analysis** is an end-to-end data analytics project focused on understanding customer purchasing behavior, spending patterns, product performance, discount usage, subscription behavior, customer segmentation, shipping preferences, and revenue contribution.

The project works with customer shopping transaction data and combines **Python, SQL, and Power BI** to transform raw data into meaningful business insights and an interactive analytical dashboard.

The objective is to answer practical business questions and provide a clear view of how different customer groups, products, categories, and purchasing behaviors contribute to overall business performance.


---

# 📊 Dashboard Preview

![Customer Behavior Dashboard](customer_behavior_dashboard.png)


---

## 🎯 Problem Statement

Businesses collect large volumes of customer transaction data, but raw transactional data alone does not provide clear answers to important business questions.

This project aims to analyze customer shopping behavior and answer key questions such as:

* How does revenue differ between male and female customers?
* Which discounted purchases are still above the average purchase amount?
* Which products receive the highest customer ratings?
* How does average spending differ between Standard and Express shipping?
* Do subscribed customers spend more than non-subscribers?
* Which products have the highest percentage of discounted purchases?
* How can customers be segmented based on their previous purchase behavior?
* Which products are most frequently purchased within each category?
* Are repeat buyers more likely to subscribe?
* Which age groups contribute the most revenue?

---

## 🎯 Project Objectives

The major objectives of this project are to:

* Analyze customer purchasing patterns
* Measure overall customer and purchase KPIs
* Compare customer behavior across different groups
* Understand subscription behavior
* Analyze discount usage
* Identify highly rated products
* Identify frequently purchased products
* Segment customers based on purchasing history
* Compare shipping-related spending
* Analyze revenue contribution by age group and category
* Build an interactive Power BI dashboard for business reporting

---

# 📌 Key Performance Indicators

The Power BI dashboard provides the following headline KPIs:

| KPI                         |      Value |
| --------------------------- | ---------: |
| 👥 Number of Customers      |   **3.9K** |
| 💰 Average Purchase Amount  | **$59.76** |
| ⭐ Average Review Rating     |   **3.75** |
| 🔔 Subscribed Customers     |    **27%** |
| 🚫 Non-Subscribed Customers |    **73%** |

These KPIs provide a high-level overview of the customer base, average spending, customer satisfaction through ratings, and subscription adoption.

---

# 🔍 Key Insights

## 1. Subscription Behavior

The dashboard shows that:

* **27%** of customers are subscribed
* **73%** of customers are not subscribed

This provides an overall view of subscription adoption and highlights the difference between subscribed and non-subscribed customers.

The SQL analysis further compares subscribers and non-subscribers using:

* Number of customers
* Average purchase amount
* Total revenue

---

## 2. Customer Spending

The overall average purchase amount is **$59.76**.

The SQL analysis uses this average as a benchmark to identify customers who:

* Used a discount
* Still made a purchase at or above the overall average purchase amount

This helps identify customers who maintain relatively high spending even when discounts are applied.

---

## 3. Product Rating Analysis

Customer review ratings are analyzed to identify the **top 5 products with the highest average review rating**.

This provides a product-level view of customer satisfaction and helps identify highly rated products.

---

## 4. Shipping Analysis

The project compares average purchase amounts between:

* Standard Shipping
* Express Shipping

The analysis helps understand whether purchasing behavior differs based on shipping type.

The Power BI dashboard also provides a broader view of shipping types, including:

* 2-Day Shipping
* Express
* Free Shipping
* Next Day Air
* Standard
* Store Pickup

---

## 5. Discount Analysis

Discount behavior is analyzed at the product level.

The SQL analysis calculates the percentage of purchases where a discount was applied and identifies the **top 5 products with the highest discount purchase rate**.

This provides a way to understand which products are most frequently associated with discounted purchases.

---

## 6. Customer Segmentation

Customers are segmented based on their number of previous purchases:

| Segment       | Previous Purchases |
| ------------- | -----------------: |
| **New**       |                  1 |
| **Returning** |               2–10 |
| **Loyal**     |       More than 10 |

This segmentation provides a simple framework for understanding customers according to their purchasing history.

---

## 7. Product Performance by Category

The project identifies the **top 3 most purchased products within each category**.

This analysis uses SQL ranking techniques to compare products within their respective categories.

The Power BI dashboard analyzes the following categories:

* Clothing
* Accessories
* Footwear
* Outerwear

---

## 8. Repeat Buyers & Subscription

The project investigates the relationship between repeat purchasing and subscription behavior.

Customers with **more than 5 previous purchases** are classified as repeat buyers for this analysis, and their subscription status is compared.

This helps investigate whether customers with stronger purchasing history are also more likely to subscribe.

---

## 9. Age Group Analysis

Revenue contribution is analyzed across different age groups.

The dashboard includes:

* Young Adult
* Middle-aged
* Adult
* Senior

Both **Revenue by Age Group** and **Sales by Age Group** are visualized in the Power BI dashboard.

---

## 10. Gender Analysis

The SQL analysis compares total revenue generated by:

* Male customers
* Female customers

The Power BI dashboard also provides gender-based filtering and analysis.

---

# 🧠 Business Questions Answered

The SQL component addresses **10 business questions**:

| #  | Business Question                                                                      |
| -- | -------------------------------------------------------------------------------------- |
| 01 | What is the total revenue generated by male vs. female customers?                      |
| 02 | Which customers used a discount but still spent more than the average purchase amount? |
| 03 | Which are the top 5 products with the highest average review rating?                   |
| 04 | How do average purchase amounts compare between Standard and Express Shipping?         |
| 05 | Do subscribed customers spend more?                                                    |
| 06 | Which 5 products have the highest percentage of purchases with discounts applied?      |
| 07 | How can customers be segmented into New, Returning, and Loyal customers?               |
| 08 | What are the top 3 most purchased products within each category?                       |
| 09 | Are repeat buyers also likely to subscribe?                                            |
| 10 | What is the revenue contribution of each age group?                                    |

---

# 🛠️ Tools & Technologies

## Python

* Python
* Pandas
* Jupyter Notebook

## SQL

* SQL
* PostgreSQL

## Data Visualization

* Microsoft Power BI

## Data Format

* CSV

---

# 🐍 Python Analysis

The Python notebook contains the analysis workflow performed on the customer shopping behavior dataset.

### File

```text
Customer_Behavior_Analysis.ipynb
```

Python is used as part of the analytical workflow to work with the customer dataset and support the overall analysis.

---

# 🗄️ SQL Analysis

The SQL component converts business requirements into analytical queries.

### File

```text
Customer_Behavior_Analysis.sql
```

The project demonstrates practical SQL concepts including:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `SUM()`
* `AVG()`
* `COUNT()`
* `CASE`
* Subqueries
* Common Table Expressions (CTEs)
* `ROW_NUMBER()`
* Conditional aggregation
* Percentage calculations
* Customer segmentation
* Ranking
* Comparative analysis

### SQL Techniques Used

**Aggregate Functions**

Used for calculating:

* Total revenue
* Average purchase amount
* Average review rating
* Customer counts

**CASE Statements**

Used for customer segmentation into:

* New
* Returning
* Loyal

**CTEs**

Used for organizing multi-step analytical queries.

**Window Functions**

`ROW_NUMBER()` is used to rank products within categories.

**Subqueries**

Used to compare customer purchase amounts against the overall average.

---

# 📊 Power BI Dashboard

The Power BI dashboard converts the analytical results into an interactive business reporting interface.

### Dashboard File

```text
Customer_Behavior_Dashboard.pbix
```

### Dashboard PDF

```text
Customer_Behavior_Dashboard.pdf
```

The dashboard includes:

### KPI Section

* Number of Customers
* Average Purchase Amount
* Average Review Rating

### Customer Analysis

* Subscription Status
* Gender
* Category
* Shipping Types

### Sales & Revenue Analysis

* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group

The dashboard provides filters for different customer and transaction dimensions to support interactive analysis.

---

# 📈 Dashboard Analysis Areas

## Revenue by Category

Revenue is analyzed across:

* Clothing
* Accessories
* Footwear
* Outerwear

## Sales by Category

Sales performance is visualized across the same product categories.

## Subscription Status

Customer subscription distribution is presented as:

* Yes — 27%
* No — 73%

## Gender

The dashboard provides a comparison between:

* Female
* Male

## Shipping Types

The dashboard includes:

* 2-Day Shipping
* Express
* Free Shipping
* Next Day Air
* Standard
* Store Pickup

## Age Groups

The dashboard provides sales and revenue analysis for:

* Young Adult
* Middle-aged
* Adult
* Senior

---

# 🔄 End-to-End Analytics Workflow

```text
                 Customer Shopping Data
                          │
                          ▼
                    Data Preparation
                          │
                          ▼
                 Python / Jupyter Notebook
                          │
                          ▼
                   Business Questions
                          │
                          ▼
                     SQL Analysis
                          │
                          ▼
                KPI & Metric Development
                          │
                          ▼
                  Power BI Dashboard
                          │
                          ▼
                  Business Insights
```

---

# 💼 Business Value

This project demonstrates how customer transaction data can be transformed into business-oriented analysis.

The analysis can support decision-making in areas such as:

* Customer segmentation
* Customer retention
* Subscription strategy
* Product performance
* Discount strategy
* Revenue analysis
* Customer purchasing behavior
* Category performance
* Shipping behavior
* Customer engagement analysis

---

# 📂 Repository Structure

```text
customer-behavior-analysis/
│
├── Customer_Behavior_Analysis.ipynb
│   └── Python / Jupyter Notebook analysis
│
├── Customer_Behavior_Analysis.sql
│   └── SQL business analysis queries
│
├── Customer_Behavior_Dashboard.pbix
│   └── Editable Power BI dashboard
│
├── Customer_Behavior_Dashboard.pdf
│   └── PDF export of the Power BI dashboard
│
├── customer behavior SQL Queries.pdf
│   └── Documented SQL queries
│
├── customer_shopping_behavior.csv
│   └── Customer shopping behavior dataset
│
└── README.md
    └── Project documentation
```

---

# 📁 Project Files

| File                                | Description                                   |
| ----------------------------------- | --------------------------------------------- |
| `Customer_Behavior_Analysis.ipynb`  | Python/Jupyter Notebook used for analysis     |
| `Customer_Behavior_Analysis.sql`    | SQL queries used to answer business questions |
| `Customer_Behavior_Dashboard.pbix`  | Editable Power BI dashboard                   |
| `Customer_Behavior_Dashboard.pdf`   | PDF version of the Power BI dashboard         |
| `customer behavior SQL Queries.pdf` | Documented SQL analysis                       |
| `customer_shopping_behavior.csv`    | Customer shopping behavior dataset            |
| `README.md`                         | Project documentation                         |

---

# 📊 Project Deliverables

### 1. Data Analysis

Customer shopping behavior data is analyzed using Python.

### 2. SQL Business Analysis

Ten business questions are answered using SQL queries and analytical techniques.

### 3. Customer Segmentation

Customers are categorized into New, Returning, and Loyal segments based on previous purchases.

### 4. KPI Development

Key customer and purchase metrics are presented through Power BI.

### 5. Interactive Dashboard

A Power BI dashboard brings together customer, sales, revenue, subscription, shipping, gender, category, and age-group analysis.

---

# 🚀 Future Enhancements

The project can be further extended with:

* Customer Lifetime Value (CLV)
* RFM Analysis
* Customer Churn Analysis
* Customer Retention Rate
* Cohort Analysis
* Subscription Conversion Analysis
* Sales Trend Analysis
* Revenue Forecasting
* Discount Impact Analysis
* Product Recommendation Analysis

---

# 📌 Conclusion

This project demonstrates an end-to-end approach to customer behavior analytics by combining **Python, SQL, and Power BI**.

Starting from customer shopping transaction data, the project moves through data analysis and business-question-driven SQL querying before presenting the results through an interactive Power BI dashboard.

The final solution provides a structured view of **customer spending, product performance, discounts, subscriptions, customer segments, shipping behavior, category performance, gender, and age-group revenue contribution**.

---

## ⭐ Project Highlights

* End-to-end data analytics workflow
* 10 practical business questions
* Python-based analysis
* PostgreSQL/SQL analysis
* Customer segmentation
* Advanced SQL concepts
* KPI-driven Power BI dashboard
* Interactive business reporting
* Product, customer, category, subscription, shipping and age-group analysis


