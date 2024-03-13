# Happy Face Detection using Convolutional Neural Network (CNN)

This repository contains a Python script for training and evaluating a Convolutional Neural Network (CNN) model to detect whether a person in an image is happy or not. The script utilizes TensorFlow and Keras libraries for building and training the model.

# Prerequisites
- Python 3.x
- TensorFlow
- Keras
- h5py
- numpy
- matplotlib

# Script Overview

- Load the training and testing datasets from HDF5 files.
- Normalize the image vectors and reshape the label vectors.
- Build a CNN model using TensorFlow and Keras.
- Compile the model using binary cross-entropy loss and both RMSProp and Adam optimizers.
- Train the models on the training dataset.
- Plot the training history (accuracy and loss) for both optimizers.
- Evaluate both models on the testing dataset.
- Display the test accuracy and loss for both optimizers.
- Let the best optimizer run for longer and evalute results.


