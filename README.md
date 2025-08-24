# 📊 Retail Sales SQL Project

## 📌 Project Overview

This project analyzes **retail sales data** using SQL queries.\
It covers **data cleaning, aggregation, customer insights, and sales
analysis** to understand business performance.

The dataset is stored in a single table:

``` sql
CREATE TABLE retail_sales (
    transactions_id INT PRIMARY KEY,
    sale_date DATE,
    sale_time TIME,
    customer_id INT,
    gender VARCHAR(20),
    age INT,
    category VARCHAR(50),
    quantiy INT,
    price_per_unit FLOAT,   
    cogs FLOAT,
    total_sale FLOAT
);
```

------------------------------------------------------------------------

## 🛠 SQL Concepts Used

-   **DDL (Data Definition Language)** -- Creating tables
-   **DML (Data Manipulation Language)** -- Inserting/Deleting records
-   **Filtering & WHERE conditions**
-   **Aggregations (SUM, AVG, COUNT)**
-   **GROUP BY & HAVING**
-   **Ranking with Window Functions**
-   **Case statements**
-   **Date & Time functions**

------------------------------------------------------------------------

## 📑 Queries Performed

1.  ✅ Data Cleaning -- Remove rows with missing values.\
2.  📌 Find distinct product categories.\
3.  📅 Count sales on a particular date.\
4.  👕 Find clothing sales where quantity \> 10 in November 2022.\
5.  💰 Calculate total sales by category.\
6.  👩‍🦰 Find average age of customers (by category).\
7.  💵 Find transactions where total sale \> 1000.\
8.  👨‍👩‍👧 Transactions grouped by **gender & category**.\
9.  📈 Find the **best-selling month** in each year.\
10. 🏆 Top 5 customers by total sales.\
11. 🛍 Find unique customers by category.\
12. ⏰ Categorize orders by **Morning, Afternoon, Evening** shifts.

------------------------------------------------------------------------

## 🚀 How to Use

1.  Import the `retail_sales.sql` file into your SQL database.

    ``` bash
    mysql -u username -p database_name < retail_sales.sql
    ```

2.  Run the SQL queries step by step to explore insights.\

3.  Modify queries to suit your analysis needs.

------------------------------------------------------------------------

## 📊 Sample Insights

-   Identify the **best-selling product categories**.\
-   Find **high-value customers** for loyalty programs.\
-   Discover **peak sales hours** (morning, afternoon, evening).\
-   Understand **monthly sales trends**.

------------------------------------------------------------------------

## 📌 Future Enhancements

-   Build a **Power BI / Tableau Dashboard** using this data.\
-   Add **stored procedures** for automated reports.\
-   Integrate with **Python (Pandas + SQLAlchemy)** for advanced
    analysis.

------------------------------------------------------------------------

## 👩‍💻 Author

**Shaily Bhargava**\
💼 BCA Student \| Data Enthusiast \| Aspiring Data Analyst
