# Research on CNNs

This folder contains my work on **Convolution Neural Networks**.

# MNIST

MNIST is the most classical task that is given to learn about convolutions.
My [solution](mnist.ipynb) of this task with modified LeNet performs on the level of 98% accuracy.

# Classification

I tried to use CNNs in the task of classification. However, I decided to use them in different contexts.

This [file](few_shot_classification.ipynb) solves binary classification, but with a twist - train dataset is very small.
Heavy usage of augmentations and self-supervised learning allowed me to get 96% accuracy.

This [file](multiclass_classification.ipynb) solves multiclass classification of butterflies with EfficientNet.

This [file](video_classification.ipynb) tries to solve multilabel classification of video while not using
models that work with sequences - just with CNN.
Extraction of frames from video and classifier built on top of YOLO do that easily.
