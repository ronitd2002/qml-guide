# Classification tasks (an intro)

Mapping between `N` datapoints with `n` feature space, with operators of dimensions 2^nX2^n. This mapping function gives a value `y` within a finite set of labels of size `d`. If `d`=2 binary classification problem otherwise it is a multi class classifier. 

With this much clear for us we can be given a set of points in euclidean space and we might require to draw a suitable hyperplane with a linear form resembling:

y_i (label) = W_i (weight matrix) @ x_i (datapoints) + b_i (bias)

Usually this has overfitting and generalization problems and such an ideal fit is possible only for **regression problems**. In other general cases we can solve this using two methods:

1. A **support vector machine** *(supervised algorithm)*
This is a supervised algorithm and hence requires us to train the model and test it/ validate it against the testing dataset partition. 
2. **Kernel Method** *(unsupervised algorithm)*
This method involves encoding a phi function into the data vector and this phi transformation encaptures the essence of this aforementioned *"hyperplane"*. )

All of this is pretty cool but all of this is already defined and standard methods in classical machine learning. So what is *Quantum* here?

## Quantum Benchmarks of above standard classification methods

So all of the above theories have quantum benchmarks for them. We will implement same in a following notebooks and test the performance of the same against their classical versions for same number epochs.