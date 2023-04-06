# MachineLearning

**kNN based Movie Recommender Engine**


**Part 1: The Application**

Question I am trying to answer here: Given a movies data set, what are the 5 most similar movies to a movie query?

**Part 2: Data Source and Contents**
Use the following path as the data source:
  "https://github.com/ArinB/MSBA-CAData/raw/main/CA05/movies_recommendation_data.csv"
 
The data contains thirty movies, including data for each movie across seven genres and their IMDB ratings. The labels column values are all zeroes because we aren’t using this data set for classification or regression. You can ignore this column.

Additionally, there are relationships among the movies that will not be accounted for (e.g. actors, directors, and themes) when using the KNN algorithm simply because the data that captures those relationships are missing from the data set. Consequently, when we run the KNN algorithm on our data, similarity will be based solely on the included genres and the IMDB ratings of the movies.


**Part 3: Building your own Recommender System**

Your website sends a request to its back-end for the 5 movies that are most similar to The Post. The back-end has a recommendation data set exactly like ours. It begins by creating the row representation (better known as a feature vector) for The Post, then it runs a program similar to the one below to search for the 5 movies that are most similar to The Post, and finally sends the results back to the user at your website.

