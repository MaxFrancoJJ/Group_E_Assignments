This folder contains some files to allow us to create the MYSQL DB Schmea and tables based on the MySQL model file we delivered in the previous campaign data assignment.  (the first group assignment)

Instructions: 
Run the scripts in this order:

01_Create_CampaignSchema.sql
02_Campaign_Dump_16052019.sql

**You will get some warnings similar to the below which are to do with the UTF8 encoding - you can ignore these errors and proceed:**

14:24:51	CREATE SCHEMA IF NOT EXISTS `campaign` DEFAULT CHARACTER SET utf8	1 row(s) affected, 1 warning(s): 3719 'utf8' is currently an alias for the character set UTF8MB3, but will be an alias for UTF8MB4 in a future release. Please consider using UTF8MB4 in order to be unambiguous.	0.015 sec

After you have run the above, you will then have a schema containging the 5 Tables:
* d_date
* d_product
* d_shopping_centre
* f_sales_marketing
* f_visits

You will need to refresh your lists of schemasin order to see tihs new schema called **campaign**
