# Bonferroni Mean based Fuzzy K-Nearest Centroid Neighbor (BM-FKNCN) 
K-nearest neighbor (KNN) is an effective nonparametric classifier that determines the neighbors of a point based only on distance proximity. The classification performance of KNN is disadvantaged by the presence of outliers in small sample size datasets and its performance deteriorates on datasets with class imbalance. We propose a local Bonferroni Mean based Fuzzy K-Nearest Centroid Neighbor (BM-FKNCN) classifier that assigns class label of a query sample dependent on the nearest local centroid mean vector to better represent the underlying statistic of the dataset. The proposed classifier is robust towards outliers because the Nearest Centroid Neighborhood (NCN) concept also considers spatial distribution and symmetrical placement of the neighbors. Also, the proposed classifier can overcome class domination of its neighbors in datasets with class imbalance because it averages all the centroid vectors from each class to adequately interpret the distribution of the classes. The BM-FKNCN classifier is tested on datasets from the Knowledge Extraction based on Evolutionary Learning (KEEL) repository and benchmarked with classification results from the KNN, Fuzzy-KNN (FKNN), BM-FKNN and FKNCN classifiers. The experimental results show that the BM-FKNCN achieves the highest overall average classification accuracy of 89.86% compared to the other four classifiers.

# Citation
If the code is useful in your research, please cite the following paper:

A. Widyadhana, C. B. P. Putra, R. Indraswari, and A. Z. Arifin, “A Bonferroni Mean Based Fuzzy K Nearest Centroid Neighbor Classifier,” J. Ilmu Komput. dan Inf., vol. 14, no. 1, pp. 65–71, 2021.

https://doi.org/10.21609/jiki.v14i1.959

# Classifier

<ul>
  <li>KNN</li>
  <li>FKNN</li>
  <li>FKNCN</li>
  <li>BM-FKNCN</li>
  <li>BM-FKNCN</li>
</ul>

# Data

<ul>
  <li>Mammogram</li>
  <li>Vehicle</li>
  <li>Ionosphere</li>
  <li>E-Coli (Imbalanced)</li>
  <li>Glass (Imbalanced)</li>
  <li>Iris</li>
  <li>Wine</li>
  <li>Appendictis (Imbalanced)</li>
</ul>


# Result
```
Average of Accuracy

KNN = 0,8630
FKNN = 0,8666
FKNCN = 0,8637
BM-FKNN = 0,8634
BM-FKNCN = 0,8986
```

# License
This project is licensed under the terms of the apache 2.0 license (as Tensorflow and derivatives). If used for research, citation would be appreciated.
