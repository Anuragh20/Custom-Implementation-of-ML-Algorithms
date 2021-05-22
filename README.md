# Custom-Implementation-of-ML-Algorithms

**Summary:**
This folder contains the custom implementation of various machine learning algorithms with the use of any of the popular libraries such as Scikit Learn etc.
Objective of the Activity:
To deconstruct the inner workings of a Machine Learning Algorithm in order to achieve the following:
1.	Understand the overall flow of the data during the Training Phase
2.	Evaluate the Space and Time complexity of the algorithm during the Training and the Testing phases
3.	Identify the Boundary cases of the algorithm and figure out the weakness, the areas where the algorithm could fail
4.	Better understand the actual math behind the inner workings
5.	Ability to recreate the algorithm in cases where the traditional libraries such as Scikit Learn fail to scale up when the size of the data set is huge

**Contents:**
1.	FILE 1: TFIDF Vectorizer
    a.	Custom Implementation of TFIDF Vectorizer and comparison of the results with data on SKLearn TFIDF vectorizer
    b.	Implementation of max features functionality. As a part of this task, we modify the fit and transform functions so that vocab will contain only 50 terms with top idf scores

2.	 FILE 2: Implementation of SGD Classifier with LogLoss
    a.	The goal of the task is to compare the values of the weights and the intercepts obtained through the Custom implementation and the SKlearn implementation and make the        difference as small as possible

3.	File 3: Implementation of Random Forests 
    a.	Implement Random Forests and evaluate the performance of the implementation on Train and OOB data for Boston Housing Data
