# CEM-Algorithm-and-Diagonal-Gaussian-Mixtures

### Goal
Find the best unsupervised classification. Use of probabilistic models.

### Language
```Python```

### Contents
1. Definition of diagonal Gaussian mixture models
2. Writing the kmeans algorithm and improvements
3. Implementation of the CEM algorithm

### Librairies
* ```numpy```
* ```matplotlib```
* ```scipy```

### Conclusion 
In this study we implemented the kmeans algorithm. We found that the kmeans were very dependent on the initialization, and that the output could therefore vary greatly from one classification to another.
The CEM algorithm has much less variability, and enables us to find the two classes more accurately. It seems more appropriate to use it for this type of unsupervised classification.
