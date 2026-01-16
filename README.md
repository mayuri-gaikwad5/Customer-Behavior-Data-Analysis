# 📊 End-to-End Customer Behavior Data Analysis

## 📌 Project Overview

This project demonstrates a **complete end-to-end data analytics workflow** using real-world customer behavior data.  
Instead of learning tools in isolation, the goal was to understand **how each stage of analytics connects in a business context** — from problem definition to insights and reporting.

### Analytics Pipeline Followed

**Business Problem → Raw Data → Cleaning & Feature Engineering → Database Storage → SQL Analysis → Visualization → Insights**

---

## 🧠 1. Business Problem Definition

Businesses often face challenges in understanding customer behavior and performance drivers.

This project focuses on answering key business questions such as:

- Which products perform best based on customer ratings?
- Which customer age groups generate the most revenue?
- How does subscription status affect customer distribution?
- What purchasing patterns emerge across product categories?

Clearly defining these questions helped guide every technical decision in the analysis.

---

## 🗂️ 2. Dataset Overview (Raw Data)

The dataset represents **customer behavior data**, including:

- Customer demographics (age, gender)
- Product and category information
- Purchase frequency
- Review ratings
- Subscription status
- Payment and shipping methods

### Initial Data Challenges

- Missing values
- Categorical variables in text format
- Columns not directly suitable for analysis

Understanding the structure and quality of raw data was essential before moving forward.

---

## 🧹 3. Data Cleaning & Feature Engineering (Python)

### Tools Used

- **Python**
- **Pandas**
- **NumPy**

### Key Steps

#### 3.1 Handling Missing Values
- Missing review ratings were filled using **category-level median values**.

#### 3.2 Feature Engineering

**Age Group**
- Young Adult
- Adult
- Middle-aged
- Senior

**Purchase Frequency (Days)**
- Converted textual frequencies into numeric day values.

---

## 🛢️ 4. Database Storage (MySQL)

After cleaning, the dataset was exported from Python and stored in **MySQL**.

### Why MySQL?

- Simulates real-world production systems
- Enables scalable querying
- Separates processing from analysis

---

## 🧮 5. SQL-Based Analysis

### SQL Concepts Applied

- `GROUP BY`
- `AVG()`
- `ORDER BY`
- `LIMIT`

### Insights

- Top 5 products by average rating
- Revenue distribution by age group
- Category-level performance comparison

---

## 📊 6. Visualization & Dashboarding (Power BI)

### Dashboard Components

- KPI Cards (Average Purchase, Rating, Customers)
- Revenue by Age Group
- Revenue by Category
- Subscription Distribution
- Product-wise Average Purchase

### Filters Used

- Gender
- Subscription Status
- Category
- Payment Method
- Shipping Type

---

## 🔍 7. Insights & Findings

- Majority customers are **non-subscribers**
- **Young Adults** generate highest revenue
- Certain categories outperform others
- High-value products offer upselling opportunities

---

## 🎯 8. Key Learnings

- Data analysis is a **process**, not tools alone
- Cleaning is the most critical step
- SQL enables structured analytics
- Visuals must translate into insights

---

