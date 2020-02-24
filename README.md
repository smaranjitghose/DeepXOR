# DeepXOR
A foundational problem of implementing XOR Gate using Artificial Neural Networks

### Okay!..Lemme see:

An XOR (exclusive OR gate) is a digital logic gate that gives a true output only when both its inputs differ from each other. The truth table for an XOR gate is shown below:

![](https://github.com/smaranjitghose/DeepXOR/blob/master/images/XOR_Truth_Table.png)

The goal of the neural network is to classify the input patterns according to the above truth table. If the input patterns are plotted according to their outputs, it is seen that these points are not linearly separable. Hence the neural network has to be modeled to separate these input patterns using decision planes

### An insight into the Neural Network

As mentioned before, the neural network needs to produce two different decision planes to linearly separate the input data based on the output patterns. This is achieved by using the concept of hidden layers. The neural network will consist of one input layer with two nodes (X1,X2); one hidden layer with two nodes (since two decision planes are needed); and one output layer with one node (Y). Hence, the neural network looks like this

![](https://github.com/smaranjitghose/DeepXOR/blob/master/images/XOR_NN.png)
