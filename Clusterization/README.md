# Research on clusterization methods

This folder contains my work on **ensemble methods**.

## Clusterization contest

I have found a rather interesting clusterization
[task](https://www.kaggle.com/competitions/scintillation-detector),
where I would need to separate two types of particles.

Extensive [description](description.pdf) was very helpful in my research
and the whole task presented several challenges that I could test
my skills on.

My best metric - `0.85199`;
it was obtained by separating PSD values on `0.37` (constant that I found during Grid Search).

Although actual clusterization methods performed pretty badly on the task,
they were still useful in finding approximation of threshold for PSD value separation.

You can find my whole research in this [file](contest.ipynb).
