# Predict the age of sea slugs using KNN
Predict the age of sea slugs using KNN implemetationby pure python vs by Scikit-Learn liberary
### Introduction
The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.It simply predicts a new sample using the K-closest samples from the training set depends on how the user defines distance between samples.

### Advantages of KNN
* The algorithm is simple and easy to implement.
* There’s no need to build a model, tune several parameters, or make additional assumptions.
* The algorithm is versatile. It can be used for classification, regression, and search (as we will see in the next section).

### Disadvantages of KNN
* The algorithm gets significantly slower as the number of examples and/or predictors/independent variables increase.
* kNN is less likely to perform well on advanced tasks like computer vision and natural language processing.

## Tools

* Python 3.
* Python basic modeules math and collections.
* NumPy Library (1.18.5).
* Pandas Library (1.3.3).
* Matplotlib Library (3.3.2).
* Seaborn Library.
* Sklearn Library (1.0.1).
* Jupter Lab (3.2.5).
* Visual studio.

### Problem Specification
The age of an abalone can be found by cutting its shell and counting the number of rings on the shell. In the Abalone Dataset, you can find the age measurements of a large number of abalones along with a lot of other physical measurements.

The goal of the project is to develop a model that can predict the age of an abalone based purely on the other physical measurements. This would allow researchers to estimate the abalone’s age without having to cut its shell and count the rings.

### Importing the Abalone Dataset
In this tutorial, you’ll work with the **Abalone Dataset** [2]. You could download it and use pandas to import the data into Python.

### Implementation of KNN steps
1. Load the data
2. Initialize K to your chosen number of neighbors
3. For each example in the data
  * Calculate the distance between the query example and the current example from the data.
  * Add the distance and the index of the example to an ordered collection
4. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances
5. Pick the first K entries from the sorted collection
6. Get the labels of the selected K entries
7. If regression, return the mean of the K labels
8. If classification, return the mode of the K labels

### Notebook Steps
1. Code the kNN algorithm from scratch in NumPy
2. Use the scikit-learn implementation to fit a kNN with a minimal amount of code
3. Use GridSearchCV to find the best kNN hyperparameters
4. ush kNN to its maximum performance using bagging

## REFRENCES
</center>

[1] [Applied Predictive Modeling book](https://www.amazon.com/Applied-Predictive-Modeling-Max-Kuhn/dp/1461468485)
[2] [Abalone Dataset](https://archive.ics.uci.edu/ml/datasets/abalone)
[3] [The k-Nearest Neighbors (kNN) Algorithm in Python](https://realpython.com/knn-python/)

**Note:**
> For more details see the project explination from [here]().
