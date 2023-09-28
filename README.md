# Multilayer-Perceptron
The paper describes and provides a detailed account of the implementation of a Multilayer Perceptron (MLP) using Keras to determine whether a patient has diabetes. 

MLP is an artificial neural network (ANN) architecture developed as a solution to the limitations of the perceptron, which represents the simplest ANN architecture [1, p.305]. An MLP typically comprises an input layer, one or more hidden layers, and an output layer [1, p.309]. When an MLP incorporates a deep stack of hidden layers, it is referred to as a deep neural network (DNN) [1, p.309]. 

The task at hand involves experimenting with different  combinations of optimizer algorithms (SGD, Adam, Nadam, RMSprop), learning rates (0.1, 0.01, 0.001), and the number of epochs (8, 32, 100, 120), with the goal of identifying the configuration that yields the highest diagnostic accuracy. Through this process, we aim to enhance the MLP's ability to accurately identify diabetic conditions.


[1] A. G ́eron, Hands-On Machine Learning with Scikit-Learn, Keras, and
TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Sys-
tems. O’Reilly Media, 2019
