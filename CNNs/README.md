# Research on CNNs

This folder contains my work on **Convolution Neural Networks**.

## MNIST

[MNIST](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) is the most classical task that is given to learn about convolutions.
My [solution](mnist.ipynb) of this task with modified LeNet performs on the level of 98% accuracy.

## Classification

I tried to use CNNs in the task of classification. However, I decided to use them in different contexts.

This [file](few_shot_classification.ipynb) solves binary classification, but with a twist - train dataset is very small.
Heavy usage of augmentations and self-supervised learning allowed me to get `96%` accuracy.
You can find contest by this [link](https://www.kaggle.com/competitions/platesv2).

This [file](multiclass_classification.ipynb) solves [contest](https://www.kaggle.com/competitions/classification-of-butterflies) on multiclass classification of butterflies with EfficientNet.

This [file](video_classification.ipynb) tries to solve multilabel classification of video while not using
models that work with sequences - just with CNN.
Extraction of frames from video and classifier built on top of YOLO do that easily.
You can find this contest [here](https://www.kaggle.com/competitions/what-on-the-video).

## Segmentation

I solved the task of semantic segmentation of the image with circles.
This [solution](segmentation.ipynb) is rather simple, but that is almost always the case with YOLO -
it makes everything extremely simple!

## Detection

Detection task that I approached is harder due to the nature of dataset -
I needed to find seagulls on images that are quite blurred and small.
However, YOLO once again does its magic - the solution is very small yet perfomant.
You can find contest by this [link](https://www.kaggle.com/competitions/find-the-seagulls).
