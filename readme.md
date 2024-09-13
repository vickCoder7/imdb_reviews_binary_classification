**Table of Contents**

1. Setup
2. Load the IMDB dataset
3. Decode reviews back to text
4. Multi-hot encoding of the integer sequences
5. Labels' vectorization
6. Set aside a validation data
7. Build the model
8. Compile the model
9. Train the model

> **Executive summary**

In this project, I performed a binary classification on the Interned Movie Database reviews. The model was developed using keras layers, with two hidden layers, having 16 units each and 'relu' as the activation function. The output layer has only one neuron and its activation function is the sigmoid function as I am determining the probability (between 0 and 1) of a review being negative or positive.

The details of the model are as follows: 

* Optimizer: rmsprop
* Loss: Binary crossentropy
* Metrics: Accuracy

Reference: *Deep Learning with Python*, François Chollet
