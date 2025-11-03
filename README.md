# MNIST_Dataset_Example
This project demostrates the MNIST dataset which contains a large collection of handwritten digits used to train a neural network while utilizing TensorFlow + Keras. The goal is for demostration of image classification. 
# Table Of Contents
- [Implementation](#implementation)
- [Requirements](#requirments)
- [How to Use](#how-to-use)
- [Error Handling](#error-handling)
- [References](#references)
# Implementation
The models implementation consists of an input of the MNIST dataset in which it involves a collection of 70,000 handwritten digits (0-9), with each image being 28x28 pixels. The model is trained using 25 EPOCHs in which it is passed through 25 times, with a validation split of 0.2 to prevent overfitting and validates on a specific portion of the data. 
# Requirments 
This project requires tensorflow, keras, and scikit-learn. It was developed using a Python environment through VSCode.

Use 'pip install -r requirements.txt' to install the following dependencies:

```
absl-py==2.3.1
astunparse==1.6.3
certifi==2025.8.3
charset-normalizer==3.4.3
flatbuffers==25.2.10
gast==0.6.0
google-pasta==0.2.0
grpcio==1.74.0
h5py==3.14.0
idna==3.10
joblib==1.5.2
keras==3.11.3
libclang==18.1.1
Markdown==3.9
markdown-it-py==4.0.0
MarkupSafe==3.0.2
mdurl==0.1.2
ml_dtypes==0.5.3
namex==0.1.0
numpy==2.3.3
opt_einsum==3.4.0
optree==0.17.0
packaging==25.0
pillow==11.3.0
protobuf==6.32.0
Pygments==2.19.2
requests==2.32.5
rich==14.1.0
scikit-learn==1.7.2
scipy==1.16.1
setuptools==80.9.0
six==1.17.0
tensorboard==2.20.0
tensorboard-data-server==0.7.2
tensorflow==2.20.0
termcolor==3.1.0
threadpoolctl==3.6.0
typing_extensions==4.15.0
urllib3==2.5.0
Werkzeug==3.1.3
wheel==0.45.1
wrapt==1.17.3
```
# How to Use
To utilize this code, a Python environment is installed. Download the MNIST.py file onto your computer into a folder. Then open that folder/file on VSCode. 

# References 
[1]GeeksforGeeks, “MNIST Dataset : Practical Applications Using Keras and PyTorch,” GeeksforGeeks, May 2024. https://www.geeksforgeeks.org/machine-learning/mnist-dataset/
‌
