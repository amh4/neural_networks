# neural_networks

## The Tech

<div align="center">
	<code><img height="40" src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="Jupyter Notebook" title="Jupyter Notebook" /></code>
	<code><img height="40" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python" /></code>
</div>

## Note - I have not run this code locally due to the GPU demands of running NN's. This code was run in Kaggle as they allocate 30hrs per week of TPU (Tensor Processing Unit) time. It is downloaded from Kaggle as per the end of the exercise.

This repo contains two of the Neural Networks that I have built as part of the Kaggle Deep Learning resources they provide.

# What are Neural Networks?

A Neural Network is a collection of interconnected Nodes that each take multiple inputs from each other. When combined into Layers of Nodes, each with their own unique relations to each other, these layers can take on strong predictive abilities.

The relationships between each Node are set when the model is trained. When training the model the weight of each input to the Node, and the bias assigned to that Node, is set. This is an iterative proccess, that when do robustly, can leave you with an accurate model.

The iterative training process is controlled through multiple variables such as:

Batch Size - How much data is passed in during each training sample
Epoch - When an entire data set has been passed through the network
Dropout layer - When part of a different part of a layer is sytematically removed when training the model to reduce overfitting
Batch Normalization Layer - When all the feature data is set to a typical scale
Learning Rate - Defines how quickly the network updates itself on what it has learned so far. The quicker the learning rate the larger the moves you will see in your validation loss output

There are many other variables within the model that you are able to tweak to alter the model but this is my initial understanding so far. You can discuss the loss function used, the optimizer, the numbers of layers and number of Nodes plus much much more.

# The Networks in this repo

The first model is for Binary classification designed to predict whether a hotel booking will be cancelled.

The second file on Dropout and Batch Normalization layers contains two models. One predicting how popular a track on Spotify will be. The second predicting the compresive strength of concrete.

# Next Steps

After getting an understanding of how to build a model the next steps will be to work independently on Kaggle hosted datasets to get a better understanding of how to adjust models for best results.
