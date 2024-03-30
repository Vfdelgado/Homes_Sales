# Home Sales Analysis with PySpark

This project involves analyzing home sales data using PySpark, a Python library for working with big data processing. The dataset used in this project is provided in home_sales_revised.csv.

## Project Overview
### Steps

Importing PySpark SQL Functions: Import necessary PySpark SQL functions for data analysis.

Reading Data: Read the home sales data from home_sales_revised.csv into a Spark DataFrame.
<img width="879" alt="Screenshot 2024-03-29 at 10 43 53 PM" src="https://github.com/Vfdelgado/Homes_Sales/assets/146504714/d41eeb0d-d966-4655-8824-303c4b9ab4cb">

Creating Temporary Table: Create a temporary table called home_sales to perform SQL queries.

Answering Questions: Use SparkSQL queries to answer specific questions about the home sales data, such as calculating average prices and filtering based on certain criteria.

Caching Data: Cache the home_sales temporary table to improve query performance.

Checking Cache: Check if the home_sales temporary table is cached to ensure caching was successful.

Running Queries with Cached Data: Execute queries using the cached data and compare the runtime to uncached runtime to evaluate performance improvements.

Partitioning Data and Creating Temporary Table for Parquet Data: Partition the data by the "date_built" field and create a temporary table for the Parquet data.

Running Queries on Parquet Data: Execute queries on the Parquet data and compare the runtime to uncached runtime to assess performance.

Uncaching Data: Uncache the home_sales temporary table to release memory resources.


## Conclusion
This project demonstrates how to perform data analysis on large datasets using PySpark. By leveraging the capabilities of PySpark and SparkSQL, we were able to efficiently analyze the home sales data and derive valuable insights.

### Resources
Study session with fellow cohorts, past class activities, online resources.
