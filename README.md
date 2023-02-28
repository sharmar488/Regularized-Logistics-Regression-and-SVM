# Regularized-Logistics-Regression-and-SVM
## Regularized Logistics Regression
Train and test a regularized logistic regression model one two data sets, namely the breast
cancer and sonar data sets which are available here https://www.csie.ntu.edu.tw/~cjlin/
libsvmtools/datasets/binary.html#breast-cancer and here https://www.csie.ntu.edu.
tw/~cjlin/libsvmtools/datasets/binary.html#sonar. We will use the scaled version for
our experiment. A copy of them is also enclosed in this homework. Use the provided training/testing splitting. In particular, the file “xxx-scale-test-indices.txt” contains the indices of
examples in the original file for training, and “xxx-scale-test-indices.txt” contains the indices of
examples in the original file for testing.
– Use the 5-fold cross validation method to decide the best value of the parameter C. The
candidate values for C are 0.1, 1, 10, 100, 1000. For each C, report the training error and
validation error. Choose the best C that yields the lowest validation error.
– Use the selected best C value to train a logistic regression model on the whole training
data and evaluate and report its performance (by error rate) on the testing data.
1
– Report the results on the two data sets.
Note: To train a regularized logistic regression by liblinear library, you can use the option “-s
0”.
## Support Vector Machine
• Repeat the same experiments as in Problem 1 by using linear SVM. To train a linear SVM by
liblinear you can use the option “-s 3”.
• Repeat the same experiments as in Problem 1 by using kernel SVM. To train a kernel SVM by
libsvm you can use the option “-s 0”. Use the optional “-t ” to choose different types of kernels.
Try polynomial kernel and RBF kernel with default values of parameters.
• Compare the test error given by Logistic Regression, Linear SVM and Kernel SVMs.
