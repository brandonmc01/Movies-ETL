# Movies-ETL

The purpose of this project was to clean large sets of movie data retrieved from wikipedia and kaggle. Once the data was cleaned, I merged the two sets of data. I then merged this dataframe with a dataframe of ratings data for all movies. Finally, I exported this dataframe, as well as the raw ratings data into an SQL database.

#### Deliverable 1 : ETL_function_test
- Data is extracted from Wikipedia in JSON format.
- Data is extracted from Kaggle Metadata and MovieLens.

#### Deliverable 2: ETL_clean_wiki_movies
- The TV shows are filtered out from the Wikipedia data and transformed into a Dataframe.
- A try-except block used to catch errors while extracting IMDB IDs with a regular expression.
- A list comprehension is used to keep columns with non-null values.
- The non-null box office data is converted to string values using the lambda and join functions.
- Transformation of the Wikipedia data by cleaning the box office, budget, release date and running time columns.

#### Deliverable 3: ETL_clean_kaggle_data
- Cleaned the Kaggle metadata.
- The Wikipedia and Kaggle dataframes were merged and cleaned.
- Extracted and cleaned the MovieLens Ratings Data.
- Finally merged the ratings data with the Wikipedia and Kaggle metadata.

#### Deliverable 4: ETL_create_database
- Uploaded the clean and merged data on PostgreSQL.
- Existing data in Movies table replaced by current data in PostgreSQL.

