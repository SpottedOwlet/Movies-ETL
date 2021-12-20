<h2><p align=center> ETL of Movie Datasets </p> </h2>

<h3><p> Purpose </p></h3>
This analysis uses the movie and ratings datasets from three different sources, Wikipedia, Movielens and Kaggle. The main purpose of the analysis is to clean, transform and load data into a database. 

<h3><p> Resources: </p></h3>
Data Source: movies_metadata.csv, ratings.csv, wikipedia-movies.json
Software: Jupyter Notebook, Python 3.7.10, PostgreSQL

<h3><p> Analysis Overview: </p></h3>

The function is built to clean and transform the datasets in the following 4 steps. The resulting files: 'movies' containing clean movie data and 'ratings' containing clean ratings data are then uploaded to PostgreSQL in the same function.

<h4> PART I : Write an ETL Function to Read Three Data Files : ETL_function_test.ipynb </h4>
<h4> PART II : Extract and Transform the Wikipedia Data : ETL_clean_wiki_movies.ipynb </h4>
<h4> PART III : Extract and Transform the Kaggle Data : ETL_clean_kaggle_data.ipynb</h4>
<h4> PART IV : Create the Movie Database : ETL_create_database.ipynb </h4>

