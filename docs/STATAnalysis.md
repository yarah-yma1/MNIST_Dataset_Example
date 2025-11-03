# Statisical Analysis 
MNIST dataset contains 60,000 training and 10,000 testing of greyscale images of handwritten digits ranging from 0 to 9. Each images the dimenions of (28,28,1) showing the width, height, and single gray scale channel. 
- The pixel values were normalized by divding 255.0 for an improvement of convergence during the training.
- The dataset is relevivly low and clean in noise in which allowed for high accruacy across models. It was espcially high in simple neural networks and CNNs.
- The model used mutliple convolution and pooling layers follwed by dense layers to classfiy the images into 10 output categories.
- The total number of trainable parameters was around 1.6 million and the model size was about 6.17 MB.
