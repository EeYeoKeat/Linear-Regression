Gaussian Process (GP) is refer to collection of random variables such that any subset of these variables is jointly Gaussian. We can use GP to describe distribution over functions. The Kernel is the essential component for GP and it mainly for compute covariance between datapoints. 


The Gaussian Processes Regression is an application of GP to perform regression. 

<img alt="note about GP" width="50%" src="img/note1.JPG">

Theoretically, the f(x) and f(x') is similar if the vectors of x and x' similar. The covariance function K(x,x') is indicate the similarity between x and x' and encodes the similarity of f(x) and f(x'). The mean function, m(x) encodes the priori expectation of function. If the similarity between known datapoints is small, then the mean function tends to nominate result.


###References:
1. http://www.gaussianprocess.org/gpml/chapters/RW.pdf
2. https://towardsdatascience.com/gaussian-process-regression-from-first-principles-833f4aa5f842


