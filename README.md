# Handwritten-Chasracter-Recognition
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Handwritten Character Recognition with MNIST
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Introduction
In this notebook, we will be working with the MNIST digit recognition competition dataset. We will apply a CNN model which will include some augmentation as well. In the end, we will also visualize the activations of our CNN model. Finally, we'll make our submission.
# Data-set Description

The **[MNIST Handwritten Digit Classification Dataset](http://yann.lecun.com/exdb/mnist/)** consists of 60,000 training images and 10,000 testing images of handwritten digits.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

![alt text](https://i.imgur.com/Su00XUA.png)
# Necessary Packages
Torch
Matplatlib
Seaborn
Numpy
Pandas
