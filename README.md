# Handwritten-Character-Classifier-ML
My take on the standard neural network task of constructing a classifier of handwritten characters 
Data obtained from: https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format

Network achieves a 98-99% accuracy on both training and validation data.

Dataset contains 372450 examples of 28x28 (784) pixel images.

Algorithm parameters: 
- Applies a MinMax scaler to the dataset
- Applies same convolution with 32 filters onto input images
- Relu activation function
- MaxPools with 2x2 resolution
- 30% dropout used for reguralization
