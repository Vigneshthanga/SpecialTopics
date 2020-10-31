# Multi Task Learning 

Multi-task learning is a type of learning where we predict multiple targets with the same input features. 
For example, apart from image classification task, we can also predict the image quality between 0 and 1.

Overview of Model
=================
1) The first layer is Image input layer
2) Next is Normalization layer
3) Next is ImageAugmentation layer
4) Then a convolution block and resnet block
5) Structured Data Input
6) Then a merge layer both type of inputs. Finally, diverge two different heads as classification head and regression head.

Requirements
============
Our model requires Numpy and Autokeras

How to Run / Alter Code
=======================
1) Run Multi_Task_Learning.ipynb
