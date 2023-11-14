
# Leaf Classification using Neural Network (MLP)


This project aims to classify leaf species using a Neural Network architecture. The Leaf Classification dataset is used to train and evaluate the model. The neural network model is implemented using the Keras library with TensorFlow backend.

## Data Description:


The dataset has been loaded and cleaned.
It contains features related to leaf characteristics.


## Data Splitting:


The dataset has been divided into training and validation sets.

Training set: 80%

Validation set: 20%


## Standardization:



Standardization of features has been performed on the data.
Mean and standard deviation for each feature dimension have been computed using the training set.
Each feature and sample have been standardized by subtracting the mean and dividing by the standard deviation.


## Label Encoding:


Labels have been encoded for the classification task.


## Training a Neural Network


The implemented neural network is a 3-layer Multi-Layer Perceptron (MLP) with:


Input layer

Hidden layer with tanh activation

Output layer with softmax activation

## Hyperparameters Explored:

Neurons in Hidden Layer

512, 700, 3000, 600, 1092, 800, 1000, 1024

L2 Regularization

0.1, 0.01, 0.0001

Dropout Rate

0.6, 0.7, 0.5, 0.4

Optimizers

Adam, SGD, RMSprop

Epochs

Ranges from 20 to 200

Batch Size

Ranges from 16 to 128

Learning Rate

Explored different learning rates (0.01, 0.001, 0.1)

Learning Rate Scheduler

Implemented Learning Rate Scheduler after a certain number of epochs


## Results:


The model performances have been evaluated based on accuracy and loss metrics on the validation set.


