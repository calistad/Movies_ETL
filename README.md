# Movies ETL

## Overview

To follow the ETL process:

- To extract the Wikipedia and Kaggle data from their respective files.

- To transform the datasets by cleaning them up and joining them together.

- To load the cleaned dataset into a SQL database.

### Purpose

Amazing Prime loves the dataset, thus we will create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

## Summary

### ETL_function_test

- To Load and extract the Wikipedia data.
- To Extract the Kaggle Data.
- To Convert each file to a DataFrame.

  - The wiki_movies_df DataFrame
  
  ![Screen Shot 2021-10-08 at 3 32 31 PM](https://user-images.githubusercontent.com/88747464/136615482-c716c39e-4578-487b-bc6b-e5b3b0aad5c2.png)

  - The kaggle_metadata DataFrame
  
  ![Screen Shot 2021-10-08 at 3 32 44 PM](https://user-images.githubusercontent.com/88747464/136615489-d1c70aab-e892-4121-920b-d3253674a6eb.png)

  - The ratings DataFrame
  
  ![Screen Shot 2021-10-08 at 3 32 54 PM](https://user-images.githubusercontent.com/88747464/136615495-9a9d6348-c79e-4e50-b048-6e92502df2a8.png)


### ETL_clean_wiki_movies

- To extract, transform, and clean the Wikipedia Data.

- To use a try-except block to catch errors.

- To convert the transformed data into a DataFrame.

![Screen Shot 2021-10-08 at 3 35 08 PM](https://user-images.githubusercontent.com/88747464/136615841-91c2bd31-0bb0-4476-996b-ee34f2da4f69.png)

### ETL_clean_kaggle_data

- To extract and transform the Kaggle Data.

- To convert the transformed data into a DataFrame.

![Screen Shot 2021-10-08 at 3 35 36 PM](https://user-images.githubusercontent.com/88747464/136615873-1ab5be80-c8ac-441e-8626-7181cf8ee787.png)


### ETL_create_database

- To merge Wikipedia and Kaggle DataFrames.

- To transform and merge the ratings data.

- To create and connect to the database, then import data.

![movies_query](https://user-images.githubusercontent.com/88747464/136615958-582584ea-53ae-42e4-a5ae-305afcc48f79.png)

![ratings_query](https://user-images.githubusercontent.com/88747464/136615984-13fd0b4b-0532-4db7-96b1-50e863538012.png)
