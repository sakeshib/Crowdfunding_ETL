# crowdfunding_ETL

## Overview
This project aims to build an ETL pipeline to process crowdfunding data. The primary objective is to extract relevant information, transform it into structured DataFrames, and store the data in CSV format for later use. 

## Project Structure
- In the `crowdfunding_ETL`:
    - `ETL_Mini_Project_JLiu.ipynb` - contains the ETL process
    - In the `Resources` folder: 
        - `crowdfunding.xlsx` - contains the raw crowdfunding data
        - `category.csv` - contains unique categories
        - `subcategory.csv` - contains unique subcategories
        - `campaign.csv` - contains campaign details
        - `contacts.xlsx` - contains raw contact info data 
        - `contacts.csv` - contains cleaned up contact information
        - `crowdfunding_db_schema.sql` - contains table schema created from ERD
    - In the `Images` folder:
        - `crowdfunding_db_schema.png` - contains a sketch of ERD diagrams
        - `crowdfunding_table.png` - an image showing the creation of `crowdfunding_db` database and 4 tables
        - `crowdfunding_csv.png` - an image showing each CSV file imported successfully
        - `campaign_sql_table.png` - an image showing data in *campaign* table
        - `contacts_sql_table.png` - an image showing data in *contacts* table
        - `category_sql_table.png` - an image showing data in *category* table
        - `subcategory_sql_table.png` - an image showing data in *subcategory* table

## Technologies Used
- Python
- Pandas
- PostgreSQL
- Jupyter Notebook
- Github

## Resources Used
- Xpert Learning Assistant
- Office Hours



