Key Findings:
K-means Clustering: Utilizing K-means clustering, we identified two primary customer segments characterized by their purchasing behavior. Cluster 0 represents customers with low recency, high frequency, and high monetary value, while Cluster 1 comprises customers with high recency, low frequency, and low monetary value.
Hierarchical Clustering: Despite its exploratory nature, hierarchical clustering failed to yield meaningful segmentation due to the diverse count of customers in the resulting clusters. This highlights the importance of considering cluster balance in algorithm selection.
DBSCAN: While DBSCAN achieved a respectable Silhouette Score, the unbalanced distribution of customers across clusters, particularly in Cluster -1, indicates limitations in capturing meaningful patterns. Further refinement of parameters or preprocessing steps may be necessary to enhance the clustering results.![image](https://github.com/tranyuan/unsupervisedfinal/assets/56104350/f178a9e8-e331-4b89-a305-5c8cb30bf337)
