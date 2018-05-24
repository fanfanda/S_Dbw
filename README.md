# S_Dbw
S_Dbw validity index.
If you think the code is useful,please give me a star ^_^!

S_Dbw原论文地址(Clustering Validity Assessment: Finding the optimal partitioning of a data set)：https://pdfs.semanticscholar.org/dc44/df745fbf5794066557e52074d127b31248b2.pdf <br>

各类聚类算法评价指标的评测论文(Understanding of Internal Clustering Validation Measures)：http://datamining.rutgers.edu/publication/internalmeasures.pdf ,该篇论文是通过比较多种聚类评价指标的反馈来选择聚类算法的超参，最终结论是S_Dbw对于异常点，扰动等等因素的干扰最鲁棒，选出的超参较为准确。<br>

这里实现的S_Dbw适用于评价k-medoids聚类算法，该算法的聚类中心不同于k-means，是具体的某一个点，所以有人想用与其他的聚类算法评价，需要稍微修改代码
