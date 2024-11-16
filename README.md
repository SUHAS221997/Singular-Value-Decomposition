Dataset Overview

The Netflix dataset used in this project is a cleaned and combined version of multiple data sources.
It represents user-item interactions in the form of a user-rating matrix. The rows correspond to users, the columns correspond to movies, and the cell values indicate the user's rating for a given movie. Missing values represent movies that users have not rated.

Dataset Overview

1. Movies Dataset (movies.csv)
This dataset contains metadata for movies available in the system.
--MovieID: A unique identifier for each movie.
--Year: The release year of the movie. Some values might be missing.
--Name: The title of the movie.

2. Ratings Dataset (ratings.csv)
This dataset contains user ratings for the movies.
--CustID: Unique customer identifiers. 
--Ratings: Ratings given by customers on a scale of 1–5.
--MovieID: A unique identifier for each movie.

Goal

The goal is to recommend movies to users based on their preferences using SVD technique.

