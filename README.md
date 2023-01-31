# KNN-classifier
Implement your own simple KNN classifier using Python

Each dimension is normalized, separately from all other dimensions.
Specifically, for both training and test objects, each dimension are
transformed using function: F(v) = (v - mean) / std, using the mean and std
of the values of that dimension on the TRAINING data.

Used Euclidean distance to compute distances between instances.

Report of accuracy on testing data when k=1,2,3....9.

As output, the programs should print the value of k used for the test
set on the first line, each output line should list the predicted class
label, and actual class label.
