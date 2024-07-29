# RNN Implementation from Scratch

## Overview

This repository contains a Recurrent Neural Network (RNN) implementation from scratch using NumPy. The RNN is designed to process sequences of data, such as text, and learn to predict the next element in the sequence. This implementation covers the essential components of an RNN, including forward and backward passes, weight updates, and text generation.

## Implementation Details

- **Forward Pass**: Calculates hidden states using the current input and previous hidden state. Outputs are generated using a softmax layer.
- **Backward Pass**: Computes gradients for weights and biases using backpropagation through time (BPTT). Gradients are clipped to avoid exploding values.
- **Training**: Adjusts weights using gradient descent to minimize cross-entropy loss. Training continues until the loss is below a threshold or a maximum number of iterations is reached.
- **Sampling**: Generates a sequence of words by sampling from the model’s output probabilities.

## References

- [Recurrent Neural Networks (RNNs)](https://towardsdatascience.com/recurrent-neural-networks-rnns-3f06d7653a85)
- [Minimal character-level language model with a Vanilla Recurrent Neural Network](https://gist.github.com/karpathy/d4dee566867f8291f086)
- [Recurrent Neural Network Forward Propagation With Time](https://www.youtube.com/watch?v=u8utlK_c5C8)
- [Various Weight Initialization Techniques in Neural Network](https://www.youtube.com/watch?v=tMjdQLylyGI)


