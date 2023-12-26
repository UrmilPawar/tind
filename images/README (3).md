
# Movie Recommendation System
A content Based recommendation system was implemented using TMDB 5000 dataset

### Following is the base approach behind the result
1. **Horizontal Clustering**
- A clustering algorithm is applied on the daaset classify each and every movie instance in a cluster.The cluster of the 'test movie' is determined and all the movies that bolongs to the same cluster are extracted. 
2. **Vertical Analysis**
- For each and every column (except vote count) for the obtained set of movies , the similarities of the encodings of movies of the column with that of the test movie column were found and top five similar movies index were obtained (from each column). So a set of top 5 movies is generated for every column
- Now we check every set of 'Top 5 movies' based on every column and get the movie that has occurred in the maximum number of set
Similarly more top most repeating movies are determined and then Printed.

### Following are the steps which were implemented 
1.	**Data Loading**
- Importing the data and necessary libraries
2.	**Data Visualization** : 
-	Determining the column names and keeping only the necessary columns
- Finding the null places and filling them with mean and sum.
3.	**Data Encoding**
- Converting column into two types : Numerical , Binary lists
4.	**Training**
- Applying Clustering Algorithm
5.	**Testing**
- Implementing the approach and testing it for a random movie 


### Following are the images
![Alt text](image link)