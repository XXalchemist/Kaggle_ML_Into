# Clustering ML Algo's

_Unsupervised Learning : When we don't know the answer._

## Content

|**Sr. No.**| **Algorithm Name**|
|---|---|
|1.| K- Means |
|2.| Hierarchial Clustering |


## K - Means clustering

### Steps :-
1. Choose the number K of cluster
2. Select at random K points , the centroids(not neccessary from your dataset)
3. Assign each data point to the closest centroid that forms K cluster
4. Compute and place the new centroid of each cluster
5. Reassign each data point to the new closest centroid if any reassignment took place go to **step 4** otherwise FIN 

## Hierarchial clustering

Two types :-
- Agglomerative
- Divisive
  
### Steps (Agglomerative) :-
1. Make each data point a single point cluster -> that forms N cluster
2. Take the two closest data points and make them one cluster -> that forms N-1 cluster
3. Take the two closest cluster and make them one cluster -> that form N-2 cluster
4. Repeat Step-3 until there is only one cluster

_Distance between clusters can be measured through - Closed Points, - Farthest Points, - Average Distance_


  