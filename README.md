# MNIST-dataset-with-deep-learning
### "Neural Network for digit recognition"

The first file "Neural Network for digit recognition" has two parts. In the first part I build a simple fully connected one hidden layer neural network from scratch. Hidden units are activated using tanh function. Neural network is trained using cross entropy loss. I change the number of hidden units and learning rates to find the optimal parameters. Final model has 100 hidden units and learning rate of 0.003.

The second part has an additional hidden layer with 100 hidden units.  


### Neural Network for digit recognition with different regularization techniques

In this file I build a fully connected neural network from scratch and implement different regularization and optimization techniques. Neural network has two hidden layers with 300 hidden units in each layer.

The techniques used are:
* L2 regularization. 
* RMSprop optimization + L2 regularization
* dropout + L2 regularization.

### MNIST dataset with CNN and TensorFlow

In this file I investigate three models with different neural network architectures using TensorFlow. The activation function is Relu for all models. 

* First model have one convolutional layer and two fully connected layers. 
* Second model has two convolutional layers and two fully connected layers.
* Third model has three convolutional layers and one fully connected layer. 


### Software demands

The first two python notebooks are written in Python 2, the third one is written in Python 3. 

The libraries needed for the first two are pandas, numpy, matplotlib and math. Additionally, TenserFlow is needed for the third one. 
