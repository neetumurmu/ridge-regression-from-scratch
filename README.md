# Ridge Regression from Scratch

This project implements ridge regression from scratch in python using both batch and stochastic gradient descent.  
A **multivariate dataset with multicollinearity** is used for testing algorithms, which is simulated using scikit-learn.   
Evaluation metric used : **R2-score**

### Objectives
- To understand the math behind ridge regression algorithm.
- To compare performance difference between algorithms implemented using batch and stochastic gradient descent.
- To compare the accuracy of implemented regression algorithms with scikit-learn algorithms.

### Observations 

- Batch GD outperforms SGD by a large margin, because a small dataset is used to train the algorithms.
- Implemented algorithms have almost same accuracy with a difference of +/-0.5-1.0%.


