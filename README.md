# CAE
In this notebook I've used Convolutional Autoencoders to denoise image MNIST data, as well as used simple CNN for classification.

Firstly the noise has been added to the image data and then it has been reconstructed by using CEA.
CNN achieved the accuracy of 0,99.

The image data from MNIST before and after adding the noise looks as shown below

![](images/Added%20noise.png)

The architecture of Convolutional Autoencoders look like shown below. It contains encoder and decoder parts with 3 convolutional layers per each.

![](images/cae.png)
