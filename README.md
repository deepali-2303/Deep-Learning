# RNN Implementation from Scratch

## Overview

This repository contains a Recurrent Neural Network (RNN) implementation from scratch using NumPy. The RNN is designed to process sequences of data, such as text, and learn to predict the next element in the sequence. This implementation covers the essential components of an RNN, including forward and backward passes, weight updates, and text generation.

## Implementation Details

- **Forward Pass**: Computes hidden states and outputs for each time step in the sequence.
- **Backward Pass**: Implements backpropagation through time to compute gradients and update weights.
- **Training**: Uses gradient descent to minimize cross-entropy loss.
- **Sampling**: Generates sequences by sampling from the model’s output probabilities.

## References

- [Recurrent Neural Networks (RNNs)](https://towardsdatascience.com/recurrent-neural-networks-rnns-3f06d7653a85)
- [Minimal character-level language model with a Vanilla Recurrent Neural Network](https://gist.github.com/karpathy/d4dee566867f8291f086)
- [Recurrent Neural Network Forward Propogation With Time](https://www.youtube.com/watch?v=u8utlK_c5C8)
- [Various Weight Initialization Techniques in Neural Network](https://www.youtube.com/watch?v=tMjdQLylyGI)


