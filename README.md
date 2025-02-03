# Movie-Recommendation-System-Using-Collaborative-Filtering
Creating a Recommendation System in Python

## Project Overview
This project implements a movie recommendation system using collaborative filtering techniques, specifically leveraging user-item interaction data to predict user ratings for movies. The system is designed to recommend movies based on the preferences of similar users, providing personalized suggestions that enhance user experience.

## Key Features
Collaborative Filtering: Utilizes matrix factorization techniques to derive latent factors for users and movies, facilitating accurate predictions of user ratings.
PyTorch Implementation: The model is built using PyTorch, enabling efficient computation and flexibility in model design and training.
Data Handling: Custom dataset class MovieDataset manages the loading and preprocessing of user ratings data, ensuring seamless integration into the training process.
Evaluation Metrics: Implements various evaluation metrics to assess model performance, including Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
Visualization: Includes visualization of user and movie embeddings using PCA, providing insights into the underlying relationships between users and movies.


## Dataset
The model is trained on a dataset containing user ratings for a variety of movies. The data is preprocessed to create a user-item interaction matrix, which serves as the foundation for the collaborative filtering approach.
