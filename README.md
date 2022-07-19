# Movies ETL

## Overview
An automated system was created that will take in data from Wikipedia, Kaggle, and MovieLens ratings and update it regularly into a table in a PostgreSQL database as requested by Amazing Prime. This regularly updated data will help Amazing Prime's investment in movies.

### Results
A table showing the movie data was created, shown below:

<p align="center">
    <img
         src=Resources/movies_query.png
         >
    </p>

A table showing the ratings data was created, shown below:

<p align="center">
    <img
         src=Resources/ratings_query.png
         >
    </p>
    
    
## Summary
     - Two .csv files and one JSON file were cleaned, extracted, transformed, joined, and then loaded into a database.
     - It is recommended that Amazing Prime utilizes this database to make further decisions regarding investments in movies. 
     - This data helps visualize what low-budget films will become popular, which is what Amazing Prime is looking for.
