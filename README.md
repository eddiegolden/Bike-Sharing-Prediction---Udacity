# Bike-Sharing-Prediction---Udacity
Predicting bike sharing based on data using a neural network - First project in Deep Learning course in Udacity 

#### In this project, you'll build your first neural network and use it to predict daily bike rental ridership. 

![Neural Network](assets/neural_network.png)

### The Technical Details (all the code is in [Bike Sharing notebook](Bike_Sharing_notebook.ipynb) and [My Answers](my_answers.py)
* **Load the data from Bike-Sharing-Dataset folder**
This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

* **Split the data to training, validation and testing**

* **Build the network**
The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is $f(x)=x$. A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called *forward propagation*.

* **Train, test and predict**
Here you'll set the hyperparameters for the network. The strategy here is to find hyperparameters such that the error on the training set is low, but you're not overfitting to the data. If you train the network too long or have too many hidden nodes, it can become overly specific to the training set and will fail to generalize to the validation set. That is, the loss on the validation set will start increasing as the training set loss drops.

You'll also be using a method know as Stochastic Gradient Descent (SGD) to train the network. The idea is that for each training pass, you grab a random sample of the data instead of using the whole data set. You use many more training passes than with normal gradient descent, but each pass is much faster. This ends up training the network more efficiently. You'll learn more about SGD later.

#### My name is Eddie Goldenberg, from Israel
