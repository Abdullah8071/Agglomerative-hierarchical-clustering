# Agglomerative-hierarchical-clustering

Abstract
Clustering is a task of assigning a set of objects into groups called clusters. In data mining, hierarchical clustering is a method of cluster analysis which seeks to build a hierarchy of clusters. Strategies for hierarchical clustering generally fall into two types: Agglomerative: This is a "bottom up" approach: each observation starts in its own cluster, and pairs of clusters are merged as one moves up the hierarchy. Divisive: This is a "top down" approach: all observations start in one cluster, and splits are performed recursively as one moves down the hierarchy. Motivation for clustering in general, covering hierarchical clustering and applications, includes the following: analysis of data; interactive user interfaces; storage and retrieval; and pattern recognition. 

Dataset and Feature:
Stored data approach:
Step 1: Examine all interposing dissimilarities, and form cluster from two closest
points.
Step 2: Replace two points clustered by representative point (center of gravity)
or by cluster fragment.
Step 3: Return to step 1, treating clusters as well as remaining objects, until
all objects are in one cluster.
NN-chain algorithm
Step 1: Select a point arbitrarily.
Step 2: Grow the NN-chain from this point until a pair of RNNs is obtained.
Step 3: Agglomerate these points (replacing with a cluster point, or updating
the dissimilarity matrix).
Step 4 :From the point which preceded the RNNs (or from any other arbitrary
point if the first two points chosen in steps 1 and 2 constituted a pair of
RNNs), return to step 2 until only one point remains.
Each agglomeration occurs at a greater distance between clusters than the previous agglomeration, and one can decide to stop clustering either when the clusters are too far apart to be merged (distance criterion) or when there is a sufficiently small number of clusters (number criterion). Divisive Hierarchical Clustering 

• A top-down clustering method and is less commonly used. It works in a similar way to agglomerative clustering but in the opposite direction. This method starts with a single cluster containing all objects, and then successively splits resulting clusters until only clusters of individual objects remain. GeneLinker™ does not support divisive hierarchical clustering. 

Libraries Included
In order for the completion of the specific project we also needed to download a few additional libraries which are mentioned below:
	SK learn
	Numpy
	Matplot
	NLKT

