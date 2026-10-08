# Retail Customer Purchase & Sales Analysis

## Overview

This project analyzes **3,900 retail purchase records** to understand customer behavior, purchasing patterns, product performance, and sales trends.

The project follows a practical data analytics workflow:

**Raw Data → Data Cleaning → Feature Engineering → SQL Analysis → Dashboard → Business Insights**

The analysis was performed using **Python, MySQL, and Power BI**.

---

## Dataset

The dataset contains **3,900 purchase records** and 18 columns covering:

* Customer demographics
* Product and category information
* Purchase amount
* Location and season
* Review ratings
* Subscription status
* Shipping type
* Discount and promo usage
* Previous purchases
* Payment method
* Purchase frequency

---

## Tools & Technologies

* **Python** — Data cleaning and feature engineering
* **Pandas / NumPy** — Data manipulation
* **MySQL** — SQL analysis
* **Power BI** — Dashboard and visualization
* **GitHub** — Project documentation

---

## Project Steps

### 1. Data Cleaning

* Inspected the dataset and data types
* Checked missing values and duplicates
* Standardized text values
* Cleaned column names
* Handled missing review ratings using category-level median imputation
* Prepared the dataset for analysis

### 2. Feature Engineering

Created additional features such as:

* Customer age groups using quartiles
* Numerical purchase-frequency intervals
* Customer segments based on previous purchases

### 3. SQL Analysis

Used MySQL to answer business questions related to:

* Revenue by gender
* Customer spending
* Discount usage
* Product performance
* Subscription behavior
* Customer segmentation
* Product rankings within categories
* Purchase amount by category
* Seasonal sales and revenue
* Location-level sales
* Repeat customer behavior

SQL techniques included:

* Aggregations
* `CASE WHEN`
* Subqueries
* CTEs
* Window functions
* Ranking
* Conditional calculations

---

## Dashboard

A Power BI dashboard was created to present the main findings visually.

The dashboard covers:

* Sales and revenue
* Customer segments
* Product performance
* Category performance
* Customer demographics
* Seasonal trends
* Purchase behavior

---

## Key Result

One notable finding from the analysis:

**Male customers generated $157,890 in revenue, compared with $75,191 from female customers.**

However, total revenue alone does not explain the reason for this difference.

Further analysis should consider:

* Number of customers by gender
* Average purchase amount
* Purchase frequency
* Previous purchases

This demonstrates an important analytical principle:

> A difference in revenue is a finding, not necessarily an explanation.

---

## Project Deliverables

The repository includes:

* **Cleaned Dataset**
* **Python Notebook**
* **MySQL SQL Queries**
* **Power BI Dashboard**
* **Project Report**
* **Project Presentation**
* **README Documentation**

---

## How to Run

### Python

Open the Python notebook and install the required libraries:

```bash
pip install pandas numpy
```

Run the notebook to reproduce the data cleaning and feature engineering steps.

### MySQL

Create the database:

```sql
CREATE DATABASE retail_analysis;
```

Select the database:

```sql
USE retail_analysis;
```

Import the cleaned dataset into the `customer_analysis` table.

Run the SQL queries to reproduce the analysis.

### Power BI

Open the Power BI dashboard file and refresh the data source if required.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python / Pandas
* SQL / MySQL
* CTEs
* Window Functions
* Customer Segmentation
* Business Question Formulation
* Data Visualization
* Power BI
* Business Insight Generation
* Analytical Thinking

---

## Conclusion

This project demonstrates the complete analytics process:

**Understand the Data → Ask Business Questions → Analyze → Identify Patterns → Generate Insights → Communicate Findings**

The focus was not only on writing Python and SQL, but on using data to answer practical business questions and support decision-making.
