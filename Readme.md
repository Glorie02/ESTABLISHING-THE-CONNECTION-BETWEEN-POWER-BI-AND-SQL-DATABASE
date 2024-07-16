# Establishing the Connection Between Power BI and SQL Database

## Overview

This repository provides step-by-step instructions and resources for connecting Power BI to a SQL database. It includes configuration details, necessary prerequisites, and best practices to ensure a seamless integration for data analysis and visualization.

## Connecting Power BI to a CSV File

1. **Launch Power BI**: Open the Power BI app and click on **Get Data** on the Home page.
2. **Load CSV Data**: Select **CSV/file** and insert the "Bank Term Deposit Subscription" CSV data.
3. **Data Preview**: When the data preview page appears, change the Data Type detection to **Based on entire dataset** and click **Load**. The data will then be loaded.

## Connecting Power BI to a SQL Database

1. **Load Data into SQL**: First, load the table into SQL. Write a query to return only the top 25 rows from the data.
2. **Get Data from SQL Server**: Click on the **Get Data** button and select **SQL Server database** from the dropdown menu.
3. **Fill Connection Details**: Enter the Server name and Database name. For Data connectivity mode, select **Import**.
4. **Advanced Options**: Optionally, in the advanced options, write your SQL query to return only the necessary data for analysis and click **OK**.
5. **Preview Data**: Once the preview loads, verify the information to ensure it's correct, then click **Load**.
6. **Clean Data**: After the data is loaded, switch to the Table view to begin the data cleaning process.

## Best Practices

- Ensure all necessary prerequisites are met before starting the connection process.
- Verify data accuracy at each step to avoid issues during analysis.
- Follow the step-by-step instructions carefully to ensure seamless integration.
