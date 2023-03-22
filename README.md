# Cleaning-and-Preparing-IMDB-Data

## Introduction:
The IMDB dataset is a comprehensive dataset of movies released over the years. This dataset contains information about movie titles, release years, ratings, budgets, gross earnings, and more. This project aims to clean and preprocess the dataset to make it suitable for further analysis.

## Tasks:

1. Load the IMDb data.
2. Rename the file to the dataset name.
3. Using the Pandas dataframe drop function, get rid of unnecessary columns.
4. Determine the number of columns removed. In this case, we removed one column - budget - because it was highly correlated to the gross attribute.
5. Identify the number of missing values within each column.
6. Determine which missing values can be easily filled without changing the basic statistics of the data. In this case, the "gross" column can be easily filled using the mean result without changing the statistics of the column.
7. Fill the columns from step 6 with the fillna function.
8. Uppercase all of the country values and replace any reference to "United States" with "USA".
9. Replace "N/A", "NaN", and "Null" with an empty string.
10. Fix any unicode issues in the "movie_title" column with the ftfy library.
11. Assume a movie cannot be less than 10 minutes or greater than 300 minutes. If a movie is outside those bounds, set the value to 0.
12. Identify what would be considered an outlier for the "imdb_score" column.
13. Fix "imdb_score" and "title_year" outliers.
14. Output the cleaned up file onto a new csv called "clean_imdb.csv".

## Timeline:

### Day 1:

* Load the IMDb dataset.
* Rename the file to the dataset name.
* Use the Pandas dataframe drop function to get rid of unnecessary columns.
* Identify the number of columns removed.
* Determine the number of missing values within each column.
* Determine which missing values can be easily filled without changing the basic statistics of the data.
* Fill the columns from the previous step with the fillna function.

### Day 2:

* Uppercase all of the country values and replace any reference to "United States" with "USA".
* Replace "N/A", "NaN", and "Null" with an empty string.
* Fix any unicode issues in the "movie_title" column with the ftfy library.
* Assume a movie cannot be less than 10 minutes or greater than 300 minutes. If a movie is outside those bounds, set the value to 0.
* Identify what would be considered an outlier for the "imdb_score" column.

### Day 3:

* Fix "imdb_score" and "title_year" outliers.
* Output the cleaned up file onto a new csv called "clean_imdb.csv".



