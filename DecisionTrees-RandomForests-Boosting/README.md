# DecisionTrees-RandomForests-Boosting

This task involves implementing Decision Trees, Random Forests, and Boosting algorithms and evaluating their performance on the Titanic dataset.

## Decision Trees

Creating a `DecisionTree` class with `fit` and `predict` methods. The class accepts parameters such as criterion, max_depth, min_samples_split, and min_samples_leaf.

## Random Forests

Creating a `RandomForest` class that takes a classifier object, num_trees, and min_features as input. Utilizing sampling with replacement and selecting random subsets of features when splitting. Implementing `fit` and `predict` methods for training and inference.

## Boosting

Creating an AdaBoost algorithm in a `AdaBoost` class, which takes a weak learner, num_learners, and learning_rate as input parameters. The `predict` method computes class predictions based on a weighted sum of weak learners' predictions.

## Evaluation

Evaluating the performance of each algorithm on the Titanic dataset by training them on a training set and evaluating their classification performance on a test set.
