# RFM Analysis (Segmented Customer)

This project contains a set of queries that can be used to analyze customer data using RFM analysis. RFM analysis is a customer segmentation technique that classifies customers based on their Recency, Frequency, and Monetary value.

## Queries
The following is a list of the queries that are included in this project:

* **Check Unique Values**
    * This query will return a list of all unique values in the `sales_data_sample` table.
* **Analysis Revenue**
    * This query will return a table that shows the revenue generated by each product line, year, deal size, and territory.
* **What is the Best Month for Sales in a Specific Year? How Much Was Earned That Month?**
    * This query will return a table that shows the best month for sales in a specific year, as well as the amount of revenue that was earned that month.
* **November Seems to be the Month, What Product They Sell in November?**
    * This query will return a table that shows the products that were sold in November, as well as the amount of revenue that was generated from those sales.
* **Who is Our Best Customer (RFM Analysis)**
    * This query will return a table that shows the top customers based on their RFM scores.
* **RFM Analysis**
    * This query will perform RFM analysis on the customer data and return a table that shows the customer segments.
* **What Product Are Most Often Sales Together**
    * This query will return a table that shows the product codes that are most often sold together.

## How to Use
To use the queries in this project, you will need to have a database with the `sales_data_sample` table loaded into it. Once you have the database loaded, you can use the following steps to run the queries:

1. Open a terminal window and navigate to the directory where the queries are located.
2. Run the following command to create a database connection:
mysql -u <username> -p <database_name>
```

3. Once you are connected to the database, you can run the queries by typing the following command:

```
mysql <query_file>

For example, to run the query that returns the top customers based on their RFM scores, you would type the following command:


mysql rfm_analysis.sql


## Notes
The queries in this project are designed to be used with a specific database schema. If you are using a different database schema, you may need to modify the queries to make them work.
