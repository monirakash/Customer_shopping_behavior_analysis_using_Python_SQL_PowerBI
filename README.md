
# 🛒 Customer Shopping Behavior Analysis

An end-to-end data analytics project demonstrating **Python, PostgreSQL, SQL, and exploratory data analysis (EDA)** skills. The project cleans raw shopping data, engineers useful features, loads the processed dataset into PostgreSQL, and answers business questions using advanced SQL.

## Project Objectives

- Clean and preprocess customer shopping data.
- Perform exploratory data analysis using Python.
- Engineer new analytical features.
- Load processed data into PostgreSQL.
- Solve real-world business problems using SQL.
- Demonstrate analytical thinking suitable for Data Analyst / Business Intelligence roles.

## Tech Stack

- Python (Pandas)
- Jupyter Notebook
- PostgreSQL
- SQL (CTEs, Window Functions, Aggregation)
- PowerBI
- CSV Dataset

## Repository Structure

```
.
├── shopping_behavior_analysis_of_customer---.ipynb   # Data cleaning & EDA
├── shopping_analysis.sql                              # Business SQL queries
|--- customer_behavior_analysis.pbix                   # Interactive Dashboard              
└── README.md
```

## Data Preparation

The notebook performs the following tasks:

- Summary statistics
- Missing value checking
- Rename columns to snake_case
- Create `age_group`
- Create `purchase_frequency_days`
- Validate discount and promotion columns
- Remove redundant columns
- Connect Python to PostgreSQL
- Export cleaned data for SQL analysis

## Business Questions Answered

Examples include:

1. Revenue by gender
2. Revenue by age group
3. Revenue concentration by location
4. Highest-rated products
5. Top-selling products within each category
6. Seasonal demand by product category
7. Customer segmentation (New, Returning, Loyal)
8. Customer value tiering using frequency and spending
9. Repeat buyers vs subscription status
10. Subscriber spending comparison
11. Discount effectiveness

The SQL script demonstrates:

- Common Table Expressions (CTEs)
- Window Functions
- Ranking Functions
- Aggregations
- CASE expressions
- Business KPI calculations

## Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Relational Database Design
- PostgreSQL
- Advanced SQL
- Business Intelligence
- Customer Segmentation
- Revenue Analysis


## 📊 Power BI Dashboard
<img width="1482" height="726" alt="image" src="https://github.com/user-attachments/assets/6649ac56-6621-4ed3-977a-2e6b49bb65cd" />

The project includes an interactive Power BI dashboard (`customer_behavior_analysis.pbix`) for business intelligence and executive reporting.

### Dashboard KPIs
- 👥 Total Customers
- 💰 Average Purchase Amount
- ⭐ Average Review Rating

### Interactive Visualizations
- 🍩 Customer Distribution by Subscription Status (Donut Chart)
- 📈 Revenue by Product Category (Clustered Column Chart)
- 📊 Sales by Product Category (Clustered Column Chart)
- 👥 Revenue by Age Group (Clustered Bar Chart)
- 🛍️ Sales by Age Group (Clustered Bar Chart)

### Interactive Filters (Slicers)
- Product Category
- Shipping Type
- Customer Age

### Business Questions Answered
- Which product categories generate the highest revenue?
- Which categories have the highest sales volume?
- How does customer spending differ across age groups?
- What percentage of customers are subscribed?
- How do shipping preferences affect customer purchasing patterns?
- What are the overall customer count, average purchase amount, and average review rating?

### Dashboard Features
- Executive KPI cards
- Interactive cross-filtering
- Drill-down analysis by demographic segments
- Business-ready visual layout


## Author

Monir Hosen Akash

If you found this project useful, consider giving it a ⭐.
