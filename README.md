# Task 5: Working-with-SQL-Joins

## Overview
This project focuses on practicing various SQL JOINs to combine data from multiple related tables. Where I simply have created two tables — `Customers` and `Orders` — and applied different types of JOINs ('INNER', 'LEFT', 'RIGHT', 'FULL' or 'UNION') to understand how they work in different scenarios.

## What I Did:
1. Designed and created two related tables: `Customers` and `Orders`
2. Inserted sample data
3. Practiced all types of JOINs using MySQL Workbench
4. Wrote queries to retrieve combined and unmatched data
5. Observed how JOINs behave when data doesn’t match across tables

## SQL JOIN Used:
1. INNER JOIN- Returns only the records that have matching values in both tables.
2. LEFT JOIN- Returns all records from the **left** table (Customers), and matched ones from the right (Orders); unmatched ones from right show as NULL
3. RIGHT JOIN- Returns all records from the **right** table (Orders), and matched ones from the left (Customers); unmatched ones from left show as NULL
4. FULL JOIN- Returns all records when there is a match in either left or right table; unmatched rows from both sides show as NULL (simulated using `UNION` in MySQL)

## Tables Used- 
1. Customers Table (CustomerID, Name, City)
2. Orders Table (ID, CustomerID, Date, Amt)

## For the detailed script of all the 4 joins, please refer the the attached SQL scrip file
