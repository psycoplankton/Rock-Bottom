# Rock-Bottom
The repository contains the notebook as well as python implementations of laguange models.

`Bigram and Neural Net` notebook has the implementations of a bigram model which takes pairs of characters and assigns probabilities based on the number of occuerences of that pair. Neural Net implementation is from scratch, to the point of the operation that happens in each neuron. 

`Multi-Layer-Perceptron` notebook has the implementation of a multi layer perceptron.

`BatchNorm_gradient_statistics` notebook is where we dig deep into the functioning of the neural netowrk and look at the gradient evolution, activation fucntions evolution. We talk about kaiming initialization from the paper [https://arxiv.org/abs/1502.01852v1]. 

`Manual_BackProp` notebook has a full on manual implentation of backpropogation algorithm through a multi layer perception.

`Wavenet` notebbok has the implementation of WaveNet architecture which was originally proposed for audio recognition but can be applied to language modelling as well, with slight modification. In the paper they use Conv1D layer, but here simple linear layers are used.
