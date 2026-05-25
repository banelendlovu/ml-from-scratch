# ML from scratch

Implementing machine learning algorithms from mathematical first principles — no shortcuts, no black boxes.

Each file includes the underlying math in the docstring, a hand-traced example in comments, and a test. The goal is to understand *why* each algorithm works, not just how to call it.

## Progress

### Linear algebra
- [ ] `vectors.py` — dot product, norm, unit vector
- [ ] `matrices.py` — multiply, transpose, inverse
- [ ] `decompositions.py` — LU, QR, SVD, eigendecomposition

### Probability & statistics
- [ ] `distributions.py` — common distributions from first principles
- [ ] `expectation.py` — expectation, variance, covariance

### Regression
- [ ] `linear_regression.py` — OLS derivation, normal equations
- [ ] `logistic_regression.py` — MLE derivation, gradient descent

### Classification
- [ ] `naive_bayes.py`
- [ ] `decision_tree.py`
- [ ] `svm.py`

### Clustering
- [ ] `kmeans.py`

### Neural networks
- [ ] `neural_net.py` — single hidden layer, backprop from scratch

## Stack

Python 3.x · NumPy (for verification only — core logic uses raw math)

## Reference

Primary text: *Mathematics for Machine Learning* — Deisenroth, Faisal, Ong (free at mml-book.github.io)