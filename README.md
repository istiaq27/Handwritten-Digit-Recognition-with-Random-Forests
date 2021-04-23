# Handwritten-Digit-Recognition-with-Random-Forests algorithm

In this project we are developing such a system that includes a machine to understand and classify the images of handwritten digits as 10 digits (0–9). Handwritten digits from the MNIST database are already famous among the community for many decades now, as decreasing the error rate with different classifiers and parameters. We will train a Random Forest classifier on the MNIST dataset to perform handwriting recognition of digits on images of 28x28 resolution. The classifier predicts the handwritten digit in the image and returns the result as a number from 0 to 9.

This work shows how random forests can be used to learn a model to classify and predict handwritten digits. First, the 28x28 greyscale images of handwritten digits are imported as a vector of length 784 with values between 0 and 255. The training data also contains their labels (the number it displays). Then, the random forest classifier is learnt and applied to the test data.
# Data Set
The data set is taken from the respective kaggle.com challenge, and you can find it from [here:](https://www.kaggle.com/c/digit-recognizer/data)
