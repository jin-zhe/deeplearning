# Deep Learning Glossary
Quick reference glossary for terminologies used in deep learning.

## General

### Activation Function
**Definition**: Function which is applied over a neuron's inputs, adding a bias term and its output signifies how much the neuron should fire.

### Attention
**Definition**: A mechanism or module where it tells the network where to look at.  
**Provenance**: https://arxiv.org/abs/1506.07503

### Batch
**Definition**: A partition (usually fixed-size) of the total training dataset to be fed into the network at one go.

### Batch Size
**Definition**: The number of training examples present in a single batch.

### Classification
**Definition**: Task associated with predicting a discrete class label.

### Cost / Loss / Objective Function
**Definition**:
* **Objective function**: The most general term for any function that you optimize during training. E.g. MLE is an objective function to maximize whereas a cost function is a objective function to minimize.
* **Cost function**: A weighted sum of loss functions over your training set plus some model complexity penalty (regularization). If only one loss function is involved, then the cost function is the loss function.
* **Loss function**: Evaluates the penalty given the model's prediction when measured against the ground truth.

### End-to-End
**Definition**: A network which accepts input from one end, and produces output at the other end. As opposed to "Pipeline".

### Epoch
**Definition**: When the entire dataset underwent a forward pass followed by a backward pass in the network exactly once.

### Fine-tuning
**Definition**: Adapting a pre-trained model for a new task by using the pre-trained model parameters as the initializations for training on the new task.

### Gradient Descent
**Definition**: An iterative optimization algorithm to find the local minima of an objective function.

### Iterations
**Definition**: The number of batches needed to complete one epoch.

### Learning Rate / Step Size
**Definition**: The size of each advancement for an iteration of gradient descent.

### Regression
**Definition**: Task associated with predicting a continuous value/quantity

### Perceptron
**Definition**: A single layered neural network.

### Pipeline
**Definition**: When multiple models are trained independently and then combined into a pipeline. As opposed to "End-to-End".

### Stochastic Gradient Descent
**Definition**: Optimized gradient descent algorithm where instead of iterating through all training examples for an interation update, only iterate through a randomly selected batch of training examples.

## Computer Vision

### Activation / Feature Map 
**Definition**: The 2D tensor output by a single convolution filter. AKA "Feature Map".
**See**: https://arxiv.org/abs/1311.2901
