# Project repository by : Marwan Tragha - Valerio Guerrini - Vincent Herfeld #

>This repository contains a single self-contained notebook, that allows to train and use different VAE models on the MNIST dataset.

### Execution : ###

To **run** the code all you need to do is **execute the notebook cells** of the file `code.ipynb`.

### What you will find : ###

The notebook contains all neural networks for the Encoder and Decoder, as well as the different processes to train either a classsical Variational Auto-Encoder (VAE) or a Wake-Wake AE.

Once a model is fitted we have 1. a generative model $p_\theta(x, z)$ 2. an approximation of the true posterior $q_\phi(z | x)$

### What next ? ###

The next steps we should implement are IWAE, Chi-VAE and a decision framework to use these densities to solve decision-base tasks. In the case of MNIST, classification tasks are relevant. 
We can rely on the approximate posterior to compute the expected posterior loss and make decisions depending on these quantities.


