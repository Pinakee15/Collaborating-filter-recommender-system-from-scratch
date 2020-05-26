# Recommender-System

### First file 
A Movie Recommender model trained on netflix's movie-user-dataset. One of the most popular classical way of recommendation
system is the collaborative filtering approach , where we are give a matrix of user ratings and the movie. We can factorise
that matrix using the technique matrix factorization and this done through Singular Value decompostion (SVD). After the 
factorization we get three matrices out of which two matrices are anologous to the user matrix(S) and item matrix(V). The sigma 
matrix is the scaling matrix . Using these two matrices (S and V) , we can get the user-user similarity and the item-item similarity.
If we want to recommend on the basis of what two similar user's taste then it is called user-user similarity recommendation
system . This is less popular as the taste of user keeps on changing with time . A better approach is the item-item similarity.
The similarity between two matrices can be calculated either by cosine-similarity or the jaccard-simikarity of which cosine 
similarity is more popular. 

USEFUL RESOURCE : https://www.youtube.com/watch?v=ZspR5PZemcs

### Second file uses both Collaborative and content based recommendation system.
Content based similarity system is just where we take all the features of the items and vectorize it whether in word2vec features
or if the image is present then in extracting image features also. For example in amazon the contents are also recommended based
on content based recommendation. Similaruty between two vectors can be calculated either by eucledian distance or cosine similarity,
cosine similarity being more feasible . And this podcast system also takes into consideration the matrix factroization concepts

