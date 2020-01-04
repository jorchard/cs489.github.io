---
layout: page
title: Winter 2020
---

This course surveys how networks of neurons can perform computation. We will cover a variety of methods for designing and training neural networks. We will study some state-of-the-art methods for artificial neural networks, as well as some approaches that are guided by the biological constraints of the brain. We will look at both supervised and unsupervised learning. Other topics include population coding.

## Instructor
[Jeff Orchard](http://cs.uwaterloo.ca/~jorchard)

## Suggested Prerequisites
- one of ([CS 370](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS370), [CS 371](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS371)/[AMATH 242](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-AMATH.html#AMATH242))

## Goals
By the end of the course, students will be able to:
- Write a program to simulate the activity of a network of neurons
- Formulate a neural learning method as a gradient-based optimization
- Write a program (in Python) to implement a neural learning method from scratch
- Use a software package and supplied data to train a neural network
- Identify some commonalities between artificial neural networks and the brain

## Textbooks
- *Theoretical Neuroscience*, Dayan and Abbott, 2001 ([UW library link](http://books.scholarsportal.info.proxy.lib.uwaterloo.ca/viewdoc.html?id=/ebooks/ebooks2/pda/2011-12-01/1/11936.9780262041997))
- *Neural Networks and Deep Learning*, Nielsen, 2017 ([link](http://neuralnetworksanddeeplearning.com/index.html))
- *Deep Learning*, Goodfellow, Bengio and Courville, 2016 ([link](http://www.deeplearningbook.org/))
- *Neural Engineering*, Eliasmith and Anderson, 2003: MIT Press.

## Lecture Schedule
- MWF 11:30 - 12:20, STC 0060

## Evaluation
The course will have several assignments, a midterm, and final exam. Assignments will involve programming in Python. The approximate grade breakdown is:
- 50% Assignments
- 15% Midterm Exam
- 35% Final Assessment
  - Final exam for those taking CS 489, or
  - Project for those taking CS 698

## Topics

1. Background (4 hours)
- Neuron models, spiking vs. firing-rate
- Activation functions
- Synapses
- Networks of neurons
- The Brain: vision, memory, motor control
- Learning: supervised/unsupervised/reinforcement

2. Supervised Learning (8 hours)
- Perceptron
- Train, validation, testing
- Universal Approximation Theorem
- Cost functions
- Gradient descent using finite-difference approximation
- Error Backpropagation
- Associative memory
- Stochastic Gradient Descent (SGD)
- Regularization, Momentum, Dropout

3. Unsupervised learning (5 hours)
- Autoencoders
- Network Energy
- Restricted Boltzmann Machines (RBM)
- Deep Belief Networks
- Variational Autoencoders

4. Population coding (6 hours)
- Optimal linear decoding
- Transformations and Dynamics
- Neural integrators as working memory
- Prescribed Error Sensitivity learning

5. Convolutional Neural Networks (2 hours)

6. Recurrent Neural Networks (3 hours)
- Backprop Through Time (BPTT)
- Long Short-Term Memories (LSTM)

7. Advanced Topics (time permitting)
- Adversarial Inputs
- Predictive Coding
- Equilibrium Propagation
- Vector Embeddings (word2vec)



