This repository demonstrates how to connect and interact with a PostgreSQL database using Python within Jupyter notebooks. The workflow is divided into two parts — one focusing on database and table creation, and the other on data ingestion using CSV files and pandas.

📁 Repository Contents
modelling.ipynb
In this notebook, we establish a connection to PostgreSQL using the psycopg2 library. The notebook walks through:

Connecting to a PostgreSQL server

Creating a new database

Creating tables within that database using SQL queries

Basic transaction execution

modelling_2.ipynb
This notebook builds upon the first one. It includes:

Creating a new PostgreSQL database and new tables

Reading data from local CSV files using the pandas library

Inserting the data into the PostgreSQL database using psycopg2 and pandas

🧰 Technologies Used
Python 3.x

Jupyter Notebook

psycopg2 – PostgreSQL adapter for Python

pandas – Data analysis and CSV reading

PostgreSQL – Relational database system
