# Generator-RNN-TV-Scripts

In this project, you'll generate your own Simpsons TV scripts using RNNs. You'll be using part of the Simpsons dataset of scripts from 
27 seasons. The Neural Network you'll build will generate a new TV script for a scene at Moe's Tavern.

The codes and result analysis of the project are detailed in the .ipynb file located in the same repo.

The structure of the project is as follows:

- Get the Data
- Explore the Data
- Implement Preprocessing Functions
** Lookup Table
** Tokenize Punctuation
** Preprocess all the data and save it
- Check Point 1
- Build the Neural Network
** Check the Version of TensorFlow and Access to GPU
** Input
** Build RNN Cell and Initialize
** Word Embedding
** Build RNN
** Build the Neural Network
** Batches 
-Neural Network Training
** Hyperparameters
** Build the Graph
- Train
** Save Parameters
- Check Point 2
- Implement Generate Functions
** Get Tensors
** Choose Word
- Generate TV Script
