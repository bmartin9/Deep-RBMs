# Deep-RBMs
A package to train deep Restricted Boltzmann Machines on 2D Ising Configurations 

# Overview 
This package contains a general Restricted Boltzmann Machines (RBM) class that allows maximum flexibility in designing the architecture of your RBM. In Particular, it lets you choose exactly which weights to train and which weights to keep at a fixed (pre-defined) value. You can have multiple layers of weights (deep RBM). 

We use this deep RBM class to train a deep RBM with a very specific architecture on 2D Ising configurations. We generate our Ising configurations using standard Markov Chain Monte-Carlo (MCMC) simulations. 

The architecture of our RBM is motivated by the mathematical connection between RBMs and the Renormalization Group as well as by connections with holography (AdS/CFT). For more detail, see our report. 

With our trained RBM, we generate new Ising configurations and measure the couplings between the generated configurations. 

# Installation Guide 
Clone the repository using:
`git clone https://github.com/bmartin9/Deep-RBMs`

Install `venv`if you don't already have it:
`pip install venv`

Make your virtual environment: 
`python -m venv venv`

Activate your virtual environment:
`source venv/bin/activate` 

Install the project requirements into your virtual environment:
`pip install -r requirements.txt` 

# How to run this package 

