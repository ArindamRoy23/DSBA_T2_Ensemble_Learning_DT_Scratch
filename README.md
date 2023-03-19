# DSBA_T2_Ensemble_Learning_DT_Scratch

This GitHub repository contains the code for implementing decision trees from scratch and then using them for ensemble learning in Python.

## Introduction
Decision trees are a popular machine learning technique for solving classification and regression problems. In this repository, we have implemented the decision tree algorithm from scratch using Python. We have also implemented ensemble learning using the decision trees to improve the accuracy of our model.

## Installation
To use the code in this repository, you need to have Python installed on your system. You can download and install Python from the official website: https://www.python.org/downloads/

Once you have Python installed, you can clone this repository using the following command:
git clone https://github.com/ArindamRoy23/DSBA_T2_Ensemble_Learning_DT_Scratch.git


## Usage
After cloning the repository, you can run the code by navigating to the directory where the code is stored and running the following command:
python test.py


# Classifiaction-Tree-from-Scratch

Classification Tree from Scratch: Build and train a Decision Tree for classifiaction tasks.

## Classes:
Classification Tree: binary classification tree object
Node: node object

## Attributes:
1. max_depth: max depth of the tree (stop criterion)
2. min_samples_leaf: minimum number of samples per lieaf  (stop criterion)
3. min_samples_split: minimum number of samples to split a node (not leaves, also a stop criterion)
4. n_classes_: number of classes in training set 
5. n_features_: number of features in training set and test set
6. n_samples_: number of samples
7. criterion: criterion to split a node. Chosen from "gini", "crossentropy" and "misclassification_error"
8. tree_: tree class

## Methods:
1. __init__(max_depth, min_samples_leaf, min_samples_split, criterion = "gini"): constructor, build a Classifiactiopn Tree class
2. fit(X,y): fit the training set data
3. predict(X): predict classes for test data using trained parameters
4. predict_probability(X): predict probabilities for test data
5. acc_score: print the accuracy score of the tree model

# Regression tree from scratch
This is an implementation of the Decision Tree Regressor algorithm in Python. The Decision Tree Regressor is a machine learning algorithm that creates a decision tree model for regression problems.

The class DecisionTreeRegressor contains several methods to build and train the decision tree. The constructor method __init__ sets the maximum depth of the tree and the minimum number of samples required to split. The fit method fits the data to the decision tree, and the tree_build method builds the decision tree recursively.

The best_split method finds the best feature and threshold for splitting the data based on the mean squared error cost function. The meansqerror method calculates the mean squared error of the data.

Note that this implementation does not handle categorical data. This can be a future scope of improvement.


# Project Contributors:

Arindam Roy, Chara Vega Brown, Jiayi Wu, Taolue CHEN, Marouan Jouaidi
