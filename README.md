# MOVIES-ETL

## Overview
Amazing Prime is a "comapany" that loves their dataset and wants to keep it updated on the regularly. The purpose of the project is to refactor the code from this module to create one function that takes in the three files— Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Analysis
Using my knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data to merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates.
Then, I have merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the _"movies_df"_ DataFrame

Movies dataframe
<img width="756" alt="D3_movies_df" src="https://user-images.githubusercontent.com/98790082/161583687-03fc3988-b580-47b1-acfe-9b8f55d7234a.png">

Wiki_movies dataframe
<img width="750" alt="D2_wiki_movies_df" src="https://user-images.githubusercontent.com/98790082/161583778-1e00d7d3-48b7-4b4f-8270-b271ca8007f3.png">
 
Movie ratings
<img width="803" alt="D3_movies_ratings_df" src="https://user-images.githubusercontent.com/98790082/161583941-fdff44fd-4673-48df-9764-6721b3772031.png">


wiki_movies dataframe columns
<img width="360" alt="D2_wiki_movies_df_columns" src="https://user-images.githubusercontent.com/98790082/161584119-aa3e87a9-430c-41c9-a05d-3c233faffebc.png">

