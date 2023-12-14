# Crowdfunding_ETL
# Project_2 Crowdingfunding 
The project represented by this repository is the second project in the Data Visualization edX Bootcamp affiliated with CWRU. Participants in this project were Steven Anthony and Maddie Haughton.

This project was meant to demonstrate our knowledge of ETL with Python, Pandas, and SQL. Using the starter code provided, we analyzed the data provided in the crowdfunding.xlsx and contacts.xlsx files in the Resources folder. Then we created csv files that can also be found in the Resources folder.

These files were then the basis of our Entity Relationship Diagram, found in erd.png. The text that we entered into the QuickDBD tool can be found in the file schema.txt. After mapping the relationships between the csv files, we created a schema file (with QuickDBD) to make tables in pgAdmin using PostgreSQL. Then we imported the data from the csv files we created to the tables in pgAdmin. The schema file is called crowdfunding_db_schema.sql. To demonstrate that the date was imported into the tables, we created another .sql file with queries that can be found in select_statements.sql.