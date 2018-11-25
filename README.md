# S_Dbw
S_Dbw validity index.
If you think the code is useful,please give me a star ^_^!

## description
The S_Dbw implemented here is suitable for evaluating the k-medoids clustering algorithm. The clustering center of the algorithm is different from k-means, which is a specific point. Therefore, some people want to use other clustering algorithms to evaluate, and need to modify the code slightly.

## S_Dbw
S_Dbw consists of two items, inter-cluster density and intra-cluster variance. When using it to select the hyperparameters of the clustering algorithm, we will choose a set of parameters that minimize the S_Dbw value.

## paper link
1.[Clustering Validity Assessment: Finding the optimal partitioning of a data set](https://pdfs.semanticscholar.org/dc44/df745fbf5794066557e52074d127b31248b2.pdf)

2.[Understanding of Internal Clustering Validation Measures](http://datamining.rutgers.edu/publication/internalmeasures.pdf)
