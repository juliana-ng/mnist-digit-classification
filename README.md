# mnist-digit-classification
Deep Neural Networks are trained to classify image data from the MNIST dataset.

## Abstract
This paper explores the role of deep learning models in image data and how model performance
is affected by adjusting hyperparameters. The MNIST dataset containing 70,000 scanned images
of handwritten numbers from 0 - 9 is used in this research. The models were built using
Tensorflow and Keras, which are popular libraries commonly used in deep learning techniques
because of the simplicity and convenience. The model with 256 hidden nodes, 784 input
dimensions, and tanh activation function performs the best at an accuracy of 99.7%, 98.1%,
98.1% (training, validation, testing) and loss of 0.013, 0.068, 0.069 (training, validation, testing).

## Methods
This research is conducted using the MNIST dataset. The training dataset contains 60,000
images where 5,000 are taken as the validation dataset. The rest 10,000 images were used as the
testing dataset. The main libraries are Tensorflow (v 2.17.1), Keras (v 3.5.0), and matplotlib
libraries.

In each experiment, one hyperparameter is tweaked to find a model with the best accuracy and
loss score, and correct classification of the numbers on the images with only one hidden layer.
All experiments are run in 10 epochs instead of 30 epochs due to time constraint.

The image dataset are reshaped into vectors and the pixel values are scaled to between 0 - 1 by
dividing them by 255. The accuracy and loss for training, validation, and testing, and confusion
matrix are calculated and visualized with matplotlib.

11 models trained and compared
