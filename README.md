# crc-cnn

This repository is mainly for project I have done under my Thesis Undegraduate.

## Overview
Cancer is the leading cause of death worldwide. Colorectal cancer is the second most common cause of death from cancer after lung cancer. The most common type of colorectal cancer is adenocarcinoma. This study classifies the types of colorectal adenocarcinoma and benign tissue cancer using the Convolutional Neural Network (CNN) architecture DenseNet121, DenseNet169, and DenseNet201 with the optimizer AdaGrad, SGD, RMSprop, and Adam. The dataset used consists of 5000 images per class each. Dataset divided into training data and testing data with a ratio of 8:2, then augmentation is performed on the training data up to 8000 images per class. The use of the RMSprop and Adam optimizers has the best accuracy on all DenseNet architectures used, which is 100%. Meanwhile, the lowest accuracy was tested with DenseNet169 with the SGD optimizer, which was 98.95%.

## Dataset
The used dataset is the LC25000 dataset which includes 5000 histopathological images of adenocarcinoma class and benign tissue class http://arxiv.org/abs/1912.12142. which can accessed on kaggle https://www.kaggle.com/andrewmvd/lung-and-colon-cancer-histopathological-images

