---
layout: page
title: Winter 2021
---

This course surveys how networks of neurons can perform computation. We will cover a variety of methods for designing and training neural networks. We will study some state-of-the-art methods for artificial neural networks, as well as some approaches that are guided by the biological constraints of the brain. We will look at both supervised and unsupervised learning. Other topics include population coding.

## Instructor
[Jeff Orchard](http://cs.uwaterloo.ca/~jorchard)

## Suggested Prerequisites
- one of ([CS 370](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS370), [CS 371](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS371)/[AMATH 242](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-AMATH.html#AMATH242))

## Goals
By the end of the course, students will be able to:
- Write a program to simulation the activity of a network of neurons
- Formulate a neural learning method as gradient-based optimization
- Derive a neural learning method based on energy minimization
- Encode and decode data from the activity of a population of neurons
- Evaluate implementations, designs, and optimization strategies
- Identify some commonalities between artificial neural networks and the brain

## Textbooks
- *Theoretical Neuroscience*, Dayan and Abbott, 2001 ([UW library link](http://books.scholarsportal.info.proxy.lib.uwaterloo.ca/viewdoc.html?id=/ebooks/ebooks2/pda/2011-12-01/1/11936.9780262041997))
- *Neural Networks and Deep Learning*, Nielsen, 2017 ([link](http://neuralnetworksanddeeplearning.com/index.html))
- *Deep Learning*, Goodfellow, Bengio and Courville, 2016 ([link](http://www.deeplearningbook.org/))
- *Neural Engineering*, Eliasmith and Anderson, 2003: MIT Press.

## Lecture Schedule
The course will be offered online, but we will have some live tutorials each week (recorded).
- Tutorial time: TBD

## Evaluation
The course will have several assignments, a midterm, and final exam. Assignments will involve programming in Python. The approximate grade breakdown is:
- 20% Quizes
- 10% Peer Evaluation
- 40% Assignments
- 30% Final Assessment
  - Take-home final exam for those taking CS 489, or
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
- Autodifferentiation
- Error Backpropagation
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



