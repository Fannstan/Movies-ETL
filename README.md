# Movies-ETL

## Overview
The purpose of this project is to gather movie data from Wikipedia and Kaggle and create an automated pipeline where new data can be taken in, transformed and loaded into existing data tables.  

## Results: 
### Deliverable 1 - ETL_Function_test 
- ETL function was used to read in three data files 
  - Wikipedia data, Kaggle metadata, and MovieLens rating data

### Deliverable 2 - ETL_Clean_wiki_movies 
- The Wikipedia Data was extracted and transformed so that it could later be merged with the Kaggle metadata

### Deliverable 3 - ETL_clean_kaggle_data
- The Kaggle metadata and MovieLens rating data was extracted and transformed.
- The Kaggle metadata DataFrame is merged with the Wikipedia DataFrame 
- The MovieLens rating DataFrame is merged with the movies_df DataFrame

### Deliverable 4 - ETL_create_database
- The movies_df DataFrame is read into the PostgreSQL database 'movies' table
- The MovieLens ratings CSV data is read into the PostgreSQL database 'ratings' table
