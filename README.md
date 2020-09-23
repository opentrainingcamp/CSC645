# Neural Networks

This course introduces Neural Network for Machine Learning. It is meant to be a hands-on
course without sacrificing the conceptual background. As such the first few code examples are developed (using numpy or cupy) from basic principles without using any ML framework. After that we use Tensorflow v2 for almost all examples.

## Already done

Below are already done (the code) but need (a lot of) polishing. Especially integrating the lecture with the code.
1. Introduction
1. Logistic Regression: basic concepts, perceptron, activation function, loss and trainning. Two different applications: one using CIFAR10 data set  and the second using  **sentiment analysis** in Tweets
1. Neural Network with a single layer: a single hidden layer, backpropagation example, training using gradient descent. Using a generate data set
1. The same example as the previous but using Tensorflow low level API (as opposed to Keras) automatic differentiation.
1. Feedforward Networks: design of a feedforward network with an arbitrary number of layers and backpropagation from first principles using numpy (cupy) with no framework used. Application to MNIST data set
1. Same as the above but using the high level Keras API in tensorflow
1. Convolution Networks using Keras. Application to CIFAR10 data set

## coming soon

1. Recurrent Neural Networks: using RNN in Tensorflow to detect spam messages  
1. Autoencoder.

<img src="figures/gradient-descent.png" />
