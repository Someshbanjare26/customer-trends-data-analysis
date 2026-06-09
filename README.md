# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

An end-to-end Data Analytics project focused on understanding customer shopping behavior using transactional purchase data.

The project follows the complete analytics lifecycle:

**Python ➜ Data Cleaning ➜ PostgreSQL ➜ SQL Business Analysis ➜ Power BI Dashboard**

Using 3,900 customer purchase records, the project uncovers spending patterns, customer segments, product preferences, subscription trends, and revenue drivers that can help businesses make data-driven decisions.

---

## 📊 Dashboard Preview

![Customer Behavior Dashboard](https://github.com/Someshbanjare26/customer-trends-data-analysis/blob/main/img/Dashboard.png)

*Interactive Power BI dashboard showcasing customer demographics, subscription analysis, revenue trends, category performance, shipping preferences, and age-group insights.*

## 🎯 Business Objective

Retail businesses generate massive amounts of customer data every day, but raw data alone does not provide actionable insights.

This project aims to answer critical business questions such as:

* Which customer groups generate the highest revenue?
* Do subscriptions increase customer spending?
* Which products perform best?
* How effective are discounts?
* Which customer segments should be targeted for retention?

---

## 📊 Dataset Information

| Feature       | Value                             |
| ------------- | --------------------------------- |
| Total Records | 3,900                             |
| Total Columns | 18                                |
| Data Type     | Customer Shopping Transactions    |
| Tools Used    | Python, PostgreSQL, SQL, Power BI |
| Domain        | Retail Analytics                  |

### Key Attributes

* Customer Demographics

  * Age
  * Gender
  * Location
  * Subscription Status

* Purchase Information

  * Item Purchased
  * Category
  * Purchase Amount
  * Season

* Customer Behavior

  * Discounts Applied
  * Previous Purchases
  * Review Ratings
  * Purchase Frequency
  * Shipping Type

---

# 🧹 Data Cleaning & Preprocessing (Python)

Before analysis, the dataset was cleaned and transformed using Python.

### Steps Performed

✅ Data Loading using Pandas

✅ Exploratory Analysis using:

* `.info()`
* `.describe()`

✅ Missing Value Treatment

* Found missing values in Review Rating column
* Imputed missing ratings using category-wise median values

✅ Column Standardization

* Converted column names to snake_case format

✅ Feature Engineering

* Created `age_group`
* Created `purchase_frequency_days`

✅ Data Validation

* Checked redundancy between discount and promo code fields

✅ Database Integration

* Loaded cleaned data into PostgreSQL for SQL analysis

---

# 🗄️ SQL Business Analysis

After loading data into PostgreSQL, several business-focused analyses were performed.

### Revenue Analysis

* Revenue by Gender
* Revenue by Age Group
* Subscriber vs Non-Subscriber Revenue

### Customer Behavior Analysis

* High Spending Discount Users
* Repeat Buyers vs Subscription Status
* Customer Segmentation

### Product Analysis

* Top Rated Products
* Top Purchased Products by Category
* Discount Dependent Products

### Shipping Analysis

* Standard vs Express Shipping Spending Comparison

---

# 👥 Customer Segmentation

Customers were segmented based on purchase history:

| Segment            | Definition                |
| ------------------ | ------------------------- |
| New Customer       | First-time buyers         |
| Returning Customer | Moderate purchase history |
| Loyal Customer     | Frequent repeat buyers    |

This segmentation helps businesses create targeted retention and loyalty campaigns.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize insights and make business decisions easier.

### Dashboard Highlights

📌 Revenue Distribution

📌 Customer Segmentation

📌 Subscription Analysis

📌 Product Performance

📌 Age Group Analysis

📌 Shipping Preference Insights

📌 Discount Impact Analysis

---

# 💡 Key Business Insights

### Subscription Drives Revenue

Subscribers contribute significantly to overall business revenue.

### Loyal Customers Matter

Repeat buyers show higher lifetime value and should be retained through loyalty programs.

### Product Positioning Opportunities

Top-rated products can be promoted more aggressively in marketing campaigns.

### Discount Optimization Needed

Certain products heavily rely on discounts, indicating potential margin risks.

### Age-Based Targeting

Some age groups contribute disproportionately to revenue and can be targeted with personalized campaigns.

---

# 🚀 Business Recommendations

### 1. Increase Subscription Adoption

Offer exclusive member benefits and personalized rewards.

### 2. Strengthen Loyalty Programs

Reward repeat customers to increase retention.

### 3. Optimize Discount Strategies

Balance sales growth with profit margins.

### 4. Promote Top Performing Products

Leverage highly-rated products in campaigns.

### 5. Improve Marketing Segmentation

Target high-revenue customer groups with customized offers.

---

# 🛠️ Tech Stack

### Programming

* Python

### Data Processing

* Pandas
* NumPy
  
### Database

* MySQL

### Query Language

* SQL

### Data Visualization

* Power BI

### Version Control

* Git & GitHub

---

# 📂 Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
│   └── shopping_data.csv
│
├── python/
│   ├── data_cleaning.ipynb
│   └── preprocessing.py
│
├── sql/
│   └── business_analysis.sql
│
├── dashboard/
│   └── Shopping_Behavior_Dashboard.pbix
│
├── screenshots/
│   └── dashboard_preview.png
│
├── report/
│   └── project_report.pdf
│
└── README.md
```

---

# 📚 What I Learned

* Data Cleaning using Python
* Missing Value Treatment
* Feature Engineering
* Database Integration with PostgreSQL
* Writing Business-Oriented SQL Queries
* Building Interactive Power BI Dashboards
* Translating Data into Actionable Business Insights

---

## 📚 What I Learned

- Data Cleaning using Python
- Feature Engineering
- PostgreSQL Integration
- SQL Analysis
- Power BI Dashboard Development

---

## 👨‍💻 Author

**Somesh Kumar Banjare**

Data Analyst | Aspiring Data Engineer | Power BI Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somesh-banjare-81278228b)

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Someshbanjare26)

⭐ If you found this project useful, consider giving it a star!
