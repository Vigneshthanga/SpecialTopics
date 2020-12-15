# Text classification with Transformer
Mathematically, it relates to attending to not only the different words of the sentence, but to different segments of the words, too. 
The words vectors are divided into a fixed number (h, number of heads) of chunks, and then self-attention is applied on the corresponding chunks, resulting in h context vector for each word. 
The final context vector is obtained by concatenating all those h context vectors.

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
1) Run text_classification.ipynb
