# Crowdfunding Database Project

## Overview

This project involves creating a PostgreSQL database for a crowdfunding platform using data from four CSV files. The tasks include inspecting the CSV files, creating an ERD (Entity-Relationship Diagram), defining the database schema, creating the database and tables, importing data, and verifying the data.

## Project Files

- **campaign.csv**: Data related to crowdfunding campaigns.
- **category.csv**: Data related to categories of campaigns.
- **contacts.csv**: Contact information for campaign owners.
- **subcategory.csv**: Data related to subcategories of campaigns.
- **crowdfunding_db_schema.sql**: SQL file containing the schema for the database.

## Steps to Complete the Project

### Part 1: Data Preprocessing

1. **Merge and Clean Data**
   - Load the data from the CSV files into DataFrames.
   - Merge DataFrames to create a master DataFrame.
   - Clean the data by handling missing values, formatting columns, and standardizing data types.

2. **Analyze and Explore Data**
   - Perform exploratory data analysis (EDA) to understand the data.
   - Generate summary statistics and visualizations to identify trends and patterns.

### Part 2: Category and Subcategory Data

1. **Create a Category DataFrame**
   - Extract and organize unique categories from the master DataFrame.
   - Create a new DataFrame for categories with appropriate columns and data types.

2. **Create a Subcategory DataFrame**
   - Extract and organize unique subcategories from the master DataFrame.
   - Create a new DataFrame for subcategories with appropriate columns and data types.

3. **Save DataFrames to CSV Files**
   - Save the cleaned and organized category and subcategory DataFrames to new CSV files.

### Part 3: Campaign DataFrame

1. **Create a Campaign DataFrame**
   - Extract relevant columns for campaigns from the master DataFrame.
   - Organize and format the data in the Campaign DataFrame.

2. **Save the Campaign DataFrame to CSV**
   - Save the Campaign DataFrame to a new CSV file.

### Part 4: Creating the Database

1. **Inspect the CSV Files and Sketch an ERD**
   - Inspect the provided CSV files.
   - Create an ERD using QuickDBD to visualize the database structure.

2. **Create a Table Schema Based on the ERD**
   - Use the information from the ERD to create a table schema for each CSV file.
   - Specify data types, primary keys, foreign keys, and other constraints.

3. **Save the Database Schema as a Postgres File**
   - Save the SQL schema as `crowdfunding_db_schema.sql`.

4. **Create a New Postgres Database**
   - Create a new PostgreSQL database named `crowdfunding_db`.

5. **Create Tables Using the Database Schema**
   - Run the `crowdfunding_db_schema.sql` file to create the tables in the database.

6. **Verify Table Creation**
   - Verify that the tables have been created successfully by running SELECT statements for each table.

7. **Import Each CSV File into the Corresponding SQL Table**
   - Import data from each CSV file into the corresponding tables.

8. **Verify That Each Table Has the Correct Data**
   - Run SELECT statements to verify that the data has been imported correctly into each table.
  
9. **Credits**
   - Miguel Gomez
   - Santiago Cortes

## Conclusion

This project demonstrates the creation of a PostgreSQL database for a crowdfunding platform using provided CSV files. The steps include inspecting the data, creating an ERD, defining the database schema, creating the database and tables, importing the data, and verifying the data.
