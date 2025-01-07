# Crowdfunding_ETL
Project 2

Data manipulation and conversion to CSV's is located in ETL_Mini_Project_WPlaisance.ipynb
The output CSV files are located in the Resources folder.

The DB schema creation code is saved as crowdfunding_db_schema.sql

To set up DB:
In pgadmin create a new DB named crowdfunding_db
Open the sql file crowdfunding_db_schema.sql

Import the CSV's in the following order:
category.csv, subcategory.csv, contacts.cvs, campaign.csv

Run the following code to verify:
SELECT * FROM public."Campaign" ORDER BY cf_id ASC 

