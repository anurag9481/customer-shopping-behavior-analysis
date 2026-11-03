# Customer Shopping Behavior Analysis
<p align="center">
  <img src="data analysis thumbnail.jpeg" width="800">
</p>

## Project Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, and business insights using Python, SQL, and Power BI.

The analysis is based on customer shopping transaction data containing 3,900 records and 18 columns. It explores customer demographics, product categories, purchase amounts, discounts, subscriptions, shipping preferences, and customer reviews.

The main objective is to transform raw shopping data into meaningful insights that can help businesses understand their customers and make better data-driven decisions.

## Project Objectives

- Analyze customer purchasing behavior.
- Identify popular product categories.
- Understand customer spending patterns.
- Compare purchasing behavior across different age groups and genders.
- Analyze the impact of discounts and promotions.
- Compare subscribed and non-subscribed customers.
- Identify seasonal shopping trends.
- Create SQL queries to answer business questions.
- Build an interactive Power BI dashboard.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SQL | Business data analysis |
| PostgreSQL / MySQL | Database management |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Data analysis environment |
| Git & GitHub | Version control |

## Dataset Information

The dataset contains customer shopping transaction information.

- Total Records: 3,900
- Total Columns: 18

### Important Features

| Column | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Item Purchased | Product purchased |
| Category | Product category |
| Purchase Amount (USD) | Amount spent by the customer |
| Location | Customer location |
| Size | Purchased product size |
| Color | Product color |
| Season | Shopping season |
| Review Rating | Customer review rating |
| Subscription Status | Whether the customer has a subscription |
| Shipping Type | Shipping method |
| Discount Applied | Whether a discount was applied |
| Promo Code Used | Whether a promotional code was used |
| Previous Purchases | Number of previous purchases |
| Payment Method | Customer payment method |
| Frequency of Purchases | How frequently the customer purchases |

## Project Workflow

### 1. Data Loading

- Imported the dataset using Pandas.
- Examined the dataset structure.
- Checked the number of rows and columns.
- Reviewed data types and sample records.

### 2. Data Cleaning and Preprocessing

- Checked for missing values.
- Identified duplicate records.
- Reviewed incorrect data types.
- Handled missing values where appropriate.
- Prepared the dataset for analysis.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand customer behavior.

Key areas explored:

- Customer demographics.
- Gender distribution.
- Age distribution.
- Product category performance.
- Purchase amount distribution.
- Seasonal purchasing patterns.
- Customer subscription behavior.
- Discount and promotional code usage.
- Customer review ratings.
- Payment method preferences.

### 4. SQL Analysis

Used SQL to answer business-related questions and extract meaningful insights.

Examples of business questions:

1. What is the total revenue generated?
2. Which product categories generate the highest revenue?
3. Which products are purchased most frequently?
4. What is the average purchase amount?
5. Which age groups spend the most?
6. How do subscribed and non-subscribed customers compare?
7. Which seasons generate the highest sales?
8. What is the relationship between discounts and purchase behavior?
9. Which locations have the highest number of purchases?
10. Which customers have made the most previous purchases?

### 5. Power BI Dashboard

Created a dashboard to present key business insights visually.

The dashboard focuses on:

- Total revenue.
- Total customers.
- Average purchase amount.
- Product category performance.
- Customer demographics.
- Seasonal trends.
- Subscription analysis.
- Discount analysis.

## Key Business Insights

The analysis aims to identify:

- Customer purchasing preferences.
- High-performing product categories.
- Differences in spending across customer groups.
- Seasonal changes in shopping behavior.
- Subscription patterns.
- Customer responses to discounts and promotional offers.
- Opportunities to improve customer engagement and retention.

Actual findings and numerical results will be added after completing the analysis.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
│
├── customer_behavior_sql_queries.sql
│
├── customer_behavior_dashboard.pbix
│
├── README.md
│
└── dataset/
    └── customer_shopping_behavior.csv


## Installation and Setup

Follow these steps to install and run the project on your local machine.

### Prerequisites

- Python 3.9 or above
- Git
- PostgreSQL or MySQL
- Jupyter Notebook
- Power BI Desktop (Windows only)
```
### Step 1: Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

### Step 2: Navigate to the Project Directory

cd customer-trends-data-analysis-SQL-Python-PowerBI


### Step 3: Create a Virtual Environment

```bash
python3 -m venv venv
```

### Step 4: Activate the Virtual Environment

**macOS/Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### Step 5: Upgrade pip

```bash
python -m pip install --upgrade pip
```

### Step 6: Install Required Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql psycopg2-binary jupyter ipykernel
```

### Step 7: Register the Jupyter Kernel

```bash
python -m ipykernel install --user --name=customer-analysis --display-name "Python (Customer Analysis)"
```

### Step 8: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 9: Run the Python Analysis

1. Open `Customer_Shopping_Behavior_Analysis.ipynb`.
2. Select the `Python (Customer Analysis)` kernel.
3. Run the notebook cells sequentially.
4. Explore the data cleaning, exploratory data analysis, and visualizations.

### Step 10: Set Up the Database

For PostgreSQL, create a database:

```sql
CREATE DATABASE customer_behavior;
```

Configure your database connection using SQLAlchemy in the notebook.

Load the customer shopping dataset into the database before running the SQL queries.

### Step 11: Execute SQL Queries

Open:

```text
customer_behavior_sql_queries.sql
```

Execute the queries using PostgreSQL (pgAdmin) or MySQL Workbench.

### Step 12: Open the Power BI Dashboard

Open:

```text
customer_behavior_dashboard.pbix
```

Use Power BI Desktop to explore the interactive dashboard.

**Note:** Power BI Desktop is designed for Windows. Mac users can access Power BI Service or use a Windows environment.

### Troubleshooting

**Check Python version:**

```bash
python --version
```

**Install a missing package:**

```bash
pip install package_name
```

**Verify installed packages:**

```bash
pip list
```

**Deactivate the virtual environment:**

```bash
deactivate
```

### Project Execution Summary

After completing the installation:

1. Run the Jupyter Notebook.
2. Perform data cleaning and preprocessing.
3. Conduct exploratory data analysis using Python.
4. Connect the dataset to PostgreSQL or MySQL.
5. Execute SQL queries to answer business questions.
6. Explore customer insights using the Power BI dashboard.
