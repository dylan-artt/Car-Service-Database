# Car Service Database Project

## Overview
This project is a relational database designed to manage the records of a car garage. It stores information about customers, 
their cars, vehicle services, mechanics, and the mechanics assigned to each service. The database uses SQL to create tables, 
establish relationships between them, and insert sample data for testing and querying.

## Tables
The database contains five tables:

CUSTOMER – Stores customer details, including names, email addresses, and phone numbers.
CAR – Stores vehicle details, including registration numbers, make, model, year of manufacture, and owner.
SERVICE – Stores service records, including drop-off dates and times, work descriptions, mileage, and next service dates.
MECHANIC – Stores mechanic details, including names, phone numbers, and grades.
PERFORMS – Links mechanics to the services they work on and records their time for each service.

## How To Use

1. Open a MySQL-compatible database tool. This project was developed in Microsoft SQL Server Management Studio.
2. Open the "SQLScriptsForMechanicService" txt file
3. Execute the scripts to create the tables and populate them with the sample data.
4. If your database tool requires a database to be selected first, create or select one before running the script.
5. if you wish to test the database, SQL scripts have been provided in the repository for use
6. To use them, simply copy any of your choice into a new query

## Extra Notes

- Some fields have been left blank intentionally to represent uncollected info
- The queries are built to be executed after the database has been created and populated with the sample info

## Purpose

The purpose of this project is to demonstrate relational database design, 
primary and foreign keys, SQL data retrieval, joins, and aggregate 
functions using a car garage management scenario.
