# 💳 Credit Card Financial Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing credit card transactions and customer behavior using *SQL* and *Microsoft Power BI*. The goal is to transform raw credit card and customer datasets into meaningful business insights through data cleaning, database management, and interactive dashboards.

![Project Overview](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Media%20FIle/credit_card_full_dash_gif.gif)

The project provides insights into:

- Revenue and transaction performance
- Customer demographics and spending behavior
- Card category analysis
- Customer occupation and income analysis
- Expenditure patterns
- Transaction trends over time
- Delinquent account analysis
- Card activation performance

**Here is the full report of the project: 	[Project Report](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Credit%20Card%20Financial%20Analysis%20Project%20Report.pdf)**

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| SQL (PostgreSQL) | Database creation, table design, and data import |
| Microsoft Power BI | Dashboard development and visualization |
| CSV Dataset | Source data |
| Data Analytics | Business insights generation |


## 📂 Project Structure
- [x] Raw CSV Data
- [x] SQL Database Creation
- [x] Data Import & Storage
- [x] Power BI Data Modeling
- [x] Dashboard Development
- [x] Business Insights

# 🗄️ Database Design

The SQL workflow creates a database named:
### ccdb

Two main tables are created:

## 1. Credit Card Transaction Table (cc_detail)

This table stores transaction-level information including:

- Card category
- Annual fees
- Credit limit
- Transaction amount
- Transaction count
- Revolving balance
- Utilization ratio
- Expenditure type
- Interest earned
- Delinquent account status

## 2. Customer Information Table (cust_detail)

This table contains customer demographic and financial information:

- Age
- Gender
- Education level
- Marital status
- Occupation
- Income
- Location
- Customer satisfaction score

The SQL script also imports additional transaction and customer records from CSV files into the database. Here is the complete SQL query   **[SQL FIle](https://https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/credit_card_financial_analysis.sql).**


# 📊 Power BI Dashboard

The dashboard consists of three major analytical sections:

## 1. Credit Card Transaction Report

![credit card dash](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Media%20FIle/credit_card_dash_gif.gif)

Key KPIs:

- Total Revenue: *57M*
- Total Transaction Amount: *46M*
- Total Interest Earned: *8M*
- Transaction Count: *667K*

The dashboard analyzes:

### Revenue by Card Category

| Card Type | Revenue |
|-----------|---------|
| Blue | 47M |
| Silver | 6M |
| Gold | 3M |
| Platinum | 1M |

### Revenue by Card Usage

- Swipe: 36M
- Chip: 17M
- Online: 4M


### Revenue by Expenditure Type

Major spending categories include:

- Bills
- Entertainment
- Fuel
- Grocery
- Food
- Travel


### Quarterly Performance

Revenue and transaction volume are compared across Q1-Q4 to identify seasonal trends.




# 👥 Customer Analysis Dashboard

![customer dash](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Media%20FIle/customer_dash_gif.gif)

The customer dashboard analyzes customer characteristics and their contribution to revenue.

Key KPIs:

- Total Revenue: *57M*
- Total Transactions: *46M*
- Median Income: *45K*
- Customer Satisfaction Score: *3.2*


## Customer Insights

![Insights Dash](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Media%20FIle/insight_dash_gif.gif)

### Revenue by Occupation

Highest contributing customer groups:

- Businessman
- White-collar professionals
- Self-employed customers
- Government employees


### Revenue by Education Level

Customer revenue distribution is analyzed across:

- Graduate
- High School
- Unknown
- Uneducated
- Post-Graduate
- Doctorate


### Demographic Analysis

The dashboard includes:

- Age group analysis
- Gender-based revenue comparison
- Marital status analysis
- Income group analysis
- State-wise revenue distribution





# 📈 Additional Business Analysis

The dashboard also includes:

## Weekly Revenue Growth Analysis

Tracks:

- Previous week revenue
- Current week revenue
- Week-over-week revenue percentage change


## Transaction Trend Analysis

Visualizes transaction count changes throughout the year.


## Customer Risk Analysis

Analyzes:

- Delinquent account percentage
- Delinquency by occupation
- Card activation percentage


Example findings:

- Approximately 93.9% accounts are non-delinquent
- Approximately 6.0% accounts are delinquent
- Around 57.46% cards are activated within 30 days

# 🎯 Project Objectives

- Build a structured database for credit card analytics
- Analyze customer spending patterns
- Identify revenue-driving customer segments
- Understand card usage behavior
- Monitor transaction trends
- Provide interactive business intelligence dashboards


# 🚀 Key Skills Demonstrated

- SQL Database Management
- Data Import and Transformation
- Data Modeling
- Power BI Dashboard Development
- Business Analytics
- Data Visualization
- KPI Reporting


# 📌 Future Improvements

Possible enhancements:

- Add predictive models for customer churn prediction
- Develop credit risk scoring models
- Automate data refresh pipelines
- Integrate Python-based exploratory analysis
- Add machine learning-based customer segmentation

Here is a presentation of the full project 	[Project Presentation](https://github.com/maidulhassan-collab/Credit-Card-Financial-Analysis-Dashboard/blob/main/Credit_Card_Financial_Analysis_Presentation.pptx)


# 👨‍💻 Author

*Maidul Hassan Shanto*

Data Analytics | SQL | Power BI | Business Intelligence


