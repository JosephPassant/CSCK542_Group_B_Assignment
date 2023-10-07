# CSCK542_Group_B_Assignment

## Project Description
This project develops APIs that allows users to create, read, update, and delete (CRUD) data from a college course administration database.

The application is built using Node.js and Express. 

The database is built using MySQL and MySQL Workbench based on the provided files in the SQL Database Folder. 

API requests and testing can be undertaken using the Postman application and the provided Postman collection.

To run the project the files should be downloaded to a local directory.

## Database Installation
The database can be installed using the provided SQL Dump Database files.

To create the database open MySQL Workbench and create and connect to a new database called 'mydb' using the following command:
```
CREATE DATABASE mydb;
USE mydb;
```
In MySQL workbench, select the 'Server' tab and select 'Data Import'. 

Select the 'Import from Dump Project Folder' option and then 'Load Folder Contents'. Select the 'mydb' database object and then 'Start Import'.

This will create the database schema.

## Application Installation
To launch the application, open a terminal window and navigate to the directory where the mydb_app.js file is located (NodeJS App Files Foler).

run the following command
```
node mydb_app.js
```
This should launch the application and display the following message:
```
Server running on http://localhost:3000
Connected to the database
```

## Postman Collection Installation
To test the files open the Postman application and select the 'Import' option from the file menu and and select the CSCK_Group_B.postman_collection.json file from the Postman Collection Folder.

This collection contains API calls for each of the functional requirements of the project and tests to ensure valid and invalid inputs produce the expected responses.

Different input values can be passed to the API calls by selecting the 'Body' tab and selecting the 'raw' option. The input values can then be updated in JSON format maintaining the property labels.

## Team Members
Miguel Angel Lopez Lago\
Tsz Ting Shum\
Ryutaro Inoue\
Joseph Passant


