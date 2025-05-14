# TMDB-Movie-Recommender
This project implements a movie recommendation system using content-based filtering. It utilizes metadata such as movie descriptions, genres, keywords, and crew details to suggest movies based on similarity to a given movie.

## Dataset Used
The dataset used here is the TMDB movie dataset acquired from Kaggle [(Link Here)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
The dataset was collected from [TMDB](https://www.themoviedb.org/), and you can explore their API for more information and additional data. The dataset files could not be uploaded due to their large size, so it is suggested that it should be downloaded from Kaggle or the website link provided above.

## Project Overview
This movie recommendation system uses the TMDB movie dataset to build a content-based recommendation engine. The system calculates movie similarities based on a combined feature set, including:

- Overview
- Genres
- Keywords
- Cast
- Crew

We apply natural language processing (NLP) techniques such as text vectorization to create similarity scores for the movies, and the system then recommends the most similar ones.
## Main Technologies Used

- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: For machine learning, including text vectorization and similarity calculation.
- **NumPy**: For numerical operations.

## Project Setup

1. **Install Dependencies**:
    Ensure that you have Python installed on your machine. Then, install the required dependencies using:
    ```bash
    pip install -r requirements.txt
    ```

2. **Running the Script**:
    To generate recommendations, simply run the script after setting up the environment:
    ```bash
    python recommendation_system.py
    ```

3. **Search for Movies**:
    In the script, use the `recommend()` function to input a movie name (e.g., `recommend("Avatar")`) and get a list of similar movies based on the content features.

## Copyright:
This project aims to acquire the basic concepts of a recommender and NLP strategies. Although it is a well-known straightforward approach, it is not the intention to copy the code and plagiarize it. 
