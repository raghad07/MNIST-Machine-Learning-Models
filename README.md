# MNIST-Machine-Learning-Models
# Code Description
This repository contains the code for implementing and evaluating different machine learning models on the MNIST dataset. The goal is to achieve a testing accuracy of 95% and a loss of 0.1. The code includes the following components:

# Data Preprocessing: 
The MNIST dataset is loaded using TensorFlow's built-in dataset module. The pixel values of the images are normalized to a range between 0 and 1, and the labels are one-hot encoded.

# K-Nearest Neighbors (KNN):
 A KNN classifier is trained on the training data. The model predicts the digit labels for the test data, and accuracy is calculated using the metrics.accuracy_score function. The precision, recall, and confusion matrix are also calculated.

# Support Vector Machine (SVM): 
An SVM classifier with a linear kernel is trained on the training data. The model predicts the digit labels for the test data, and accuracy is calculated using the metrics.accuracy_score function. Precision, recall, and the confusion matrix are also calculated.

# Decision Tree: 
A decision tree classifier is trained on the training data. The model predicts the digit labels for the test data, and accuracy is calculated using the metrics.accuracy_score function. Precision, recall, and the confusion matrix are also calculated.

# Deep Neural Network (DNN):
 A DNN model is implemented using TensorFlow's Sequential API. The model architecture consists of several dense layers with dropout regularization. The model is trained on the training data for 40 epochs, and accuracy and loss are monitored during training. The model is evaluated on the validation data. The loss and validation loss values are plotted using matplotlib. Finally, accuracy, precision, recall, and the confusion matrix are calculated for the test data.

Choosing the Best Model: Based on the evaluation metrics (accuracy, precision, recall, and loss), the best model is selected.
