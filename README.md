Theano-Lights
=============

Theano-Lights is a research framework based on Theano providing implementation of several recent Deep learning models and a convenient training and test functionality. The models are not hidden and spread out behind layers of abstraction as in most deep learning platforms to enable transparency and flexiblity during learning and research. 

To run:
```
pip install -r requirements.txt
python train.py
```

You can find instructions on how to obtain and prepare the datasets [here](https://github.com/Ivaylo-Popov/Theano-Lights/blob/master/Data%20instructions.txt). 

#### Included models:
 * Feedforward neural network (FFN)
 * Convolutional neural network (CNN)
 * Recurrent neural networks (RNN)
 * Variational autoencoder  (VAE)
 * Convolutional Variational autoencoder (CVAE)
 * Deep Recurrent Attentive Writer (DRAW)
 * LSTM language model

#### Included features:
 * Batch normalization
 * Dropout
 * LSTM, GRU and SCRN recurrent layers
 * Virtual adversarial training (Miyato et al., 2015)
 * Contractive cost (Rifai et al., 2011)

#### Stochastic gradient descent variants:
 * SGD with momentum 
 * SGD Langevin dynamics
 * Rmsprop
 * Adam
 * Adam with gradient clipping
 * Walk-forward learning for non-stationary data (data with concept drift)

#### Supervised training on:
 * MNIST

#### Unsupervised training on:
 * MNIST
 * Frey Faces    
 * Penn Treebank
 * text8

#### Other models and features:
 * Auto-classifier-encoder (Georgiev, 2015)
 * Radias basis function neural network
 * Denoising autoencoder with lateral connections

#### Work in progress:
 * Natural neural networks (Desjardins et al., 2015) 
 * Ladder network (Rasmus et al., 2015)
 * Virtual adversarial training for CNN and RNN

Sampling a generative MNIST model developed in this framework. 

[![Sampling MNIST](https://i.ytimg.com/vi/XGUrvMAVv5g/2.jpg?time=1442748191345)](https://youtu.be/XGUrvMAVv5g)
