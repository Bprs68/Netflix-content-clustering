<h1 align='center'> Netflix Content Clustering and Recommendar System </h1>
<p align='center'>
  <img src="https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80" height="300" width="700">
</p>

This project aims to cluster similar Netflix movies/shows and build a content-based recommendation system for users based on their watching history. The dataset used in this project contains information on movies/shows available on Netflix as of 2019, collected from Flixable, a third-party Netflix search engine.

## Project Summary
The project can be summarized as follows:

1. Exploratory Data Analysis to understand the dataset
2. Clustering similar content by matching text-based features (director, cast, country, genre, rating, and description) using K-Means and Agglomerative Hierarchical algorithms
3. Building a content-based recommendation system using cosine similarity
4. Providing 10 recommendations to users based on their watching history

## Business Use Case
The project can be useful for Netflix in the following ways:

* Improving user engagement by providing personalized recommendations
* Identifying trends in the type of content available in different countries
* Understanding how the number of TV shows and movies has changed over time

## Technical Details
The project uses the following techniques and tools:

1. Python programming language
2. Jupyter Notebook as the development environment
3. Pandas and Numpy libraries for data manipulation
4. Matplotlib and Seaborn libraries for data visualization
5. Scikit-learn library for K-Means and Agglomerative Hierarchical clustering
6. Scipy library for dendrogram visualization
7. Tf-idf vectorization for feature engineering
8. Cosine similarity for building the recommendation system

## Challenges
Some of the challenges faced during the project include:

1. Handling missing values in the dataset
2. Choosing the optimal number of clusters for K-Means and Agglomerative Hierarchical clustering
3. Balancing the number of features to include in the clustering and recommendation systems
4. Optimizing the performance of the recommendation system to handle large datasets

## Future Scope
Some of the potential future extensions of the project include:

* Integrating external datasets such as IMDB ratings and Rotten Tomatoes for more accurate clustering and recommendations
* Using collaborative filtering techniques to build a user-based recommendation system
* Incorporating user feedback to improve the quality of recommendations over time

## References
The following resources were used in the development of this project:

* <a href =https://www.kaggle.com/shivamb/netflix-shows> Netflix Movies and TV Shows Dataset on Kaggle</a>
* <a href="https://scikit-learn.org/stable/modules/clustering.html">Scikit-learn Clustering Documentation</a>
* <a href="https://en.wikipedia.org/wiki/Cosine_similarity"> Cosine Similarity for Vector Space Models </a>
* <a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf">TF-IDF Vectorization for Text Data</a>
