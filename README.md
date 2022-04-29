# Ibotta
Ibotta Analytics Engineering Take Home Project
=========
Files :
db_utils.py - This file contains all the functions that are used to process and load files, execute queries to insert and update data in target tables. Answers to Part 1.
main.py - This is the main file that needs to be executed to invoke the required functions to load the csv files and execute database queries. Answers to Part 1.
ibotta.db - Database with the populated tables.
SQL Queries - SQL queries for answers to Part 2.
DDL_Tables - DDL to create tables.
Before_update.png - Data before the Part 3 step.
After_update.png - Data after updating the customer_offer_redemptions table in Part 3.


Execution :
Execute main.py file. Below are the user inputs to be provided to main.py file:
Step 1 - Do you want to load files to the tables (yes/<Enter>)? :
	"yes" - To load the file to tables. Provide the file path, filename and target table name.
	<Enter> - To skip this step.
Step 2 - Do you want to insert/update the customer_offer_redemptions_update.csv file  (yes/<Enter>)? :
	"yes" - To process the file customer_offer_redemptions_update.csv. This step inserts or updates to the customer_offer_redemptions table.
	<Enter> - To skip this step.

