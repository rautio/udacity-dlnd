# Deep Learning Foundation Nanodegree

This is a repository meant to document my projects for [Udacity's Deep Learning Foundation Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101).

## Projects

### 1. Bikeshare Usage - Neural Network from scratch

In this project we build a simple neural network from the ground up to predict bikeshare usage for the month of December based on 60 days of historical data. The purpose of this project was to introduce neural networks and create a better understanding of gradient descent, backpropagation and other concepts that might otherwise be hidden in higher level tools like Tensorflow.

The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

### 2. Image Classification - Convolutional Neural Network

In this project we build and train a convolutional neural network to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) consisting of airplanes, dogs, cats and other objects. We use a convolutional layer, max pool layer and a fully connected layer with image normalization and one-hot encoding of the labels.

### 3. TV Script Generation - Recurrent Neural Network

In this project we use a Recurrent Neural Network to generate scripts for the Simpsons TV show. We use a subset of all scripts from 27 seasons. The neural network generates a new script for a scene at Moe's Tavern.

### 4. Language Translation - Sequence to Sequence RNN

In this project we use a sequence to sequence model on a dataset of English to French sentences to translate new sentences from English to French.

### 5. Face Generation - Generative Adversarial Network

In this project we use a generative adverserial network (GAN) to genearte new images of faces that we've never seen based on the [CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). We also train it on the [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for easier parameter tuning and model testing.