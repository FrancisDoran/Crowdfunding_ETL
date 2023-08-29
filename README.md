# Crowdfunding_ETL

## Project Overview

This project focuses on the following main tasks:

1. Extract and transform data using Python, Pandas, and regular expressions.
2. Create CSV files based on the transformed data.
3. Generate an Entity-Relationship Diagram (ERD) based on the CSV file data.
4. Define a PostgreSQL table schema using the ERD.
5. Load the CSV file data into a PostgreSQL database.

## Project Structure

The project is organized as follows:

- `ETL_Mini_Project_FDoran.ipynb`: Jupyter Notebook containing the code for data extraction, transformation an to create CSV files from the transformed data.
- `crowdfunding_db_schema.sql`: SQL file containing the table schema based on the ERD.
- `README.md`: The documentation you are currently reading.

## Getting Started

1. Clone this repository to your local machine.
2. Open and run `ETL_Mini_Project_FDoran.ipynb` to perform data extraction and transformation and generate the CSVs.
3. Create a PostgreSQL database and run the `crowdfunding_db_schema.sql` script to set up the table schema.
4. Load CSV data into the database tables using appropriate SQL commands or a Database management tool.
5. Verify data using SELECT statements.

## Dependencies

- Python 3.x
- Pandas
- numpy
- PostgreSQL
- Database management tool of you choice, I used pgAdmin4

## Resources

- QuickDBD: https://www.quickdatabasediagrams.com/
