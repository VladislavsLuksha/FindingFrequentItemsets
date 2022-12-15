# Finding Frequent Itemsets
Algorithms for Massive Datasets Project


In this project, we studied FP-Growth technique to perform frequent itemsets mining on a large-scale data. The data used for the study was part of a dataset containing tweets about the Russo-Ukrainian war. The dataset was downloaded from the Kaggle repository. Given the size of the dataset and the importance for scaling up, Spark environment was used for the computations. Since the proposed project directly involves working with text, preliminary research and data pre-processing were carried out, including removing identical tweets, text cleaning, stop-words removal and tokenization. The analysis is performed for two languages: Ukrainian and English. After the implementation of FP-Growth algorithm for English tweets, we studied the scalability of the code, varying the size of the dataset and minimal support parameter.
