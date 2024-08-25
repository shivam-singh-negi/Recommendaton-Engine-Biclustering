# Recommendation-Engine-Biclustering

This is a Recommendation System that recommends movies to users based on their past movie preferences. The system leverages a **Biclustering** approach, originally used in biomedical fields for gene sequencing, and adapts it for use in movie recommendations.

## Algorithms and Techniques Used
The system employs the following key techniques:
- **Clustering**: Utilizes K-Means clustering to group similar users or movies.
- **Matrix Factorization**: Decomposes the user-movie interaction matrix into factorized components for improved recommendations.
- **Similarity Measurements**: Calculates similarities between users or movies to enhance recommendation accuracy.

## Input and Output
The recommendation engine works with movie IDs, where each movie is mapped to a unique ID. The inputs are given as a list of movie IDs, and the engine outputs recommended movie IDs.

## Input Files
The system requires the following input files:
- **movies_2000.csv**: Contains a list of movies along with their unique IDs.
- **ratings_2000.csv**: Contains user ratings for each movie, with mappings between users and movie IDs.

## Intermediate Files
These files are generated during the processing stages and store important intermediate results:
- **movie_movie_matrix**: Stores the factorized components of the movie similarity matrix.
- **user_user_matrix**: Stores the factorized components of the user similarity matrix.

## Summary
This system adapts powerful biclustering and matrix factorization techniques to deliver personalized movie recommendations based on users' historical preferences.
