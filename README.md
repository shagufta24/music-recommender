# Music Recommendation System

A simple music recommender created using Collaborative Filtering techniques.

**Introduction:**

Recommendation systems are algorithms aimed at suggesting relevant items to users based on their interests. In this project, we will recommend songs to users based on their music preferences.

There are two main types of recommender systems:

- Content-based: Give recommendations based on the similarity of two song contents or attributes.
- Collaborative-filtering: Make a prediction on posible preferences using a matrix with the play counts on different songs.

**Collaborative-filtering (CF) methods** are based entirely on the past interactions recorded among users and items to produce new suggestions. These interactions are saved in a “user-item interactions matrix” and are used to detect comparable users and items and hence make predictions based on those predicted proximities.

There are two kinds of CF techniques:

- Memory-based: The closest user or items are calculated by using a similarity metric (such as Cosine similarity) on the interaction matrix.
- Model-based: Developed using machine learning algorithms to predict user’s relation to unrelated items. The model is trained to reconstruct user-item interaction values from latent feature extraction (hidden mathematical features that may not be interpretable by humans).

#

**Project Aim:**

1. Exploratory Data Analysis of the dataset.
2. Building a collaborative filtering music recommender system using the following methods:

- Memory-based CF using various similarity metrics (cosine similarity, euclidean distance and pearson correlation).
- Model-based CF using a Matrix Factorization based algorithm (Singular Value Decomposition) and Clustering based algorithm (K-nearest neighbors).

3. Making recommendations and evaluating results.

#

**Dataset Details:**

Original data source: Million Song Dataset, a freely-available collection of audio features and metadata for a million contemporary popular music tracks. This project uses the 'Taste Profile' subset.

Link: http://millionsongdataset.com/tasteprofile/

Alternate source for the data: https://www.kaggle.com/c/msdchallenge/data

This dataset contains the following data triplets: user ID, song ID and play count.

#

This repo contains the following files:

1.  A jupyter notebook named `music-recommender` that contains the data analysis and code for the recommendation system.
2.  A `txt` file named `kaggle_visible_evaluation_triplets.txt` containing the data used.
