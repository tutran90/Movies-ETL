# **Movies-ETL**

## **Overview**
Purpose of this project was to extract, transform, and load the data a database (pdAdmin). 

Modules used for this analysis: 
- Python libraries: 
    -   pandas
    -   numpy
    -   time
    -   regular expression (re)
    -   SQLAlchemy (used to generate SQL statements)
    -   psycopg2 (PostgresSQL database adapter)

Datasets: 
- wikipedia-movies.json
- movies_metadata.csv
- ratings.csv

## **Results**

The 3 datasets were extracted and then cleaned/transformed. The transformation involved creating 2 functions to parse the data. Finally, the transformed data was merged into one dataframe. The final product was then loaded to PgAdmin where queries could be performed. 
