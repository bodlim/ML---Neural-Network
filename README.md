# ML---Neural-Network

This repository is in fulfillment of the Machine Learning Course on Coursera by Andrew Ng.

ex4.m implements the feedforward and backpropagation algorithms to learn the paramaters for a neural network system used to predict handwritten digits.

ex4data1.mat contains 5000 training examples of handwritten digits, each of which has a 20 pixel by 20 pixel grayscale image of the digit as attributes. This 20 by 20 grid of pixels is unrolled into a 400-dimensional vector. And their corresponding targeted digit is labelled as "y."

ex4weights.mats includes two parameters: theta1 and theta2. The latter is a matrix of weights controlling function mapping from the input layer to the hidden layer (there is only one hidden layer in this network). While theta2 matrix controls function mapping from the hidden layer to the output layer.
