The aim of this project is to predict the mood of the user from the audio metrics of the song and recommend similar songs to the user. 
I used the spotify data set from kaggle to perform the analysis, clustering and classification. Using the output of clustering and classification, I classified the test data into one of the clusters. From the cluster labels, I chose 5 songs randomly and recommended them to the user.

Although this can be optimised by sticking to unsupervised learning approach completely, I chose to take a hybrid approach of including both Supervised (SVC) and Unsupervised (K-means Clustering) and combining them.

This has not anyway helped me improve the quality. If anything, this only deteriorates the performance as most of the data was overfitting.
