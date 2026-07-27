# PostgreSQL Table Creation Using Python

## Overview

This project demonstrates how to connect a Python application to a PostgreSQL database using the `psycopg2` library. The program establishes a database connection, creates an `employees` table, commits the changes, and closes the database connection.

## Features

* Connects to a PostgreSQL database.
* Uses the `psycopg2` library for database operations.
* Creates an `employees` table.
* Commits changes to the database.
* Closes the database connection properly.

## Table Structure

The program creates a table named `employees` with the following columns:

| Column Name | Data Type |
| ----------- | --------- |
| Name        | TEXT      |
| ID          | INTEGER   |
| Age         | INTEGER   |

## Requirements

* Python 3.x
* PostgreSQL
* psycopg2 library

## Installation

Install the required library using pip:

```bash
pip install psycopg2
```

Alternatively, you can install the binary package:

```bash
pip install psycopg2-binary
```

## Project Structure

```text
PostgreSQL-Table-Creation/
│── create_table.py
└── README.md
```

Replace `create_table.py` with the actual name of your Python file if it is different.

## How to Run

Clone the repository:

```bash
git clone https://github.com/KotapatiDhananjay/Repository-Name.git
```

Navigate to the project directory:

```bash
cd Repository-Name
```

Run the Python program:

```bash
python create_table.py
```

## Expected Output

```text
Table created successfully
```

## Concepts Covered

* Python Database Connectivity
* PostgreSQL
* SQL DDL Commands
* Database Connection Management
* Creating Tables
* Transaction Commit
* Database Cursors

## Note

Before running the program, ensure that:

* PostgreSQL is installed and running.
* The database specified in the connection string exists.
* The username, password, host, and port are correctly configured.
* The `psycopg2` package is installed.

## Author

Kotapati Dhananjay

GitHub: https://github.com/KotapatiDhananjay
