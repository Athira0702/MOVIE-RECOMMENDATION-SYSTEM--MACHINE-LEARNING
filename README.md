# MOVIE RECOMMENDATION SYSTEM MACHINE-LEARNING

Welcome to the Movie Recommendation System repository! This project aims to deliver personalized movie recommendations using various algorithms. This repository implements a movie recommendation system using three distinct approaches: Simple, Content-Based, and Collaborative. 
## DATASETS
### TMDB Dataset
- [Download Here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Comprehensive movie-related information for 4803 movies.
### MovieLens Dataset
- [Download Here](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip)
- Information on 9,742 movies and 100,836 ratings.
## Data Preprocessing
- Selected relevant columns from 'tmdb_dataset'.
- Extracted 'cast' and 'crew' information.
- Filled missing values and converted JSON-formatted columns.
- Created a new feature, 'feature', by combining textual information.
- Merged movie and rating data from MovieLens based on 'movieId'.
## Exploratory Data Analysis (EDA)
- Explored common words in titles and overviews using wordclouds.
- Analyzed production locations, top-earning companies, popular genres, and voting patterns.
## Simple Recommendation System
- Utilizes a straightforward approach based on average ratings, vote counts, and popularity.
- Calculates weighted average score using a formula.
- Identifies top-rated and popular movies.
## Content-Based Recommendation System
- Implements content-based recommendation systems based on movie overviews and metadata.
- Uses TF-IDF and Count Vectorization techniques.
- Develops functions for generating movie suggestions based on similarity scores.
## Collaborative Filtering
- Leverages past user-item interactions for making future recommendations.
- Utilizes a "user-item interactions matrix" to represent user interactions with specific movies.
- Develops collaborative filtering models for personalized recommendations.

