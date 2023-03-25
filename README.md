# NORMID-NORWAY

# Problem Statement:  
From a provided dataset, containing tens of thousands of handwritten images, namely the MNIST (Modified National Institute of Standards and Technology) dataset; create an AI-ML model that identifies and differentiates digits written in human handwriting. 
The goal of this project is to create a model that will be able to recognize and determine the handwritten digits from its image by using the concepts of Convolution Neural Network. Though the goal is to create a model which can recognize the digits, it can be extended to letters and an individual’s handwriting. The major goal of the proposed system is understanding Convolutional Neural Network, and applying it to the handwritten recognition system.

# Abstract
Handwritten character recognition is one of the practically important issues in pattern recognition applications. The main purpose of this project is to build an automatic handwritten digit recognition method for the recognition of handwritten digit strings.
* To accomplish the recognition task, first, the digits will be segmented into individual digits. Then, a digit recognition module is employed to classify each segmented digit completing the handwritten digit string recognition task.
* The applications of digit recognition include postal mail sorting, bank check processing, form data
entry, etc. 
* The heart of the problem lies within the ability to develop an efficient algorithm that can recognize handwritten digits and which is submitted by users by the way of a scanner, tablet, and other digital devices

# Introduction
Digit recognition system is the working of a machine to train itself or recognizing the digits from different sources like emails, bank cheque, papers, images, etc. and in different real-world scenarios for online handwriting recognition on computer tablets or system, recognize number plates of numeric entries in forms filled up by hand and so on.

# How we built it?
This **AI model** has been programmed in python language. Many new libraries has been used such as tensorflow, opencv, matplotlib, numpy, keras.
* Keras- It allows you to define and train neural network models in just a few lines of code.
* Tensorflow- It is a foundation library that can be used to create Deep Learning models directly or by using wrapper libraries that simplify the process built on top of TensorFlow.
* Numpy- It is a library consisting of multidimensional array objects and a collection of routines for processing those arrays.
* Matplotlib- It provides an object-oriented API for embedding plots into applications.
* Opencv- It is a Python library that allows you to perform image processing and computer vision tasks. 

# Advantages of this system
1) The system not only produces a classification of the digit but also a rich description of the instantiation parameters which can yield information such as the writing style.
2) The generative models can perform recognition driven segmentation.
3) The method involves a relatively small number of parameters and hence training is relatively easy and fast.
4) Unlike many other recognition schemes, it does not rely on some form of pre-normalization of input images, but can handle arbitrary scalings, translations and a limited degree of image rotation. 

# Shortcomings of this system
1) It requires much more computation than more standard OCR techniques.
2) Problems of not having the same size, width, orientation, and margin has been resolved with the help of computer vision’s opencv library’s functionalities.
3) Also the problem of difficulty in distinguishing the digits such as 1 and 7, 5 and 6, 3 and 8 etc has been resolved to a greater extent. 
4) Also problems of dim lighting and blurry or unclear.

# Future Scope
Future application of these algorithms lie from the public to high-level authorities, as with future development we can attain high-level functioning applications which can be used in -
* For the classified agencies as well as commoners.
* Development of more efficient methods to complete tasks like Postal mail sorting, bank check processing, form data entry.
* More accurate detection of  vehicle numbers that can be used in security and crime detection.
* More accurate models can also help in developing more advanced facial recognition system.

# What we have learnt
We have learnt about many new libraries and how to use them like numpy, tensorflow, keras. The intresting part was to learn about how to create a model based on Convolutional Neural Network, and dive deeper into the world of Artifical Intelligence. Got to know about that there exist such dataset named keras which have about 60,000 of training samplesand 10,000 of testing samples. 
