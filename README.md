#Cryptocurrencies

##Project Overview
The goal of this project is to use unsupervised machine learning to group cryptocurrencies for use in planning a new investment product.

##Methods
Four elements were used in the clustering analysis: The total number of coins mined, the total supply, the algorithm and the proof type. After scaling and principal components analysis, k-means with 4 classes was used to cluster the 532 included coins.

##Results
Clustering resulted in 2 primary clusters which contained the majority of the coins. A third cluster contained 4 coins, and a fourth cluster contains just one coin, BitTorrent. 
While BitTorrent is easily distinguishable from the other coins by the numeric elements: Coins mined and supply, the other 3 clusters cannot be differentiated when looking at the plot of those two elements. However, the principal components analysis allowed inclusion of categorical date - algorithm and proof type, without adding too many dimensions. 
These dimensions must be contributing important information to the clustering. 

