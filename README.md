# Employee Management System

## Overview
This project is a **Python-based Employee Management System** that interacts with a MySQL database. It provides a **menu-driven interface** to perform various CRUD (Create, Read, Update, Delete) operations on an employee database.

## Features
- **Database Management**
  - Create and display databases.
  - Create and list tables.
- **Employee Records Management**
  - Insert, update, delete, and search employee records.
  - Display all employee records in a formatted table.
- **User-Friendly Menu**
  - Allows selection of actions using an intuitive menu system.
  - Ensures smooth interaction with the database.

## Prerequisites
- Python 3.x
- MySQL Server
- MySQL Connector for Python (`mysql-connector-python` package)

## Installation
1. **Install MySQL Connector**
   ```sh
   pip install mysql-connector-python
   ```
2. **Set Up MySQL Database**
   - Ensure MySQL is installed and running.
   - Update the MySQL credentials in the script (`host`, `user`, `password`).

## How to Run
1. **Execute the Python Script**
   ```sh
   python employee_management.py
   ```
2. **Follow the on-screen menu options** to perform operations.

## Database Structure
- **Database Name:** `employee`
- **Table Name:** `emp`
- **Columns:**
  - `id` (Integer, Primary Key)
  - `ename` (VARCHAR(15))
  - `salary` (FLOAT)

## Usage Instructions
- Run the script and select from the menu options:
  - `1`: Create Database
  - `2`: Show Databases
  - `3`: Create Table
  - `4`: Show Tables
  - `5`: Insert Record
  - `6`: Update Record
  - `7`: Delete Record
  - `8`: Search Record
  - `9`: Display Records

## Error Handling
- Ensures **database connection success** before performing operations.
- Validates **user input** to prevent incorrect queries.

## Future Enhancements
- Implement **GUI using Tkinter or PyQt**.
- Add **role-based authentication**.
- Export employee data to **CSV or Excel.

## Author
Developed by Shaurya Jain

