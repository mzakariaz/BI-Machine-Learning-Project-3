<h1><b>BI-Machine-Learning-Project-3</b></h1>

<h2><b>Contents</b></h2>

- [**Introduction**](#introduction)
- [**Details**](#details)
- [**Credits**](#credits)

## **Introduction**
This project is my attempt at Project 3 of the Machine Learning Engineer internship at Bharat Intern. The goal is to create a machine learning model to accurately classify species of Iris flowers, using Python, particularly libraries such as scikit-learn and TensorFlow.

## **Details**
* **<u>Project Title:</u>** *Iris Classification*
* **<u>Project Description:</u>** Develop a ML Model for classifying Iris flowers based on their features using Python, scikit-learn, and TensorFlow.
* **<u>Project Submission:</u>** All of the work to be evaluated in this project can be found in the `iris-classification.ipynb` file, located in the current directory.
* **<u>Libraries Used:</u>** The following Python libraries are imported for the stated purposes:
  * `numpy`, for numerical calculations;
  * `pandas`, for data manipulation;
  * `matplotlib.pyplot`, for data visualisation;
  * `seaborn`, for data visualisation;
  * `warnings`, for warining handling;
  * `sklearn.datasets`, for loading datasets, especially through the `load_iris` module;
  * `sklearn.preprocessing`, for preprocessing data for machine learning model implementation, especially through the `StandardScaler` module;
  * `sklearn.model_selection`, for ensuring the validity of a machine learning model, especially through the `GridSearchCV`, `train_test_split` and `cross_val_score` modules;
  * `sklearn.neighbors`, for implementing the *k-nearest neighbors* classifiction model, especially through the `KNeighborsClassifier` module;
  * `sklearn.svm`, for implementing *support vector machines*, especially through the `SVC` module;
  * `sklearn.ensemble`, for implementing ensemble methods for machine learning models, especially through the `RandomForestClassifier` and `VotingClassifier` modules, and;
  * `sklearn.metrics`, for evaluating the performance of machine learning models, especially through the `accuracy_score`, `precision_score`, `recall_score` and `f1_score` modules.

## **Credits**
All of the sources (e.g. videos, images, articles) used to help build this project are cited in the links below:
- https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html
- https://scikit-learn.org/stable/modules/svm.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
- https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html