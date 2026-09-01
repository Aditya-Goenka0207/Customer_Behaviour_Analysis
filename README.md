# 🛍️ Customer Shopping Behaviour Analysis

### End-to-End Data Analytics Project | Python • MySQL • Power BI • Business Intelligence

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/MySQL-SQL%20Analysis-orange?style=for-the-badge&logo=mysql" />
  <img src="https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow?style=for-the-badge&logo=powerbi" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-purple?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github" />
</p>

---

## 📌 Project Overview

**Customer Shopping Behaviour Analysis** is an end-to-end Data Analytics project designed to understand **customer purchasing patterns, product performance, revenue drivers, and customer segments**.

The project follows a complete analytics workflow:

```text
Raw Dataset
     ↓
Python Data Loading
     ↓
Exploratory Data Analysis
     ↓
Data Cleaning & Transformation
     ↓
MySQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
     ↓
Recommendations & Reporting
```

The objective is not simply to analyze data, but to transform raw customer transaction data into **actionable business insights that can support better marketing, customer retention, product strategy, and revenue decisions.**

---

# 🎯 Business Problem

Businesses generate large amounts of customer transaction data, but raw data alone does not explain:

* Who the most valuable customers are
* Which products and categories drive revenue
* How customer demographics affect purchasing behaviour
* Which customers are likely to become repeat buyers
* What factors influence spending
* How sales change across different customer segments
* Where opportunities exist to improve revenue and customer retention

This project addresses these questions by combining **Python, SQL, and Power BI** into a single analytical workflow.

---

# ❓ Key Business Questions

The analysis focuses on answering questions such as:

### 👥 Customer Analysis

* Who are the highest-value customers?
* Which customer segments contribute the most revenue?
* What percentage of customers are repeat buyers?
* How does spending differ across age groups?
* How does purchasing behaviour differ by gender?

### 🛒 Product & Category Analysis

* Which categories generate the highest revenue?
* Which products perform the best?
* Which categories have the strongest customer demand?
* Which product segments should receive greater attention?

### 💰 Revenue Analysis

* What is the total revenue?
* What is the Average Order Value?
* How does revenue change over time?
* Which customer segments contribute the most revenue?
* Which categories represent the biggest revenue opportunities?

### 📈 Customer Behaviour

* What purchasing patterns can be identified?
* Which customer groups are more likely to make repeat purchases?
* Which segments should receive targeted marketing campaigns?

---

# 🗂️ Dataset

The project uses the following dataset:

**`customer_shopping_behavior.csv`**

The dataset contains customer shopping and transactional information that can be used to analyze:

* Customer demographics
* Product categories
* Purchase behaviour
* Transaction values
* Customer segments
* Revenue patterns
* Shopping frequency

The dataset was first explored and cleaned using Python before being used for SQL and Power BI analysis.

---

# 🛠️ Technology Stack

| Technology                | Purpose                               |
| ------------------------- | ------------------------------------- |
| 🐍 **Python**             | Data loading, EDA and data cleaning   |
| 🐼 **Pandas**             | Data manipulation and transformation  |
| 🔢 **NumPy**              | Numerical analysis                    |
| 📊 **Matplotlib**         | Data visualization                    |
| 📈 **Seaborn**            | Statistical visualization             |
| 🗄️ **MySQL**             | Business analysis using SQL           |
| 📊 **Power BI**           | Interactive dashboard                 |
| 📄 **Jupyter Notebook**   | Python analysis                       |
| 📑 **PDF**                | Final project report                  |
| 🎤 **PowerPoint / Gamma** | Business presentation                 |
| 🐙 **GitHub**             | Version control and project portfolio |

---

# 🔄 Project Methodology

## 1️⃣ Data Loading

The raw CSV dataset was loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")

df.head()
df.info()
df.shape
```

The initial analysis focused on understanding:

* Dataset dimensions
* Column names
* Data types
* Missing values
* Duplicate records
* Basic statistics
* Data distributions

---

# 2️⃣ Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the underlying patterns in customer behaviour.

### EDA included:

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Category analysis
* Customer segmentation
* Distribution analysis
* Correlation analysis
* Outlier detection
* Revenue analysis
* Trend analysis

The objective was to identify patterns that could later be investigated through SQL and Power BI.

---

# 3️⃣ Data Cleaning

Before performing business analysis, the dataset was cleaned and standardized.

### Cleaning activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Checking inconsistent records
* Identifying outliers
* Creating derived/calculated fields
* Validating the cleaned dataset

The cleaned data was then prepared for database analysis and visualization.

---

# 4️⃣ SQL Analysis — MySQL

The cleaned dataset was imported into **MySQL** for deeper business analysis.

SQL was used to transform the cleaned data into meaningful business insights.

### SQL concepts used:

```text
SELECT
WHERE
GROUP BY
ORDER BY
HAVING
CASE
Aggregate Functions
JOIN
Subqueries
CTEs
Window Functions
Date Functions
```

### Example analysis areas:

* Total revenue
* Customer spending
* Top customers
* Category performance
* Product performance
* Revenue trends
* Customer segmentation
* Repeat customer analysis
* Average order value
* Age-group analysis

SQL queries are available in:

```text
Customer_Behaviour_Analysis.sql
```

---

# 5️⃣ Power BI Dashboard

The analyzed data was transformed into an interactive **Power BI dashboard**.

The dashboard provides a business-focused view of customer shopping behaviour.

### 📊 Dashboard Components

* KPI Cards
* Revenue Analysis
* Customer Analysis
* Product Performance
* Category Performance
* Customer Segmentation
* Demographic Analysis
* Revenue Trends
* Interactive Slicers
* Dynamic Filtering
* Business KPIs

### Key KPIs

| KPI                     | Purpose                           |
| ----------------------- | --------------------------------- |
| 💰 Total Revenue        | Measures overall business revenue |
| 👥 Total Customers      | Measures customer base            |
| 🛒 Total Orders         | Measures transaction volume       |
| 💵 Average Order Value  | Measures average customer spend   |
| 🔁 Repeat Customer Rate | Measures customer retention       |
| 🏆 Top Category         | Identifies strongest category     |

The Power BI file is available in:

```text
Customer_Behaviour_Dashboard.pbix
```

---

# 📊 Dashboard Preview

> Add your Power BI dashboard screenshot here for the best GitHub presentation.

```text
📸 Dashboard Screenshot

[ Upload Dashboard Screenshot Here ]
```



# 📈 Key Insights

The analysis helps identify several important business patterns:

### 💰 Revenue Drivers

Identified the products and categories responsible for the largest share of revenue.

### 👥 Customer Segmentation

Different customer groups were compared based on spending and purchasing behaviour to identify high-value segments.

### 🔁 Repeat Customers

Repeat purchasing behaviour was analyzed to understand customer loyalty and retention opportunities.

### 🛒 Product Performance

Products and categories were evaluated based on sales contribution and customer demand.

### 📅 Revenue Trends

Revenue patterns were analyzed across time to identify changes in purchasing behaviour and potential seasonal trends.

### 🎯 Customer Demographics

Purchasing behaviour was compared across demographic segments such as age groups and gender.

---

# 💡 Business Recommendations

Based on the analysis, businesses can consider the following strategies:

### 1. 🎯 Target High-Value Customers

Identify customers contributing significant revenue and provide personalized offers, loyalty rewards, and exclusive promotions.

### 2. 🔁 Improve Customer Retention

Use purchasing frequency and customer segments to identify opportunities for increasing repeat purchases.

### 3. 🛍️ Focus on High-Performing Categories

Allocate marketing and inventory resources toward categories that consistently generate strong revenue.

### 4. 📢 Personalize Marketing

Create targeted campaigns based on customer demographics, purchase behaviour, and product preferences.

### 5. 📈 Optimize Sales Strategy

Use historical revenue trends and customer behaviour to improve future sales planning.

### 6. 💰 Increase Average Order Value

Use cross-selling, product bundles, and personalized recommendations to increase the value of each transaction.

---

# 📁 Repository Structure

```text
Customer_Behaviour_Analysis/
│
├── 📊 customer_shopping_behavior.csv
│
├── 🐍 Customer_Shopping_Behaviour_Analysis.ipynb
│
├── 🗄️ Customer_Behaviour_Analysis.sql
│
├── 📊 Customer_Behaviour_Dashboard.pbix
│
├── 📄 Customer Shopping Behavior Analysis.pdf
│
├── 🎤 Customer-Shopping-Behavior-Analysis.pptx
│
└── 📖 README.md
```

---

# 📚 Project Deliverables

### 🐍 Python Notebook

**`Customer_Shopping_Behaviour_Analysis.ipynb`**

Contains:

* Data loading
* Data exploration
* EDA
* Data cleaning
* Data transformation
* Visual analysis

### 🗄️ SQL Script

**`Customer_Behaviour_Analysis.sql`**

Contains SQL queries used for business analysis.

### 📊 Power BI Dashboard

**`Customer_Behaviour_Dashboard.pbix`**

Interactive dashboard containing customer, product, category, revenue, and KPI analysis.

### 📄 Project Report

**`Customer Shopping Behavior Analysis.pdf`**

Detailed documentation of the project, methodology, analysis, insights, and recommendations.

### 🎤 Business Presentation

**`Customer-Shopping-Behavior-Analysis.pptx`**

Business-focused presentation summarizing the project findings.

---

# 🚀 How to Run the Project

## Step 1 — Clone the Repository

```bash
git clone https://github.com/Aditya-Goenka0207/Customer_Behaviour_Analysis.git
```

```bash
cd Customer_Behaviour_Analysis
```

---

## Step 2 — Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## Step 3 — Run the Python Notebook

Launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
Customer_Shopping_Behaviour_Analysis.ipynb
```

Run the notebook sequentially to perform:

```text
Data Loading
     ↓
EDA
     ↓
Data Cleaning
     ↓
Data Transformation
```

---

## Step 4 — Perform SQL Analysis

Open MySQL Workbench and create a database.

```sql
CREATE DATABASE customer_behavior_analysis;
```

Select the database:

```sql
USE customer_behavior_analysis;
```

Import the cleaned dataset and execute:

```text
Customer_Behaviour_Analysis.sql
```

---

## Step 5 — Open Power BI Dashboard

Open:

```text
Customer_Behaviour_Dashboard.pbix
```

If necessary, update the data source connection to your local MySQL/database environment.

---

# 🧠 Skills Demonstrated

This project demonstrates practical Data Analyst skills across the complete analytics lifecycle.

### Technical Skills

```text
Python
Pandas
NumPy
Matplotlib
Seaborn
SQL
MySQL
Power BI
DAX
Data Cleaning
EDA
Data Visualization
```

### Analytical Skills

```text
Business Problem Solving
Customer Segmentation
Revenue Analysis
Trend Analysis
KPI Development
Customer Behaviour Analysis
Data Storytelling
Business Recommendations
```

### Professional Skills

```text
Requirement Understanding
Analytical Thinking
Insight Generation
Business Communication
Dashboard Design
Data Storytelling
Report Creation
Presentation
```

---

# 🎯 Business Impact

This project demonstrates how an organization can move from:

> **Raw transactional data → Structured analysis → Business insights → Data-driven decisions**

The analysis can help stakeholders make better decisions around:

* Customer retention
* Marketing campaigns
* Product strategy
* Revenue growth
* Customer segmentation
* Sales planning
* Business performance

---

# 🔮 Future Enhancements

The project can be further enhanced by adding:

### 🤖 Machine Learning

* Customer churn prediction
* Customer lifetime value prediction
* Purchase propensity modeling
* Customer segmentation using clustering

### 📊 Advanced Power BI

* Drill-through pages
* Tooltip pages
* What-if analysis
* Advanced DAX measures
* Automated refresh

### ⚙️ Data Engineering

* Automated ETL pipeline
* Scheduled database updates
* Cloud database integration
* Automated Power BI refresh

### 📈 Advanced Analytics

* RFM Customer Segmentation
* Cohort Analysis
* Customer Lifetime Value
* Market Basket Analysis
* Predictive Sales Analysis

---

# 🏆 Why This Project Matters

This is more than a collection of SQL queries or charts.

It demonstrates an **end-to-end Data Analyst workflow**:

```text
        BUSINESS PROBLEM
              ↓
         RAW DATA
              ↓
       PYTHON + EDA
              ↓
      DATA CLEANING
              ↓
       MYSQL + SQL
              ↓
      POWER BI DASHBOARD
              ↓
       BUSINESS INSIGHTS
              ↓
      RECOMMENDATIONS
              ↓
       BUSINESS DECISIONS
```

This approach mirrors how data is used in real-world business environments.

---

# 👨‍💻 Author

## Aditya Goenka

**B.Tech Computer Science Engineering | Aspiring Data Analyst**

### Areas of Interest

* Data Analytics
* Business Intelligence
* SQL
* Python
* Power BI
* Data Visualization
* Business Analytics

### 🔗 GitHub

[Aditya-Goenka0207](https://github.com/Aditya-Goenka0207)

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.

**Thanks for visiting!**
