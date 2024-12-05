# Image Classification AI Model for CIFAR-10 Dataset

Dataset
  The CIFAR-10 dataset was used in this project. This dataset is highly suitable because it contains 60,000 color images of 32x32 pixels, categorized into 10 distinct   classes, including airplanes, cars, birds, etc. These small yet diverse images provide an ideal benchmark for testing and validating image classification models.

AI Model
  
  The project utilizes multiple AI architectures to evaluate performance and accuracy:
  
  1. Baseline Model: A simple neural network with two linear layers for quick evaluation.

  2. Model with non-linearity: A bit more complex neural network with several layers (2 or 3 or 4) and ReLU activation function.

  3. CNN Architecture: A convolutional neural network tailored to the CIFAR-10 dataset, using custom configurations for kernel size and stride. The architecture         incorporates two convolutional blocks followed by max-pooling layers and a fully connected classifier. I achieved the best results with a CNN model, which has        the following performance metrics: 72,72 % train accuracy, 70,58% test accuracy, 0,78 train loss and 0,86 test loss. 

Installation and Running Instructions
  
   Dependencies: Python 3.9+, PyTorch 1.13+, TorchVision 0.14+, NumPy, Matplotlib
  
   Installation: Clone the repository and install the dependencies.
  
   To run the project, simply just open the Jupyter Notebook file.
  
