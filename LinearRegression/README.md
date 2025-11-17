# Research on Linear Regression model

This folder contains my work on **Linear Regression** model.

## Linear Regression from scratch

To fully understand anything, you just have to build it yourself!

Fortunately, Linear Regression model is fairly simple -
it is just a line equation which coefficients are optimized with gradient descent.

I have implemented this model for the case, where there is only one feature and only one target.
That fairly simplifies everything, because I don't need to implement matrix differentiation.

You can see that implementation in this [file](model_from_scratch.ipynb);
results are visualized and compared to analytical solution.

## Linear Regression contest

To further consolidate knowledge,
I have decided to participate in this [Kaggle contest](https://www.kaggle.com/competitions/games-rating/).

My research of the dataset and concrete implementation of linear regression in PyTorch
is in this [file](contest.ipynb).
I have experimented with One-Hot encoding of categorial features, regularization and PyTorch in general.

My best MSE: `0.27572`.
