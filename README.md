# Digit_recognizer(Through-Scratch)
Objective of this work is to build a model through scratch for digit recognizer. This code helps to understand how deep neural network works.

This code consists of 4 blocks

1)Initilizing Weights

2)Forward Propagation

3)Backward Propagation
### Initializing Weights
W- weights have a dimension of (size of layer l, size of layerl-1)

b - bias have a dimension of (size of layer 1,1)
### Forward Propagation
Using the given input X, weights W, and biases b, for every layer we compute a linear combination of inputs and weights (Z)and then apply activation function to linear combination (A). At the final layer, we compute f(A(l-1)) which could be a sigmoid (for binary classification problem), softmax (for multi-class classification problem), and this gives the prediction y^.
### Backward Propagation
 In backpropagation, we find the gradients of the loss function, which is a function of y and y_hat, and gradients wrt A, W, and b called dA, dW, and db. By using these gradients, we update the values of the parameters from the last layer to the first layer.
