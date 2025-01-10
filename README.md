# Online-Shopping-DB-System
## Project Overview
This project is designed to simulate a database system for an online shopping platform. It includes comprehensive database structures, procedures, and triggers to manage products, orders, reviews, recommendations, and customer data.

## Technologies Used
- Oracle SQL  
- PL/SQL

## Project Structure
- schema → Scripts for creating and dropping tables.  
- procedures → Stored procedures and functions.  
- anonymous_block.sql → Block for inserting sample data and executing procedures.  

## How to Run
1. Setup Database:  
   - Execute `drop_tables.sql` to clear existing tables.  
   - Run `create_tables.sql` to create fresh tables.  
   - Execute `sequences.sql` for auto-increment IDs.

2. Load Procedures: 
   - Run all `.sql` files in the `procedures/` folder individually.

3. Insert Data & Test:  
   - Run `anonymous_block.sql` to populate data and test procedures.

4. Verify: 
   - Use `SELECT` statements to check table data.

