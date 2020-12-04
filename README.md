# Facial_expression_detection
Machine Learning models to predict the expression of an image 

This Major Project was compiled as a part of Machine Learning unit in the Master of Data Science course at Macquarie University. 
A kaggle competition was conducted through the semester on two different data sets. Public dataset can be found at https://www.kaggle.com/c/facial-expression-recognition/data
and the private dataset was available in a window of 24 hours. The main idea behind this project was to build a conventional and a deep learning model for the prediction.

For Conventional Machine Learning models various models were tested and one with the best accuracy(54%) found was Random Forest using Stratified Shuffle Split on the dataset. 
Performance of this model with various hyperparameters was evaluated. Also only stratified split on the data was tried and was found to be less suitable for achieving good performance.
Other convetional machine learning models tried were SVM and decision tree.

For Deep Learning Models a conventioanl CNN and DeXpression model was tried. The conventional CNN model included four layer each containing a convolution layer followed by
pooling layer followed by Batch normalization and a dropout layer. The model was tuned using hyperparameters such as classifiers- SGD v/s Adam, different learning rates.
Model was compiled along with checkpoint and accuracy of 60% was achieved. Also the DeXpression model presented in https://arxiv.org/pdf/1509.05371.pdf paper with some 
alterations and the accuracy was obtained of 44%. The input data has a size of 224 * 224 for this model so the data was resized and the model was applied on it.

This project gave an opportunity to learn in depth of the working of a machine learning model and how to select parameters to achieve the best model.
