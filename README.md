# Multilayer-Perceptron
I will create a multilayer perceptron whose output layer will be a one-hot encoded vector, so that we can use it for classification. It will automatically determine the size of the input and output layers, based on the data passed to it. You can also specify the hidden layer structure by passing it an array of integers, where the $i^{th}$ element is the number of nodes in the $i^{th}$ hidden layer (including the bias node). By default, it will generate one hidden layer and the number of nodes will be the average of the input and the output layer. We will implement stochastic gradient descent, mostly for the sake of code simplicity. 
