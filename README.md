# CNN-compare-with-ANN
Accuracy Comparsion of Simple Neural Network with Convolutional Neural Networks  on Mnist Handwritten Digit Dataset
Use CNN to do handwritten digits classification using MNIST dataset.Check how accuracy improves fast with CNN and figure out how CNN can be a better choice for doing image classification compared to ANN.
CNN vs. ANN Comparison on MNIST Dataset

## CNN vs. ANN Comparison on MNIST Dataset

### Overview

This repository explores and compares the performance of Convolutional Neural Networks (CNNs) and Artificial Neural Networks (ANNs) on the MNIST dataset. The implemented code utilizes TensorFlow and Keras for the analysis.

### Content

#### Loading and Preprocessing:

The MNIST dataset is loaded and normalized to ensure pixel values range from 0 to 1.

#### Artificial Neural Network (ANN):

A simple ANN architecture is created with flattened input images and multiple dense layers having varying units and activation functions. The model is compiled using the Adam optimizer and sparse categorical crossentropy loss. Training and evaluation of the ANN on the MNIST dataset are performed, and classification reports are generated.

#### Convolutional Neural Network (CNN):

A CNN architecture is implemented with convolutional and pooling layers. The CNN is compiled and trained using the same MNIST dataset. Evaluation and prediction using the CNN model are conducted, and a classification report is generated.

### Results of Neural Networks

#### ANN Performance:

- Achieved an accuracy of approximately 97.94% on the test set.
- Detailed classification report includes precision, recall, and F1-score for each class.

#### CNN Performance:

- Achieved an accuracy of approximately 99.09% on the test set.
- The CNN model demonstrates improved performance over the ANN, capturing spatial dependencies in the images.

### Usage

To run the code, ensure that TensorFlow and other dependencies are installed. The notebook provides step-by-step explanations and can be easily customized for further experimentation.
