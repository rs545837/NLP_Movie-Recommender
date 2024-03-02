# NLP_Movie-Recommender

Google's Universal Sentence Encoder can generate embeddings for any sentence, which can be used to create a recommendation system for movies. The system uses the Top 10,000 movies dataset from Kaggle, which provides a short description of each movie. The system then generates embeddings for all 5,500 movies in the dataset and uses principal component analysis to visualize the embeddings in 2D. The system can then use the scikit-learn NearestNeighbor algorithm to find the top 10 nearest neighbors for any given movie.
