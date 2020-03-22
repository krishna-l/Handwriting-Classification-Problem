# Handwriting-Classification-Problem
Handwriting classification is a major NLP problem that can be used for object detection and for converting a handwritten document to a digital word document. Handwriting classification is the first step in doing the task. 

Here the mnist dataset from Keras is used and we will be doing the same in 2 methods. 
1. Using Multi-Layered Perceptron model (Only TensorFlow): Train accuracy:- ~93% and test accuracy: ~92% No. of neurons = 512 and hidden layers: 2
2. Using Multi-Layered Perceptron model (TensorFlow + Keras): Train accuracy:- ~99% and test accuracy: ~98% No. of neurons 512 each and hidden layers: 2
3. Using Convolutional Neural Network + MLP: Train accuracy:- ~98.6% and test accuracy: ~98% with 2 2D Convolutional filters layers with 32 and 64 filters each and a single hidden layer with 128 neurons. All of them had relu activation function and Optimizer used was RMSprop.
Train accuracy:- ~99.05% and test accuracy: ~99.07% with the same above configuration but by using adam optimizer.
