# Multi-Class-Classification-and-Evaluation-with-SVM-Perceptron-and-K-Nearest-Neighbors
This repository contains code that demonstrates multi-class classification using Support Vector Machine (SVM), Perceptron, and K-Nearest Neighbors (KNN) algorithms. The code includes data preprocessing, model training, evaluation, and visualization of results.
### Prerequisites
-Required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
### How to Use
1- Clone or download this repository to your local machine.
2- Ensure you have the required libraries installed by running: pip install pandas numpy scikit-learn matplotlib seaborn.
3- Open the multi_class_classification.py script in your preferred Python environment.
4- Run the script to execute the multi-class classification, model training, evaluation, and visualization processes.
### Code Overview
The multi_class_classification.py script performs the following steps:
1- Imports necessary libraries for data manipulation, model training, and visualization.
2- Defines training and testing data for classification experiments.
3- Trains an SVM classifier on the training data and evaluates its performance on training and test sets.
4- Defines functions to plot confusion matrices, calculate accuracy, and visualize decision boundaries.
5- Trains Perceptron classifiers for each class using the One-vs-Rest approach.
6- Evaluates and visualizes Perceptron classifier performance.
7- Performs multi-class classification using aggregated predictions from SVM and Perceptron classifiers.
8- Optimizes KNN parameters and evaluates its performance on validation and test sets.
9- Visualizes accuracy trends for KNN.
### Results
The script generates various visualizations, including confusion matrices, decision boundaries, and accuracy curves. It provides insights into the performance of SVM, Perceptron, and KNN algorithms on multi-class classification tasks.
