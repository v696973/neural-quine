# neural-quine
Neural network-based (wellllll, rather "logistic regression-based" for now, but that doesn't sound so cool, right?) quine in pure Python.

Quine is a program that reproduces its own source code. I wrote rather inefficient and large quine by training a single neuron neural net for character by character prediction of the source code, that does character by character prediction of itself using network's trained weights. First I predict this code, then I insert the weights of the net into it and print it out.
The code should be simple enough to understand, yet it's rather esoteric - I used a few tricks to make the weights for the network smaller, sacrifising the readability of the code. Most of the space in the code is taken by weights of a single neuron.
