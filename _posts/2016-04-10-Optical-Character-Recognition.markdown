---
title: "[Projects] : Optical Character Recognition using CNN"
date: 2016-04-10 22:10
tags: [Projects,Machine Learning,OCR,Tensorflow,Neural Network]
categories: [Projects]
---

This project was the beginning of my journey into practicing Machine learning. I had very recently worked through the video lectures of Andrew Ng's coursera course on Machine learning and was eager to get my hands dirty with Neural networks.

Before I describe the solution, it is only fair that I describe the problem that the solution addresses.

**So, what is the MNIST dataset and why do we care ?**

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. It consists of labelled images of handwritten digits. Each image is 28 pixels by 28 pixels. The challenge that MNIST dataset provides is to look at a few of these labelled images through our algorithm and then be able to predict the labels of all the new images (not seen before). Sounds like a cool ability to have, right ? In the text that follows, we discuss how we use something known as Convolutional Neural Network to do just this. 

For more information on the MNIST dataset, including tabular data of how successful different algorithms have proven to be on this benchmark dataset, have a look [Here](http://yann.lecun.com/exdb/mnist/).


**Convolutional Neural Networks**

Considering that I did not have a lot of experience with ML at that time, learning CNNs proved challenging to me and me explaining it here using text and examples of my own would not only involve a lot of effort but also feels like reinventing the wheel to me. So to save myself as well as the reader some time and effort, I mention the resources that, I felt, provided the best explainations for CNN.

To understand CNN's, consider [This](http://cs231n.github.io/convolutional-networks/) or [This](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) or maybe [This](https://medium.com/technologymadeeasy/the-best-explanation-of-convolutional-neural-networks-on-the-internet-fbb8b1ad5df8).

In addition, if there is some component regarding CNN that you are not able to understand, contact me via email and I will try my best to help you out. My contact information is available [Here](pratikmishra.in).

**Tensorflow**

TensorFlow is an open source software library for high performance numerical computation developed by researchers and engineers from the Google Brain team within Google’s AI organization.It comes with strong support for machine learning and deep learning. For more information, check out their [Website](https://www.tensorflow.org/).

**Implementation and Accuracy**

The Tensorflow website provides a tutorial on applying a fully connected CNN on MNIST dataset. I followed this tutorial for my implementation and obtained an accuracy of 99.2 %. The code can be found on [github](https://github.com/tensorflow/tensorflow/blob/r1.1/tensorflow/examples/tutorials/mnist/fully_connected_feed.py).
