# Fashion MNIST classification: Project Overview

**Tags: neural network, keras, tensorflow, relu, softmax, adam, sparse categorical cross-entropy, backpropagation, dropout, EDA, image classification**

This notebook is based on Alura's course [Deep Learning parte 1: Keras](https://cursos.alura.com.br/course/deep-learning-introducao-com-keras) (Deep Learning Part 1: Keras) by Cássia Sampaio.

The main project steps were:

- visualizing image samples
- mapping the labels and pieces of clothes
- normalizing the images
- creating a neural network model with one hidden layer.

## Code and resources

Platform: Google Colab

Python version: 3.7.15

Packages: Keras, Matplotlib, Numpy, TensorFlow

## Data set

The fashion MNIST data set is available in the Keras library but also you can access it from [Github](https://github.com/zalandoresearch/fashion-mnist).
It contains 60000 and 10000 28x28 grayscale images of 10 fashion categories divided into training and test sets respectively.
The categories are:
|Label|Description|
|-----|-----------|
|0|T-shirt/top|
|1|Trouser|
|2|Pullover|
|3|Dress|
|4|Coat|
|5|Sandal|
|6|Shirt|
|7|Sneaker|
|8|Bag|
|9|Ankle boot|

## Model building

- Build a NN model with three layers, input, output, and one hidden layer.
- The images were flattened for the input layer.
- The hidden layer used the ReLU activation function with 20% of dropout.
- The output layer used the softmax function.

## Model performance

The scores were:
- evaluation loss of 0.34 approximately;
- evaluation accuracy of 0.87.
