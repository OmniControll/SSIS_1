**Snowflake ETL Pipeline** is a Python script with the process of extracting data, transforming it, and loading it into a Snowflake data warehouse.
This project uses Pandas for data manipulation, SQLAlchemy for database interactions, and dotenv for secure management of environment variables.
It ensures a secure, efficient, and automated data integration workflow, making it easier to manage and analyze large datasets.

## Features

- *Extract* Gathers data from predefined sources and structures it into a Pandas DataFrame
- *Transform* Cleans and transforms the extracted data by removing duplicates and handling missing values
- *Load* Inserts the transformed data into Snowflake, with dynamic creation of databases and tables if they don't exist

## Automatically creates the target database and table schema in Snowflake.
## environment variables to manage Snowflake credentials .
## Implements logging to monitor the ETL process and capture errors .
## error handling to manage and log SQLAlchemy and general exceptions. 

## Prerequisites

Before setting up the project, ensure you have the following installed:

- **Python 3.6+**: [Download Python](https://www.python.org/downloads/)
- **pip**: Python package installer (comes with Python)
- **Snowflake Account**: Set up a Snowflake account. [Sign Up for Snowflake](https://signup.snowflake.com/)
