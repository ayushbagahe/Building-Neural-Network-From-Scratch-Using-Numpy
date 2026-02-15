## Neural-Network-From-Scratch-Using-Numpy
## Introduction
This is a weekend project of making neural network from scratch using numpy library in python.


## What is Neuron
![Image](https://github.com/ayushbagahe/Building-Neural-Network-From-Scratch-Using-Numpy/blob/main/artificial_neuron_apple_style%20(1)%20(1).png)

## 01 INPUTS
(x₁, x₂, ..., xₙ) These are the data values fed into the neuron. Each input represents a feature or piece of information.
For example, if you're building a model to predict house prices, inputs might be: square footage, number of
bedrooms, location score, etc

## 02 Weights
(w₁, w₂,...,wₙ) Each input has an associated weight that determines its importance. Weights are learned during training
and control how much each input influences the final output. Think of weights as dials that the network adjusts to
make better predictions. Higher weights mean that input has more influence

## 03. Summation Function (Σ) 
The neuron combines all inputs with their weights using a weighted sum:
z = (w₁×x₁) + (w₂×x₂) + ... + (wₙ×xₙ) + b
This is essentially a dot product of the input vector and weight vector, plus the bias

## 04 Activation Function
(w₁, w₂,...,wₙ) Each input has an associated weight that determines its importance. Weights are learned during training
and control how much each input influences the final output. Think of weights as dials that the network adjusts to
make better predictions. Higher weights mean that input has more influence

## 05  Output (y)
This is the final value produced by the neuron after applying the activation function to the weighted sum. The
output becomes either the final prediction or an input to neurons in the next layer


## Forward Propogation
![Image](https://github.com/ayushbagahe/Building-Neural-Network-From-Scratch-Using-Numpy/blob/main/forward_propagation.png)

## What are Neural Network
