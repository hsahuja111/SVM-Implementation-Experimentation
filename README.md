# Implementation And Experimentation on SVM

This repository contains a jupyter file named SVM.ipynb which contains the code for the SVM implementation along with various visualization and experimentation.


### There are 2 subsections and both are highlighted in the jupyter notebook.

## Subsection 1

### Tasks
1. Implementation of Hard Classification SVM
2. Implementation of Soft Classification SVM
3. Adding new points and see changes in Decision Boundary
4. Removing the Support Vectors Data points and Visualize 

Here, we are taking some sythentic data and trying to find the decision boundary using 2 types of classification -- Hard Classification and Soft Classification

#### To understand briefly , Hard Classification does not allow any misclassifications however the soft classification acknowledges the misclassifications.

* This has been implemented without use of any sklearn library.
* CVXPY library has been used here for solving the optimization problems.

CVXPY demands the objective i.e the SVM equation that we want to minimise and the contraints.

#### Note: Hard and Soft Classification will have different objective function and contraints.

After solving we get the optimal values of the Weight vector and using which we get Decison Boundary.
From Decision Boundary we calculate the support Vectors by simply doing +1 and -1

Several tweaks have been made in terms of data points and changing the C parameter to see how the decision boundary is impacted

## Subsection 2

### Tasks
1. Sklearn Implemented SVM on MNIST dataset
2. Changing the parameters and reporiting the scores

Here, we have taken a famous MNIST data and used sklearn implemented SVM to visulize the support vectors and decision boundary by changing the parameters. Various scores have been reported based upon that.

### Comments for each step are added in Jupyter Notebook which will help to understand it better

