# E-commerce-Data-Analytics-using-SQL-and-Python
This project explores an e-commerce dataset using SQL and Python to perform various analytical queries and derive insights. The dataset includes information about customers, orders, payments, products, sellers, and geolocation data. The project aims to analyze key business metrics, customer trends, and order patterns.

## Dataset Source
The dataset used in this project is obtained from Kaggle:

Target Dataset - Kaggle

Since the dataset is large, it is not included in this repository, and users must download it from the provided link.

## Technologies Used
Python (Pandas, Matplotlib, Seaborn, MySQL Connector)

SQL (MySQL for data storage and querying)

Jupyter Notebook (for interactive analysis)


## Dataset Description
The dataset consists of multiple CSV files, which are loaded into a MySQL database. 
### The key tables include:
customers.csv - Customer details

orders.csv - Order history

order_items.csv - Products ordered in each order

payments.csv - Payment details

products.csv - Product catalog

sellers.csv - Seller details

geolocation.csv - Geographical mapping of customers and sellers


## Data Processing Steps
### 1] Data Ingestion
the data 
CSV files are read using Pandas and stored in MySQL.

Data types are mapped properly (INT, FLOAT, TEXT, etc.).

NULL values are handled for missing data.


### 2] Database Creation and Table Structure
The database is structured into relational tables.

Primary keys and foreign keys are defined where needed.

### 3] Data Analysis Queries
The following key business questions are answered using SQL queries:

List all unique cities where customers are located.

Count the number of orders placed in 2017.

Find the total sales per category.

Calculate the percentage of installment payments.

Count the number of customers per state.

### 4] Visualization and Insights

SQL query results are imported into Python for visualization.

Matplotlib and Seaborn are used to create bar charts, pie charts, and heatmaps for data interpretation.

## Setup Instructions
### 1] Install dependencies:
pip install pandas mysql-connector-python matplotlib seaborn

### 2] Set up MySQL database and import CSV data using the script csv-to-sql.ipynb .

### 3] Run Jupyter Notebook for analysis and visualization python+sql_ecommerce.ipynb .

## Insights Derived
Most customers are concentrated in a few major cities.

The majority of orders were placed in 2017.

Installment payments make up a significant percentage of transactions.

Certain product categories dominate in terms of revenue.
