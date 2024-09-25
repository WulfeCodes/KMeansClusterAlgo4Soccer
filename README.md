This Google Colab Notebook entry imports a soccer dataset, cleans, and picks certain columns for cluster consideration.

The data is then scaled to keep values between 1-10.

The new_centroids(): 
#find all players in cluster, take geometric mean from centroid's distance
The get_labels()
  calculates the euclidian distances per group to centroid and returns the columns with the cluster with the shortest distance highlighted.
and
random_controids()
  initializes a centroid with a value by sampling a float random value in the dataframe DB

  Lastly plot standards are initialized for optimal data visualizatios, along with the hyper parameters of the loop.

  The summary of the functionality of this code. It initializes k random centroids then labels the data in categories based on the euclidian distance, the centroids are then recalculated and  repeated until the max_iterations has been reached or the cluster algo has stopped moving.
