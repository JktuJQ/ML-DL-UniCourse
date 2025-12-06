# Research on ensemble methods

This folder contains my work on **ensemble methods**.

## Decision Tree from scratch

Since I would implement ensemble methods upon Decision Trees,
I have decided to just build it myself!

You can see that implementation in this [file](decision_tree.ipynb);
results are visualized.

My implementation also includes several stop conditions and
support for random feature selection.
All of that would come in handy when I will use those trees in ensemble methods.

## Random forest

I have implemented classifying Random Forest that is built upon decision trees.

You can see that implementation in this [file](random_forest.ipynb);
results are visualized and tested on rather hard example.

My implementation of Decision Tree does all the work -
Random Forest is just a wrapper of those.
