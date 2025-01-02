# Day---7-Plant-leaf-Iris-detection-using-DECISION-TREE
I have taken a challenge to make project on every algorithm of Machine Learning. [Day - 7 | Plant leaf Iris detection using DECISION TREE]

Project Overview
This project focuses on detecting and classifying plant leaves, specifically the Iris plant species, using the Decision Tree classifier. The Iris dataset is a popular machine learning dataset consisting of various features such as petal length, petal width, sepal length, and sepal width, which are used to classify different Iris species. By applying the Decision Tree algorithm, we aim to build a model that can predict the species of an Iris plant based on these features.

Key Objectives
Preprocess the Iris dataset: Clean the data, handle missing values, and prepare the dataset for training.
Build a Decision Tree Classifier: Train a Decision Tree model to classify the Iris plant species.
Evaluate Model Performance: Measure the accuracy of the classifier and evaluate its performance using metrics like accuracy, confusion matrix, and classification report.
Predict New Data: Use the trained model to predict the species of new Iris plants based on their features.
Algorithm: Decision Tree Classifier
The Decision Tree is a supervised learning algorithm used for classification and regression tasks. It works by recursively splitting the dataset based on the feature that provides the best separation, creating a tree-like structure.

Splitting: The Decision Tree splits the data at each node based on the feature that reduces uncertainty (measured by metrics such as Gini Impurity or Information Gain).
Leaf Nodes: The leaf nodes represent the predicted class (Iris species in this case).
Overfitting: Decision Trees are prone to overfitting if the tree is too deep. This project applies pruning techniques to avoid overfitting.
