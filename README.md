# Algorithms from Scratch
Welcome to the Algorithms from Scratch repository!This repository contains my end-to-end implementations of core machine learning algorithms, built without relying on high-level ML libraries like scikit-learn. My primary goal was to break down each algorithm into its core mathematical components, gain true intuition behind the logic, and strengthen my understanding through hands-on code and visualizations.

## Implemented Algorithms
Here are the algorithms I have implemented so far:
- Linear Regression: Implemented from scratch to understand the working of regression models and their optimization.
- Logistic Regression: Built a Binary Classifier using Logistic Regression, including the use of the sigmoid function, log loss function, gradient descent, and performance metrics like accuracy, precisiom , confusion matrix , recall and F1-score.
- Decision Tree Classifier : I implemented a simple decision tree classifier implemented from scratch where I computed the Gini index to evaluate split equality, created a recursive function to split the data based on the most informative feature and built a binary tree structure that learns to classify based on feature thresholds. This implementation deepened my understanding of information gain, overfitting, and tree-based logic. 
- Regression Tree Classifier : Here I built a Regression Tree, closely related to decision trees but focused on minimizing variance instead of Gini or Entropy. I used the mean squared error in each split to decide where to break. I have also compared this model against Linear Regression to understand when linearity fails and how trees capture non-linear patterns in data. 
- Random Forest : In this mini project I am trying to built my own Random Forest from scratch and visualize how trees work together to improve accuracy and reduce overfitting.I have also compared the performance of Random Forest and a Single decision tree classifier to understand how random forests handle overfitting issues and achieve low bias low variance goal which cannot be achieved using any other algorithms I have studied until now. 

## Technologies Used
- Python: The algorithms are implemented in Python.
- NumPy: For numerical computations, especially in linear regression and logistic regression implementations.
- Matplotlib : For Visualizations

terms

💡 Why I Did This
As an aspiring Data Scientist, I wanted to go beyond simply importing models. These projects helped me a lot to understand how ML algorithms work internally. What is the intuition and mathematics behind the algorithm and to also build a deeper foundation to confidently tackle real-world projects and interviews. 
