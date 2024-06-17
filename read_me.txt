This project processes the TMDB movie dataset (tmdb_5000_credits.csv) using Apache Spark and creates two new dataframes:

credits_cast: A dataframe where each row represents an actor's role in a movie. It contains a total of 4803 distinct movies.
credits_crew: A dataframe where each row represents a crew member's job in a movie. It contains a total of 4803 distinct movies.
The project demonstrates Spark's capabilities for processing and analyzing large-scale movie data. The created dataframes can serve as a foundation for further analysis related to the film industry.

Technologies Used:

Apache Spark
Python
Data Source:

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv