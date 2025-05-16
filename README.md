# movie-recomended-system
An introductory movie recommendation system built using Python. It uses the Bag of Words technique for vectorizing movie metadata like genre, cast, and keywords. Based on cosine similarity, the system suggests similar movies, making it a simple and effective content-based recommender.





🎬 Step-by-Step Guide to Building a Content-Based Movie Recommender System
Understanding Recommender Systems

The video begins by explaining the types of recommender systems, focusing on content-based filtering, which recommends items similar to those a user has liked in the past.
Wikipedia
+2
labelyourdata.com
+2
arXiv
+2

Project Architecture

An overview of the system's architecture is provided, detailing how different components interact, including data preprocessing, feature extraction, similarity computation, and the recommendation engine.

Data Collection and Preprocessing

The project uses the MovieLens dataset, which contains information about movies, including titles, genres, and user ratings.

Data cleaning involves handling missing values, merging datasets, and preparing the data for analysis.
Wikipedia
+3
YouTube
+3
Medium
+3

Feature Extraction

Textual data from movie overviews and genres are transformed into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).

This step converts text into a format suitable for similarity computations.
arXiv
+2
Medium
+2
GeeksforGeeks
+2
Medium
+1
YouTube
+1

Computing Similarity

Cosine similarity is calculated between movie feature vectors to determine how similar each pair of movies is.

This similarity measure helps in identifying movies that are alike based on their content.

Building the Recommendation Function

A function is developed that, given a movie title, retrieves the most similar movies based on the computed cosine similarity scores.

This function forms the core of the recommendation system.
arXiv
+5
YouTube
+5
Medium
+5

Creating a Web Interface

A simple web application is built using Streamlit, allowing users to input a movie title and receive recommendations.

The interface enhances user interaction and accessibility.

Deployment on Heroku

The final application is deployed on Heroku, making it accessible online.

Deployment involves setting up the necessary files like requirements.txt and Procfile, and pushing the code to a Heroku app
