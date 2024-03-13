# kNN based Movie Recommender Engine - CA05 

## Data Source and Contents

This project uses a IMDB dataset from the UCI Machine Learning Repository, comprising data from 30 different movies. The dataset contains the IMDB rating for each movie, as well as one-hot encoding for the movie Genre (Biography, Drama, Thriller, Comedy, Crime, Mystery, History)

**Dataset Path:** [Census Data CSV](https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv)

## Objective

The goal is to generate a Reccomender System to find the 5 most similar movies to "The Post" based on rating and genre.

## Procedures

- **NearestNeighbors Identification:**
  Uses the NearestNeighbors package from sklearn to find the closest observations (k_neighbors = 5) to a prediction observation. 
  
## Deliverables

- A fully functional Jupyter Notebook.
- A comprehensive README file detailing the methodology and results.
- Repository access on GitHub containing the notebook and README.

## Observations

The analysis will provide a list of the movie titles of 5 movies that are most similar to "The Post", as identified by the NearestNeighbors model.

## Useful Resources

- [SKlearn kNN Function Parameters](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
