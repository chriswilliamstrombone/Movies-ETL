# Movies-ETL

## Purpose

This repository for Amazing Prime created a pipline to do the following:

    - Extract data from two different sources.
        - web scrape of Wikipedia website for all movies released since 1990
        - data from Kaggle website for rating data.
    - Transform data using Jupyter Notebook, Python, Pandas and Python RegEx module.
    - Load data using PostgreSQL and pgAdmin to host final cleaned data set.


## Contents 

  1. ETL_function_test.ipynb
  2. ETL_clean_wiki_movies.ipynb
  3. ELT_clean_kaggle_date.ipynb
  4. ETL_create_database.ipynb

## Resources

Data Sources:

    - Wikipedia web scrape JSON file
    - Kaggle data from Kaggle.com - two files: movies_metadata.csv and ratings.csv

Enviroment:

    - Python 3.10

Dependencies:

    Please see Jupyter Notebook ETL_create_database.ipynb for complete list of dependencies

Software:

    Jupyter Notebook
    PostgreSQL and PgAdmin
