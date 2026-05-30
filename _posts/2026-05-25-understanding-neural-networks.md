---
layout: post
title: "Understanding Neural Networks"
math: true
---

The core concept is to find a set of weights that minimizes a defined loss function. This relies heavily on the chain rule of calculus (which we use for backpropagation[^1]).

[^1]: Backpropagation is an algorithm used to calculate the gradient of the loss function with respect to the neural network's weights.

Here is a block equation representing the softmax function:

$$
\sigma(\mathbf{z})_i = \frac{e^{z_i}}{\sum_{j=1}^K e^{z_j}}
$$

And here is an inline equation: $E = mc^2$.
