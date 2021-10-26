# SKFR-Python
## Simple and Scalable Sparse k-means Clustering via Feature Ranking

References : [Paper](https://arxiv.org/abs/2002.08541)

Implementation in R and Julia by Author : [GitHub](https://github.com/ZhiyueZ/SKFR)

In the iPython Notebook there are three implementations:
- k-means (scikit-learn) 
- SKFR-1
- SKFR-2

Note: In case of missing features in datapoints the I have removed the datapoint before training but this is not the optimal solution suggested by the authors of the paper

## Next Steps?

- Design an implementation using tensors and pytorch to be able to use GPU for lower inference times.
