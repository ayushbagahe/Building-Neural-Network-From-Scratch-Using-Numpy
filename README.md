## 01. Neural-Network-From-Scratch-Using-Numpy
## 02. Introduction
This is a weekend project of making neural network from scratch using numpy library in python.


## 03. What is Neuron
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

## 05. What are Neural Network
![image](https://github.com/ayushbagahe/Building-Neural-Network-From-Scratch-Using-Numpy/blob/main/neural_network.png)

## Explanation 
A neural network is like a team of experts working together to make a decision. Each expert focuses on a small part of the problem and passes their opinion to the next group. The first experts look at basic details, like shapes or sounds. The next group combines those details to recognize more complex patterns, like a face or a word. Finally, the last expert gives the answer, such as “That’s a cat” or “That’s a dog.” The network learns by adjusting how much each expert is listened to, improving over time with practice and feedback


## 04. Forward Propogation
![Image](https://github.com/ayushbagahe/Building-Neural-Network-From-Scratch-Using-Numpy/blob/main/forward_propagation.png)

## Explanation
Forward propagation is how a neural network makes a prediction. Input data moves from the first layer to the last, one step at a time. Each neuron multiplies the input by a weight, adds a bias, and applies an activation function to decide if the signal passes on. This continues layer by layer until the output layer gives the final result. It’s like passing a message in a chain, where each person slightly changes it before handing it off, ending with a final decision.

