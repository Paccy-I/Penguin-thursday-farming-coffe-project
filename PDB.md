# Penguin Farming Coffee Project - Database Implementation

## Project Overview

The **Penguin Farming Coffee Project** is a system designed to manage the operations of a coffee farming cooperative. This project involves the creation of a relational database to handle data related to farmers, cooperatives, farm records, sales transactions, and buyer details. The database is implemented in **Oracle** and includes tables to manage and query coffee farming-related data.

## Version

- **Database Version**: Oracle 21c Express Edition
- **SQL*Plus Version**: 21.0.0.0.0
- **Database Container Name**: `thur_penguin_farmingcoffeproject`

## Database Structure

The database schema includes the following tables:

### 1. Farmers Table
Stores information about farmers:
```sql
CREATE TABLE farmers (
  Farmer_ID INT PRIMARY KEY,
  Farmer_Name VARCHAR2(100),
  District VARCHAR2(100),
  Sector VARCHAR2(100),
  Plot_Name VARCHAR2(100),
  Plot_ID INT
);

