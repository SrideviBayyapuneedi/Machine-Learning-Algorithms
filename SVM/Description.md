# SVM Algorithm
Pros and Cons:

## The advantages of support vector machines are:
1. Effective in high dimensional spaces.
2. Still effective in cases where number of dimensions is greater than the number of samples.
3. Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
4. Versatile: different Kernel functions can be specified for the decision function.Common kernels are provided, but it is also possible to specify custom kernels.

## The disadvantages of support vector machines include:
1. If the number of features is much greater than the number of samples, the method is likely to give poor performances.
2. SVMs do not directly provide probability estimates, these are calculated using an expensive five-fold cross-validation.

Source:
http://scikit-learn.org/stable/modules/svm.html
