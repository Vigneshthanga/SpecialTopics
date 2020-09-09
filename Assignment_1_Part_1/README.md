# Multi Instance Learning on MNIST Data
Overview of Model
=================
1) Train a Resnet classifier model on MNIST Data
2) Load the pretrained model except the last layer. This will extract the features that are learnt in the first model.
3) Create bag of images where label 1 indicates the bag contains atleast one 1 and 0 indicates no one.
4) Define a new Neural network to do this binary classification task
5) Maximum number of instances that can be in the bag is 7.

Requirements
============
Our model requires PyTorch

How to Run / Alter Code
=======================
1) Run FeatureExtraction.ipynb => save the model in a pickle file
2) Run MIL_Classification.ipynb
