# Disease Prediction Model

## Decision tree
The first model is decision tree with no. of parameters = 132.
With this model I got accuracy score of 1.0, but the decision tree structure is pretty big so use any other method to achieve accuracy.

## Neural Network
Second model is neural network with 1 hidden layer
I have used categorical_crossentropy and softmax as activation function for last layer.
In around 20 epochs I got loss value in range of 1e-6 and accuracy 1.0.
I have tested this model on test data reserved for testing (35% reserved not included in validation).
The model output is one hot encoded as there are total 41 types of disease from which output should be predicted.
At last I have trained another model with Cross Validation function using wraper(Again got 1.0 accuracy).
=======

