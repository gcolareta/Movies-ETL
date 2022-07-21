# Movies-ETL

## Purpose
The purpose of this project is to create a clean dataset to be used for analysis.
In this projects I have extracted data from Wikipedia and Kaggle, transformed it into one clean dataset and load it into a SQL table.

### Deliverable 1
Part one consists of writing a function to extract and read the three data files that were provided:
- wikipedia_movies.json
- movies_metadata.csv
- ratings.csv

### Deliverable 2
In part two, more code is added to the function to clean the wikipedia_movies.json. In this process, null values are removed, and data types from 'Box office', 'Budget', 'Release date' and 'Running time' columns are converted from objects to their corresponding type so that data can be manipulated and analyzed.

### Deliverable 3
In part three, more code is added to the function to clean the movies_metadata.csv file and merge it with the wikipedia file. In this process, movies are merged using the IMBd ID, duplicates are removed and only relevant columns are included in the merged dataframe. 

### Deliverable 4
In part four, the ratings.csv file is cleaned and oly relevant data is extracted and transformed into a clean dataframe. Also, the merged movies_df DataFrame and cleaned rating CSV data were added to a SQL database.
