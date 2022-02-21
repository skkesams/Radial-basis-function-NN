# Radial-basis-function-NN

Here is a Python Code that creates an RBF Network to approximate the mapping defined by:

As a training set, use 441 randomly sampled data points defined as

Where 𝑥! = −2+0.2𝑖 𝑥 =−2+0.2𝑗 " 𝑖=0,1,...,20 𝑗= 0,1,...,20 𝑥 = #𝑥 , 𝑥 % !"

Problems solved are:

Carry out the design of RBF NN based on Gaussian kernel functions with constant spread function and using all the points in the training set as centers of the RB functions. Compare the performance results (mean square error) as you vary the spread parameter while keeping it the same for all kernel functions. Discuss your findings.

Perform the design of the RBF NN, using this time only 150 centers, choosing the centers using two approaches: a) Randomly select the centers from the input data. b) Use K-Means algorithm to find the centers. You can use a Kmeans function defined in sklearn (https://scikit- learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) or create your own.

Keep the spread parameter fix for all kernel functions. Compare the performance of this network to the one designed in part (1)
