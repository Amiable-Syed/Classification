# Classification
Classification models for classification problems.

## Background:
The convolutional neural network (CNN) is a class of deep learning neural networks. CNNs represent a huge breakthrough in image recognition. They’re most commonly used to analyze visual imagery and are frequently working behind the scenes in image classification. They can be found at the core of everything from Facebook’s photo tagging to self-driving cars. They’re working hard behind the scenes in everything from healthcare to security. They’re fast and they’re efficient. But how do they work? Image classification is the process of taking an input (like a picture) and outputting a class (like “cat”) or a probability that the input is a particular class (“there’s a 90% probability that this input is a cat”). You can look at a picture and know that you’re looking at a terrible shot of your own face, but how can a computer learn to do that? With a convolutional neural network!

A CNN has 
* Convolutional layers 
* ReLU layers 
* Pooling layers 
* A Fully connected layer A classic CNN architecture would look something like this:

**Input ->Convolution ->ReLU ->Convolution ->ReLU ->Pooling -> ReLU ->Convolution ->ReLU >Pooling ->Fully Connected** 

A CNN convolves (not convolutes…) learned features with input data and uses 2D convolutional layers. This means that this type of network is ideal for processing 2D images. Compared to other image classification algorithms, CNNs actually use very little preprocessing. This means that they can learn the filters that have to be hand-made in other algorithms. CNNs can be used in tons of applications from image and video recognition, image classification, and recommender systems to natural language processing and medical image analysis. CNNs have an input layer, and output layer, and hidden layers. The hidden layers usually consist of convolutional layers, ReLU layers, pooling layers, and fully connected layers.  Convolutional layers apply a convolution operation to the input. This passes the information on to the next layer.  Pooling combines the outputs of clusters of neurons into a single neuron in the next layer.  Fully connected layers connect every neuron in one layer to every neuron in the next layer. In a convolutional layer, neurons only receive input from a subarea of the previous layer. In a fully connected layer, each neuron receives input from every element of the previous layer. A CNN works by extracting features from images. This eliminates the need for manual feature extraction. The features are not trained! They’re learned while the network trains on a set of images. This makes deep learning models extremely accurate for computer vision tasks. CNNs learn feature detection through tens or hundreds of hidden layers. Each layer increases the complexity of the learned features. 

## A CNN 
* starts with an input image 
* applies many different filters to it to create a feature map applies a ReLU function to increase non-linearity  applies a pooling layer to each feature map
* Flattens the pooled images into one long vector. 
* Inputs the vector into a fully connected artificial neural network.
* Processes the features through the network. The final fully connected layer provides the “voting” of the classes that we’re after.
* Trains through forward propagation and backpropagation for many, many epochs. This repeats until we have a well-defined neural network with trained weights and feature detectors.
