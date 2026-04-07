# Research on Generative Models

This folder contains my work on **Generative Models**.

## Diffusion

Diffusion is one of the best methods of generating new images from nothing.
They work by de-noising initial image (which is all noise) in a special way
that is related to the prompt of the model.
In this [file](diffusion.ipynb) you can see my attempts at generating selfies.
I used the following approach: train only cross-attention layers,
which allows model to learn to associate some token with me;
presence of the token in the input prompt will cause model to de-noise images
in a way it tried during the training with images of myself.
