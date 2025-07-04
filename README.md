## -Kultra-Mega-Stores-Inventory-Analysis
Kultra Mega Stores Inventory Analysis using Structured Query Language 

## Kultra Mega Stores Inventory Case Study - SQL Solution

## This repository contains the SQL queries designed to address the "Kultra Mega Stores Inventory" case study. The queries analyze sales and order data from 2009 to 2012 to provide key business insights for the Abuja division of KMS.

##  Data Sources

The analysis is based on data from the following two files, treated as SQL tables in a Database Management System (DBMS), specifically SQL Server given the TOP and [dbo].[] syntax:

    KMS Sql Case Study.csv (mapped to SQL table: [dbo].[KMS Sql Case Study])

    Order_Status.csv (mapped to SQL table: [dbo].[Order_Status])

## Case Study Answers

## The SQL solution addresses two main case scenarios:
## Case Scenario I

    Which product category had the highest sales?
    Answer: Technology 
    
    What are the Top 3 and Bottom 3 regions in terms of sales?
    Answer: Top 3 regions (West, Ontario, Praire)  
            Bottom 3 Regions (Yukon, Northwest Territories, Nunavut)

    What were the total sales of appliances in Ontario?
    Answer: There was no sale of any appliance in Ontario

    Advise the management of KMS on what to do to increase the revenue from the bottom 10 customers.
    Answer: a) Targeted marketing campaigns that Offer personalized promotions, discounts, or loyalty programs specifically designed to re-engage these customers
            b) Conduct surveys or direct outreach to understand their needs, preferences, and reasons for low purchasing activity 
            c) Ensure these customers receive excellent support to resolve any past issues and encourage future interactions
            d) Incentivize Repeat Purchases
    
    KMS incurred the most shipping cost using which shipping method?
    Answer: Delivery Truck
## Case Scenario II

    Who are the most valuable customers, and what products or services do they typically purchase?
    Answer: Top 5 Customers (Emily Phan, Deborah Brumfield, Roy Skaria, Sylvia Foulston, Grant Carroll)
            Services they typically purchase (Furniture, Office Supplies, and Technology)

    Which small business customer had the highest sales?
    Answer: Dennis Kane

    Which Corporate Customer placed the most number of orders in 2009 – 2012?
    Answer: Adam Hart

    Which consumer customer was the most profitable one?
    Answer: Emily Phan

    Which customers returned items, and what segment do they belong to?
    Answer:


## How to Use the SQL Solution

    Database Setup: Ensure you have a SQL Server database set up.

    Data Import: Import the data from KMS Sql Case Study.csv and Order_Status.csv into your database. Make sure the tables are named [dbo].[KMS Sql Case Study] and [dbo].[Order_Status] respectively, and that column
    names match those in the CSV files (including spaces, requiring square brackets in queries).

    Execute Queries: Open the KMS SQL CASE STUDY SOLUTION.sql file in your SQL Server management studio or preferred SQL client.

    Run Each Query: Execute each query individually or in batches to get the results for each question.

        Question 6 Note: For the second part of Question 6, you will need to run the first sub-query to identify the top 5 customer names, then manually insert those names into the IN clause of the second sub-query.

        Question 11 Note: The SQL file includes queries to extract the necessary data for analysis, followed by a detailed explanation within SQL comments on how to interpret the results and draw a conclusion.

## Key Insights (Based on Data Analysis)

The SQL queries provide insights into sales performance, regional contributions, customer behavior, and shipping cost efficiency. Notably, the analysis for Question 11 reveals a potential misalignment in shipping cost expenditure compared to the initial assumptions about shipping method costs, suggesting areas for optimization.

This README provides a comprehensive overview of the SQL solution, guiding users through its purpose, data sources, questions addressed, and how to utilize the provided SQL script.

## Author Notes

This project is part of my personal data analysis portfolio, built to demonstrate SQL proficiency.
---

## Contact

If you have any feedback, suggestions, or collaboration interests, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/adeiye-akande-29426147/) or leave a message via GitHub.


