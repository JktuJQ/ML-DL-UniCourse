# Research on Logistic Regression model

This folder contains my work on **Logistic Regression** model.

## Logistic Regression from scratch

To fully understand anything, you just have to build it yourself!

Fortunately, Logistic Regression model is fairly simple -
it is just a linear regression model whose results are clamped into $ [0, 1] $ range
by sigmoid function.

You can see that implementation in this [file](model_from_scratch.ipynb);
results are visualized.

## Logistic Regression contest

To further consolidate knowledge,
I have decided to participate in this [Kaggle contest](https://www.kaggle.com/competitions/classification-of-oil-and-gas).

My research of the dataset and example of applying `sklearn` `LogisticRegression` model.
is in this [file](contest.ipynb).
I have experimented with One-Hot encoding of categorial features.

My best F1-score: `0.85397`.
