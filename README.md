# Description
A Neural Network model is presented in TensorFlow using its core functionality without a high-level API like Keras. Gradient descent algorithm is implemented with TensorFlow's automatic differentiation to update layer parameters. Finally, this implementation is used to classify hand-written digits. 

The project workflow is as follows:
1. Creating the Neural Network class. Setting up initial parameter values.
2. Creating a forward pass function.
3. Computing the cross entropy loss with logits. Updating parameters for all the layers.
4. Creating a predict function with the help of the forward pass.
5. Creating the main training mechanism. Implementing gradient descent with automatic differentiation.
6. Breaking down data-set in batches. Breaking down the training process in epochs and steps.
7. Applying the neural network model to classify hand-written digits from MNIST Dataset.
8. Creating model instance and setting up hyperparameters.Training the model.
9. Plotting the training results. Visualizing predictions on the test set.

# Dataset
The MNIST Dataset is used to train the neural network. The MNIST database consists of handwritten digits having a training set of 60,000 examples, and a test set of 10,000 examples. For more, see https://www.kaggle.com/datasets/hojjatk/mnist-dataset

# Results 

