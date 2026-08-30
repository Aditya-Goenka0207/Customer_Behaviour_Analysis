# Customer_Behaviour_Analysis

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data loading and exploration in Python to SQL analysis, interactive Power BI dashboard creation, business reporting, and presentation.

The goal of the project is to transform raw data into **meaningful business insights** that can support data-driven decision-making.

### Project Workflow

**Raw Dataset → Python EDA → Data Cleaning → SQL Analysis → Power BI Dashboard → Report → PPT Presentation**

---

## 📁 Dataset

The project uses a structured dataset containing relevant business/customer/transactional information.

The dataset was initially loaded into Python for:

* Understanding the structure of the data
* Checking data types
* Identifying missing values
* Detecting duplicate records
* Finding outliers
* Understanding distributions and patterns
* Preparing the data for further analysis

> **Dataset:** `customer_shopping_behavior.csv`

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                                   |
| ----------------------------------- | ----------------------------------------- |
| **Python**                          | Data loading, EDA & data cleaning         |
| **Pandas**                          | Data manipulation and analysis            |
| **NumPy**                           | Numerical operations                      |
| **Matplotlib / Seaborn**            | Data visualization                        |
| **MySQL / PostgreSQL / SQL Server** | SQL-based data analysis                   |
| **Power BI**                        | Interactive dashboard and visualization   |
| **Gamma**                           | Business presentation / PPT               |
| **GitHub**                          | Project documentation and version control |

---

# 🔄 Project Steps

## 1. Data Loading

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")

print(df.head())
print(df.info())
print(df.shape)
```

The initial analysis focused on understanding:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Duplicate records

---

## 2. Exploratory Data Analysis (EDA)

EDA was performed to identify trends, relationships, patterns, and anomalies in the dataset.

### Key EDA Activities

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Distribution analysis
* Correlation analysis
* Outlier detection
* Category-wise analysis
* Trend analysis

Example:

```python
df.describe()
```

Visualizations were created to better understand the data and identify important patterns.

---

## 3. Data Cleaning

The raw dataset was cleaned before performing further analysis.

### Cleaning Activities

* Handled missing values
* Removed duplicate records
* Corrected data types
* Standardized categorical values
* Handled inconsistent data
* Identified and treated outliers where required
* Created calculated/derived columns

The cleaned dataset was then prepared for SQL analysis and Power BI.

---

# 🗄️ 4. SQL Analysis

The cleaned data was imported into a relational database for further analysis.

SQL queries were used to answer important business questions.

### SQL Concepts Used

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* `CASE`
* Aggregate Functions
* `JOIN`
* Subqueries
* CTEs
* Window Functions

### Example Business Questions

* What is the total revenue?
* Which categories generate the highest revenue?
* Who are the top customers?
* What are the best-performing products?
* What is the monthly/ yearly revenue trend?
* Which customer segments generate the most revenue?
* What percentage of customers are repeat buyers?

SQL analysis was performed using **PostgreSQL / MySQL / SQL Server**.

---

# 📊 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive business dashboard.

### Dashboard Features

* KPI cards
* Revenue analysis
* Customer analysis
* Product/category performance
* Trend analysis
* Interactive filters and slicers
* Charts and graphs
* Drill-down analysis where applicable

### Key KPIs

* **Total Revenue**
* **Total Customers**
* **Total Orders**
* **Average Order Value**
* **Repeat Customer Rate**
* **Top-Performing Category**



# 📈 Results & Key Insights

The analysis generated several meaningful business insights.

### Key Findings

* Identified the highest-performing products/categories.
* Identified customer segments contributing the most revenue.
* Analyzed revenue trends over time.
* Identified high-value and repeat customers.
* Compared performance across different segments.
* Highlighted areas with potential for business growth.

These insights can help businesses improve **customer retention, sales performance, product strategy, and revenue generation**.

---

# 📄 Project Report

A detailed report was created to document:

* Business problem
* Dataset description
* Data cleaning process
* Exploratory analysis
* SQL analysis
* Dashboard findings
* Key insights
* Business recommendations

**Report:** `Customer Shopping Behavior Analysis.pdf`

---

# 🎯 Business Recommendations

Based on the analysis, potential recommendations include:

1. Focus on high-performing products and categories.
2. Develop targeted strategies for high-value customers.
3. Improve customer retention and repeat purchases.
4. Investigate underperforming categories.
5. Use historical trends to improve future sales planning.
6. Develop personalized marketing strategies based on customer behavior.

---

# 🎤 Presentation

A presentation was created using **Gamma** to communicate the project's findings in a concise and business-friendly format.

The presentation covers:

* Business problem
* Dataset
* Methodology
* Data analysis
* SQL insights
* Power BI dashboard
* Key findings
* Business recommendations

**Presentation:** `Customer-Shopping-Behavior-Analysis.pptx`

---

# ▶️ How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/Aditya-Goenka0207/Customer_Behaviour_Analysis.git
```

## 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

Customer_Shopping_Behaviour_Analysis.ipynb

Run the cells to perform data loading, EDA, and data cleaning.

## 4. SQL Analysis

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL scripts located in:

```text
sql/
```

## 5. Power BI Dashboard

Open:

Customer_Behaviour_Dashboard

Update the data source if required and refresh the dashboard.

---

# 📂 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw/
│   │   └── dataset.csv
│   └── cleaned/
│       └── cleaned_dataset.csv
│
├── notebooks/
│   └── EDA_and_Data_Cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Data_Analytics_Dashboard.pbix
│
├── report/
│   └── Data_Analytics_Report.pdf
│
├── presentation/
│   └── Data_Analytics_Project.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

# 💡 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas & NumPy
* Data Visualization
* SQL
* PostgreSQL / MySQL / SQL Server
* Power BI
* Dashboard Development
* Business Intelligence
* Data Storytelling
* Business Reporting
* Presentation Development

---

# 👨‍💻 Author

**Aditya Goenka**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Data Visualization

---

## ⭐ Project Objective

The primary objective of this project is to demonstrate the ability to take a **raw dataset and transform it into actionable business insights using an end-to-end data analytics workflow.**
