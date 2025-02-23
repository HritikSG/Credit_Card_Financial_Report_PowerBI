# Credit Card Financial Dashboard

## Overview

This project involves creating a **Power BI Weekly Dashboard** for **Credit Card Financial Data**. The dashboard provides insights into customer transactions, revenue trends, and demographic-based spending patterns. The data is sourced from a **pgAdmin SQL Database**, transformed using **DAX queries**, and visualized in **Power BI**.

## Features

- **Data Import and Processing**:
  - Prepared CSV files containing credit card financial data.
  - Created tables in **pgAdmin SQL Database** and imported CSV files into SQL.

- **Database Connectivity**:
  - Established a connection between **pgAdmin** and **Power BI**.

- **Data Modeling and Transformation**:
  - Performed **DAX queries** to generate additional columns, such as:
    - **Age Group**
    - **Income Group**
    - **Revenue Metrics**
    - **Current Week Revenue**
    - **Previous Week Revenue**
    - **Week-over-Week Revenue (WoW Revenue)**

- **Dashboard Design**:
  - Developed **two Power BI dashboards**:
    1. **Credit Card Transaction Dashboard**
    2. **Credit Card Customer Dashboard**

- **Automated Updates**:
  - The dashboards update dynamically as new data is inserted into the **pgAdmin SQL Database**.

## Reports

The following Power BI reports are included in this project:

1. **Credit Card Customer Report** 
2. **Credit Card Transaction Report**

## Dataset

The project includes **four CSV files** containing raw data. These files were processed and loaded into **pgAdmin SQL Database** before visualization in **Power BI**.

## SQL Queries

All **SQL queries** used for data preparation are provided in a text file on **GitHub**. These queries cover data cleaning, transformations, and table creation.

## How to Use

1. **Set Up the Database**:
   - Create a PostgreSQL database in **pgAdmin**.
   - Run the provided SQL scripts to create and populate tables.

2. **Connect Power BI to pgAdmin**:
   - Use **PostgreSQL connector** in Power BI to fetch data from the database.

3. **Run DAX Queries**:
   - Execute **DAX formulas** in Power BI to create calculated columns.

4. **Refresh the Dashboard**:
   - Update the dataset in **pgAdmin** to see real-time changes in Power BI.

## Dependencies

- **pgAdmin (PostgreSQL Database)**
- **Power BI Desktop**
- **DAX Queries**

## Contributing

Contributions are welcome! Please create a **pull request** for any improvements or bug fixes.

contact: hritik@umich.edu
