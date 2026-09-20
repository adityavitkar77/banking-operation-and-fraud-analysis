# 🏦 Banking Operation and Fraud Analysis

## 📌 Project Overview

This project analyzes **banking Operation and card transactions** to understand transaction patterns, customer and account activity, loan information, and potential fraudulent transactions.

The project uses **Python, SQL, Excel, and Power BI** for data cleaning, exploratory data analysis, SQL analysis, and interactive dashboard reporting.

The main objective is to identify important banking trends, analyze transaction behavior, monitor fraud patterns, and generate meaningful business insights through data analysis and visualization.

---

## 🎯 Project Objectives

* Analyze customer and account information.
* Understand banking transaction patterns.
* Analyze transaction amounts, types, and channels.
* Identify and analyze potentially fraudulent card transactions.
* Calculate fraud transactions, fraud amount, and fraud rate.
* Analyze loan information and repayment-related data.
* Compare transaction activity across different categories.
* Create interactive Power BI dashboards for business reporting.
* Generate insights that can support banking decision-making.

---

## 🛠️ Tools & Technologies

  * Python
  * Pandas
  * NumPy
  * SQL
  *Power BI

---

## 📂 Dataset

The project contains multiple banking-related tables:

* `customer`
* `accounts`
* `branches`
* `employee`
* `transaction`
* `card_transaction`
* `cards`
* `loans`
* `loan_payment`
* `support_ticket`

These tables contain information related to customers, accounts, branches, transactions, cards, fraud indicators, loans, loan payments, and support activities.

---

## 🔍 Analysis Performed

### 👤 Customer & Account Analysis

* Total number of customers
* Customer activity analysis
* Customer distribution
* Account types
* Account balances
* Active and inactive accounts

### 🏦 Branch & Employee Analysis

* Number of branches
* Branch-wise activity
* Employee distribution
* Transaction activity by branch

### 💳 Transaction Analysis

* Total number of transactions
* Total transaction amount
* Transaction type analysis
* Transaction channel analysis
* Transaction trends over time
* High-value transactions
* Customer transaction activity

### 🚨 Fraud Analysis

* Total card transactions
* Fraud transactions
* Fraud amount
* Fraud rate
* Fraud transactions by merchant category
* Fraud trends over time
* Customer-level fraud activity
* Card-level fraud analysis

### 💰 Loan Analysis

* Total loans
* Total loan amount
* Average loan amount
* Loan type analysis
* Loan status analysis
* Interest rate analysis
* Loan duration analysis
* Loan payment analysis
* Late payment analysis

---

## 🧹 Data Cleaning & Preparation

Python and Power Query were used for data preparation, including:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Date conversion
* Data validation
* Column formatting
* Preparing data for analysis and visualization

---

## 🐍 Python / EDA

Exploratory Data Analysis was performed using **Jupyter Notebook** with Pandas, NumPy, Matplotlib, and Seaborn.

The analysis includes:

* Data understanding
* Data type analysis
* Missing value analysis
* Duplicate checking
* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Transaction analysis
* Fraud analysis
* Loan analysis
* Data visualization

---

## 🗄️ SQL Analysis

SQL was used to perform analytical queries on the banking database.

Key SQL concepts used:

* SELECT and WHERE
* GROUP BY and HAVING
* ORDER BY
* Aggregate Functions
* INNER JOIN
* LEFT JOIN
* SELF JOIN
* Subqueries
* CTEs
* CASE statements
* Window Functions

## 📊 Power BI Dashboard

The Power BI report is divided into multiple analytical sections.

### Page 1 — Banking Overview

**KPIs:**

* Total Customers
* Total Accounts
* Total Transactions
* Transaction Amount
* Total Loans
* Loan Amount
* Fraud Amount
* Fraud Rate %

**Visualizations:**

* Monthly Transaction Trend
* Transactions by Channel
* Transactions by Type
* Branch-wise Analysis
* Customer Transaction Analysis

---

### Page 2 — Fraud Analysis

**KPIs:**

* Card Transactions
* Fraud Transactions
* Fraud Amount
* Fraud Rate %

**Visualizations:**

* Fraud Trend Over Time
* Fraud by Merchant Category
* Fraud vs Normal Transactions
* Fraud by Card Type
* Top Customers by Fraud Amount

**Filters/Slicers:**

* Merchant Category
* Card Type
* Fraud Status

---

### Page 3 — Loan & Customer Analysis

**KPIs:**

* Total Loans
* Average Loan Amount
* Total Loan Amount
* Amount Paid
* Interest Paid
* Late Payments

**Visualizations:**

* Loans by Loan Type
* Loan Status
* Loan Amount by Category
* Loan Payment Analysis
* Credit Score vs Loan Amount


## 📁 Project Structure

```text
Banking-Transactions-and-Fraud-Analysis/
│
├── data/
│   ├── customer.csv
│   ├── accounts.csv
│   ├── branches.csv
│   ├── employee.csv
│   ├── transaction.csv
│   ├── card_transaction.csv
│   ├── cards.csv
│   ├── loans.csv
│   ├── loan_payment.csv
│   └── support_ticket.csv
│
├── python/
│   └── banking_eda.ipynb
│
├── sql/
│   └── banking_analysis.sql
│
├── powerbi/
│   └── banking_transactions_fraud_analysis.pbix
│
├── screenshots/
│   ├── banking_overview.png
│   ├── fraud_analysis.png
│   
│
└── README.md

```
