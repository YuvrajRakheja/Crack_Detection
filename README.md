# Crack_Detection
Concrete-Crack-Detection-Segmentation
This repository contains the code for crack detection in concrete surfaces. It is a PyTorch implementation of the paper by Young-Jin Cha and Wooram Choi - "Deep Learning-Based Crack Damage Detection Using Convolutional Neural Networks"

The model acheived 98% accuracy on the validation set.
Dependencies required:

PyTorch, OpenCV, Dataset -The data set can be downloaded from this link: https://data.mendeley.com/datasets/5y9wdsg2zt/2

The dataset file creates the training dataset class to be fed into the Convolutional Neural Network. This class automatically determines the number of classes by the number of folders in 'in_dir' (number of folders=number of classes)
