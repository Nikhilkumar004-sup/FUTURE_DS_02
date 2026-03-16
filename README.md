# Customer Retention & Churn Analysis

# Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses such as SaaS platforms, telecom providers, fintech apps, and online learning services.

This project analyzes customer behavior to understand:

* Why customers leave a service
* Which customer segments are most likely to churn
* How long customers typically remain active
* What strategies businesses can implement to improve customer retention

The goal of this project is to generate **data-driven insights that help businesses reduce churn and improve customer lifetime value.**

# Business Problem

Customer acquisition is expensive, and losing existing customers directly affects revenue growth.

Businesses need to answer important questions such as:

* Why are customers leaving the platform?
* Which customer segments are most at risk of churn?
* How long do customers typically stay with the company?
* What actions can improve retention and customer loyalty?

This analysis simulates the type of work performed by **data analysts in product, growth, and retention teams.**

# Dataset

This project uses the **Telco Customer Churn Dataset**.

Dataset Source: Kaggle
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains customer demographic information, service subscriptions, billing details, and churn status.

### Dataset Overview

* Total Customers: 7043
* Features: 21 columns
* Target Variable: **Churn**

### Key Variables

* customerID – Unique identifier
* gender – Customer gender
* tenure – Months with the company
* InternetService – Internet plan type
* Contract – Subscription contract type
* MonthlyCharges – Monthly payment amount
* TotalCharges – Total amount paid by the customer
* PaymentMethod – Payment method used
* Churn – Whether the customer left the service

# Tools & Technologies

This project uses multiple tools commonly used in real data analytics workflows.

**Programming & Analysis**

* Python
* Pandas
* NumPy

**Data Visualization**

* Matplotlib
* Seaborn

**Version Control**

* Git & GitHub

# Data Analysis Process

The project follows a structured analytics workflow.

### 1. Data Cleaning

* Removed missing values
* Converted TotalCharges to numeric format
* Standardized churn variable

### 2. Exploratory Data Analysis

Analyzed customer behavior across multiple dimensions:

* Contract type
* Internet service
* Payment method
* Customer tenure
* Monthly charges

### 3. Churn Pattern Analysis

Identified which customer groups show higher churn rates.

### 4. Cohort Analysis

Customers were segmented based on **tenure groups** to understand retention trends over time.

### 5. Customer Lifetime Analysis

Estimated customer lifetime value using:

* Average monthly revenue
* Average customer tenure

### 6. Retention Driver Analysis

Correlation analysis was used to identify key variables influencing churn.

# Key Insights

### Churn Patterns

* Customers on **month-to-month contracts** show the highest churn rates.
* Customers using **electronic check payments** tend to churn more frequently.
* **Fiber optic internet users** show higher churn compared to DSL users.

### Retention Trends

* The majority of churn occurs during the **first 6 months** of subscription.
* Customers with **long-term contracts** demonstrate stronger retention.

### Customer Lifetime Trends

* Customers who remain longer generate significantly higher lifetime value.
* Longer tenure strongly correlates with reduced churn probability.

# Business Recommendations

Based on the analysis, the following strategies are recommended:

### Encourage Long-Term Contracts

Offer discounts or incentives for customers who switch from month-to-month plans to yearly contracts.

### Improve Customer Onboarding

The first 6 months are critical. Improve early engagement through onboarding support and product education.

### Launch Retention Campaigns

Target high-risk customers with personalized offers and proactive support.

### Reward Loyal Customers

Introduce loyalty programs for long-tenure customers.

### Monitor High-Churn Segments

Focus retention strategies on customer groups with high churn rates.



# Why This Project Matters

Customer retention analytics is one of the **highest impact areas in data science and analytics**.

Reducing churn can significantly improve:

* Customer lifetime value
* Business revenue
* Product engagement
* Long-term growth

This project demonstrates how data can be used to **translate customer behavior into actionable business strategy.**

---

# Author
Nikhil Kumar D N

