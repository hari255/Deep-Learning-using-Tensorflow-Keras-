We will be extensively using Tensorflow and Keras to heat and train our machine learning model.  { requirements : 6 cores, 16GB RAM, GPU Preferred} If not, you may expereience dealys in training the model.

Watch out for Pit Falls: 

What are we going to do?

Regression or Classification?

Regression : Trying to predict a real number.

Classification : Trying to assign a value to particular class. It can be binary or we may also have multiple classes.

AID to tune hyperparameters:

ACTIVATION FUNCTIONS in Neural Networks: Sigmoid, Tanh, ReLU, LeakyReLU, MaxOut and ELU
We wiil choose above activation functions to fire a neuron based on the data. 
Ex: Signmoid is used to predict probability as an output 
Ex: Tanh is used for classification between two classes
Ex: ReLU is most commonly used activation function in CNN's

LOSS FUNCTIONS in Neural Networks: It is also referred to as Cost function or error function, It qunatifies the error between output of the algorithma and given target value
Goal is to minimize the loss function / minimizing the errors
Ex: MSE for regression problems / MAE(mean absolute error)
Ex: Cross entropy for sigmoid related problems / Hinge loss
Ex: Svm loss 

OPTMIZERS in neural networks: Optmizers updates the model, in response to the output of the loss function.
categorical_crossentropy for Multi-class classification
Adam for Adaptive moment estimation which is well suited for data in high dimensional feature space. 


hYPERPARAMETERS AND lOSS FUNCTIONS

Parameters of a deep neural network are the weights and biases that are learned using the backpropagation algorithm.
In addition, there are many hyperparameters for an MLP. These are parameters specified before
training, not learned from a training set.
• Number of hidden layers.
• Number of neurons in each layer
• The activation units in each hidden layer and possibly its parameters.

Another choice to make is the loss function to minimize. Possible choices are:
• Mean square error or mean square log function.
• Mean absolute error.
• Binary cross-entropy or multiclass cross-entropy function.
• Hinge loss or squared hinge loss.

Hyperparameters Related to Training, There are also hyperparameters related to training.
• Learning rate in gradient descent.
• Momentum parameter.
• Number of epochs (iterations)
• Batch size.

Methods to find hyperparameters
• Manual search.
• Grid search.
• Random Search.
• Bayesian optimization.
