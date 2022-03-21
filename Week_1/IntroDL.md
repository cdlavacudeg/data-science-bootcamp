# Introduction to Deep Learning & its application
## Learning Objectives

- What and why Deep Machine Learning
- Machine Learning vs Deep Learning
- Deep Learning Applications
- Deep Learning Frameworks

### Some cool deep learning applications
- Deep learning agent playing Flappy Bird!
- Increasing the pixels of a blurry image
- [LipNet](https://www.youtube.com/watch?v=fa5QGremQf8): Lips reading

## Why Deep Learning

Older machine learning algorithms typically plateau (become constant) in performance after they reach a threshold of data.

Deep learning is one-of-a-kind algorithm whose performance continues to improve because more the data fed, the more the classifier is trained, resulting in outperforming the traditional models/ algorithms.

## What is Deep Learning?
- A Deep Learning algorithm is able to learn hidden patterns from the data by itself (without human supervision), combine them together, and build much more eﬃcient decision rules.

Now what does learning hidden patterns mean? Taking the same apple example, it means that:

- A deep learning model first identifies the low level features like the edges of an apple
- Then it slowly understands the more complex features like body and stem.
- Finally, it combines all the learnings and learns the shapes, colours and other characteristics that can be used to identify an apple.
The further you advance into it, the more complex the features it can recognize.

### Machine Learning vs Deep Lerning
- ARTIFICIAL INTELLIGENCE: Programs with the ability to learn and reason like humans.

- MACHINE LEARNING: Algorithms with the ability to learn without being explicitly programmed.

- DEEP LEARNING:Subset of machine learning in which artificial neural networks adapt and learn from vast amounts of data.

### Why is Deep Learning so popular?
In 2012, deep neural networks began to outperform traditional classification algorithms, including machine learning algorithms.This is largely due to increased performance of computer processors (CPUs GPUs) and larger storage media for retaining huge training datasets. Every year since, deep learning has continued to get better, becoming state of the art for solving problems in many diﬀerent domains. This explosion in deep learning is largely thanks to improvements in hardware and massive labeled data sets that allow deep learning models to improve quickly over time.

## Deep Learning frameworks
Both TensorFlow and PyTorch have their advantages as starting platforms to get into neural network programming. Traditionally, researchers and Python enthusiasts have preferred PyTorch, while TensorFlow has long been the favored option for building large scale deep learning models for use in production.

However, the latest releases have seen the two libraries converge towards a more similar profile. As long as you stick to either TensorFlow or PyTorch as your deep learning framework, you can do nothing wrong.

# Introduction to Neural Networks & its working
- Brain neurons: signal is transmittedfrom one neuron to another till it reaches the nerve endings
    - Synapse: The transfer of electric signal between two neurons

- Neural networks: as the name suggest, Neura networks (also called as Artificial Neural Networks ANN) are inspired by the neurons in the human brain.
    - Neurons is to Nervous System
    - **Perceptron** is to Neural Network (Basic unit of a neural network)

## Perceptron - Single Layer Perceptron
Like a single unit in Neural Network is called Neuron, the single most basic unit in Artificial neural network is called Perceptron.

- The various features of our dataset (independent values) are given as input x1, x2, x3,.... xn.
- Each input feature is given a weight to determine how important it is.

Perceptron makes a decision y (dependent variable) on the basis of an activation function.

<img src="https://lh4.googleusercontent.com/Sqi6-cX51iJe64raDIGvSSeOpMJc0P3xoAMZ5GwQDRCZuJlyXb3W2gZ5S9jzCac6vGJzXHkExajx1aQR_ULQd0RrZerAQyR-hEkxCK_oQ7GrYAeTLVwQN8NjTPLBE2EsVifh6GIu2NtkIfOz-A"/>

## Multi Layer Perceptron
When a perceptron that teams up with additional perceptrons, stacked in several layers, to solve complex problems.

<img src="https://lh6.googleusercontent.com/A_pGl7UoJQqQ-dKhrj5k0jhwj3RgN3uSPY2N1Q6mw8bMI6nux4Z19xBYgOH_z5saSshFJL1Bcpxyf3uj8ZIFHjQu60r4DHD_IY1KX3SuV5QAGso09YZuUSOCQaEJ-red8eP43B2RDmzmVSiu1A"/>

In this example, we have three layers:
- Input layer
- Hidden Layer
- Output Layer

## What are Hidden Layers?
Hidden layers constitute of all the layers in a Neural Network other than the input and the output layer - Hence the word hidden.

Hidden layers act like a black box - the internal mechanism is hidden.

Each layer contributes to the final output layer by applying some mathematical transformations.

## When is a Neural Network Called Deep?
Whenever there are more than 3 layers (Input, Hidden, Output) in a Neural Network, we call it a deep Neural network.

<img src="https://lh6.googleusercontent.com/dR0vKLEb8CE5346wfVOPMg77wF8lQ8CtwwTZ697Npco7NSC_9dKVjSRUPIPo4AFBIb0yedwZil6p98uHOR0qjvdUwBaEztKHYtK6y9Ppm9LUnrN2YoR2s_8KKGPxuI13wwAcVEiMGSlPk9scbQ"/>

## What do hidden layers do?
Let us consider a facial recognition Neural Network

<img src="https://lh3.googleusercontent.com/Zu_jMIKZUbRPNSPO02JGKGQeBkHcU2jfuLsKs7HhsCN1mMNlElC7GXP2Pujb5AN3tQ8QFe28gQyxsChHVypSw484f4Xb-TpCnrqZ_L10fgc43_daZIK4nw6WZ_fW43BMi_xYNWMwPsUbgeDMAA"/>

- The initial layers start small - They identify edges
- The middle layer start to identify objects - like eyes, nose, ears etc.
- The final layers start to identify the final images and hence recognise the entire face.

## Forward and Backward Propagation
<img src="https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FQ7bFhKnaWVnMmlxSsNji%2FScreen%20Shot%202022-03-14%20at%207.35.45%20PM.png?alt=media&token=917dce24-8297-446e-91e5-01100f50a530"/>
- Forward Propagation: Signal goes from input layers towards output layers
- Backward Propagation: Signal goes from output to input layers


