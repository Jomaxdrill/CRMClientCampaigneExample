# CRM Client Campaign Example
The following project is an example using Angular ,Node JS and JDOBDC to process and store customer data . 
Technologies used: 
Front Angular CLI: 11.2.0
Express+Node.js v14.15.5 
Oracle Database connection. Also, use SQL Developer for database manipulation.
Main comments language: Spanish

Context:
A CSV File contains clients data information. CRM staff wants an application that lets them select the respective information they need  between al the possible available data columns (name,surname,phone,address) and finally store all this information table where one of its columns;campaign_id,references the group of clients uploaded. That's why it is mandatory to check before upload the last campaign_id value to assign a new one for all these new clients at the table. 

- Create a table with the following fields (CRM_USER_CAMPAIGN):
id (primary key)
name
surname
phone
address
campaign_id




