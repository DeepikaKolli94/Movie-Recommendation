# Movie-Recommendation

# Objective
Main objective of this project was to perform analysis on movies data and use this data in combination with MovieLens ratings to build various types of Recommender Systems. The main objective of recommender systems is customization. There are different categories of recommender systems that we have implemented in this project specifically collaborative filtering algorithms using KNN and SVD for dimension reduction of a large User-Item Sparse matrix to provide more robust recommendations. Next to overcome the shortcomings faced by KNN and SVD we have implemented a more sophisticated method to improve movie recommender system where we have implemented Alternating Least Square (ALS) Matrix Factorization in Apache Spark ML.


# Data 
Dataset consists of metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2018. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, IMDB vote counts and vote averages. This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5. 
Dataset Reference : https://grouplens.org/datasets/movielens/latest/

# Results
Below we have shown the RMSE values obtained for all the models that we have implemented. ALS model had lower RMSE value of 0.823 on test data after Cross validation and hyper parameter tuning compared to the RMSE value of 0.91 for SVD and 1.02 for KNN

# Technologies
Python, Pyspark
