
# XOR Perceptron

## Overview

This repository contains Python code for implementing a simple Perceptron to solve the XOR problem. The code includes functions for forward propagation, backward propagation, and training the neural network.

## Files

* `xor_perceptron.ipynb`: Jupyter Notebook containing the main code for XOR Perceptron.
* `README.md`: Documentation file explaining the code and its components.

## Dependencies

* Python 3.x
* Libraries: numpy

## Setup

1. Install the required dependencies:
   <pre><div class="bg-black rounded-md"><div class="flex items-center relative text-gray-200 bg-gray-800 dark:bg-token-surface-primary px-4 py-2 text-xs font-sans justify-between rounded-t-md"></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">pip install numpy
   </code></div></div></pre>
2. Open and run the `xor_perceptron.ipynb` Jupyter Notebook for detailed execution.

## Code Structure

* `forward_propagation`: Function for the forward propagation step, predicting the output.
* `backward_propagation`: Function for the backward propagation step, updating weights based on errors.
* `train`: Training function to iterate through epochs and update weights.

## Neural Network Architecture

* Input Layer Neurons: 3
* Hidden Layer Neurons: 4
* Output Layer Neurons: 1

## Usage

1. The notebook implements a Perceptron to solve the XOR problem.
2. Execute the code cells in sequential order to train and test the Perceptron.

## Additional Information

* The code includes comments for better understanding of each function and step.
* Adjust the number of neurons in the hidden layer or other parameters for experimentation.

## License

This code is provided under the [MIT License]().
