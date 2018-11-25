# S_Dbw
S_Dbw validity index.
If you think the code is useful,please give me a star ^_^!

## description
The S_Dbw implemented here is suitable for evaluating the k-medoids clustering algorithm. The clustering center of the algorithm is different from k-means, which is a specific point. Therefore, some people want to use other clustering algorithms to evaluate, and need to modify the code slightly.

## S_Dbw
S_Dbw consists of two items, inter-cluster density($1.1$) and intra-cluster variance($1.2$). When using it to select the superparameter of the clustering algorithm, we will choose a set of parameters that minimize the S_Dbw value.
$$Dens\_bw(c) = \frac{1}{c\cdot(c-1)}\sum_{i=1}^{n}(\sum_{{{j=1}\atop{i\neq{j}}}}^{c}\frac{density(u_{ij})}{\max(density(v_i), density(v_j))}) \tag{1.1}$$
$$Scat(c) = \frac{1}{c}\sum_{i=1}^{c}\frac{\left\|\delta(v_i)\right\|}{\left\|\delta(S)\right\|} \tag{1.2}$$

## paper link
1.[Clustering Validity Assessment: Finding the optimal partitioning of a data set](https://pdfs.semanticscholar.org/dc44/df745fbf5794066557e52074d127b31248b2.pdf)

2.[Understanding of Internal Clustering Validation Measures](http://datamining.rutgers.edu/publication/internalmeasures.pdf)
