# Research on RNNs

This folder contains my work on **Recurrent Neural Networks**.

## LSTM/GRU from scratch

Many recurrent neural networks are built upon either LSTM (Long Short-Term Memory)
or GRU (Gated Recurrent Unit) cells, which help them to operate on sequences.

I have implemented those from scratch and compared them to torch's implementation
on a task that requires to classify a sequence of numbers as having positive/negative sum.
You can see results in this [file](lstm_gru_from_scratch.ipynb).

## Seq2Seq deciphering

Recurrent neural networks are frequently used for Seq2Seq tasks,
and I decided to test them on one.
The task is quite simple - model needs to learn how to decode Caesar cipher.
In case of fixed cipher shift this task does not particularly need RNNs -
it is a simple classification task that actually only requires one linear layer.

However, for sake of research, I still implemented model using LSTM layer -
due to that, the model is easily adapted to decode cipher's with unknown shifts,
but that would require huge training dataset which is based on language corpus.
You can find my results in [file](caesar_cipher.ipynb).
