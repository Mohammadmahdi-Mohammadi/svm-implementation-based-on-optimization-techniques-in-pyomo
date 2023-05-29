# svm-implementation-based-on-optimization-techniques-in-pyomo

A) Load the dataset

import numpy as np
from sklearn.datasets import make_classification
x, y=make_classification(n_classes=2, n_samples=400, n_features=2, n_informative=2, n_redundant=0, n_repeated=0, shuffle=False, weights=[0.55, 0.5], random_state=27)

B) split into train and test

C) Implementation and solve the dual problem of Soft SVM in pyomo by calling ipopt

D) report accuracy precision recall f1 score Based on decision boundary

E) 5-fold cross validation Implementation 
