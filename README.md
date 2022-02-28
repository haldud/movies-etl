# Movies ETL
Extract, transform, and load movies data.

## Overview
In this module, we have been practicing extracting data from a source, transforming it in Python, and loading the data into a database.

The data was sourced from multiple sources such as Wikipedia and Kaggle (metadata and ratings).

We worked on cleaning and merging data.

We finally loaded the clean data into a PostgreSQL database.

## Files
### Resources
1. [Metadata](Resources/movies_metadata.csv)
2. [Wikipedia](Resources/wikipedia_movies.json)
3. Ratings file not included due to large size, but can be downloaded from Kaggle

### Code
1. Module practice Interactive Python Notebook [file](movies_etl.ipynb).
2. Challenge Interactive Python Notebook files:
   - [Clean Kaggle Data](ETL_clean_kaggle_data.ipynb)
   - [Clean Wiki Movies](ETL_clean_wiki_movies.ipynb)
   - [Create Database](ETL_create_database.ipynb)
   - [Function Test](ETL_function_test.ipynb)

## Results
1. Database movies [query](Resources/movies_query.png) showing number of records in movies table.
2. Database movies [query](Resources/ratings_query.png) showing number of records in ratings table.
