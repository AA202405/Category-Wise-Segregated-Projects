Movie Recommendation System (TMDB Dataset)

This project is a content-based Movie Recommendation System built using the TMDB (The Movie Database) dataset.
The system predicts five similar movies based on a selected movie by analyzing metadata such as genres, overview, cast, crew, and keywords.
A simple Python-based frontend is implemented using PyCharm.

Features
1)Recommends the top 5 movies similar to a given movie.
2)Uses TF-IDF vectorization and cosine similarity for similarity measurement.
3)Performs text preprocessing and metadata engineering for accurate recommendations.
4)Utilizes multiple movie metadata fields from the TMDB dataset.
4)Contains a clean and minimal Python-driven interface.


Dataset Information
The project uses the TMDB Movies Dataset, which includes:
  Movie titles
  Genres
  Overviews/descriptions
  Keywords
  Cast and crew details
  Popularity, ratings, and other metadata
Note: The dataset may need to be downloaded externally due to size limitations and placed in the project’s data folder.

How the System Works
The dataset metadata is cleaned and merged into a single descriptive text field.
TF-IDF vectorization converts the merged text into numerical vectors.
A cosine similarity matrix is generated for all movie vectors.
When a movie is selected, the system identifies the closest matches based on similarity scores.
The five most similar movies are returned as recommendations.

Example Output
Input Movie: Interstellar
Recommended Movies:
The Martian
Gravity
Arrival
Inception
Sunshine
