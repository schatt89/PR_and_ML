# Pattern Recognition and Machine Learning
Homework solutions for Introduction to Pattern Recognition and Machine Learning course at Tampere University

## K-nearest neighbours

In knn.ipynb there is an implementation of the 1-nearest neighbour algorithm to classify the images from CIFAR-10 dataset. The best result I got with 1-nn is 15% accuracy.

## Bayes classifier

In bayes_classifier.ipynb I use implementation of Naïve Bayes classifier to predict classes of the images of CIFAR-10 dataset base on the mean colours. Then I add the dependency between the mean colours and try it with more features (the 32x32 images are compressed to 2x2, 4x4, 8x8 and 16x16). The best result is acquired with images compressed to 4x4 - 34.16 % accuracy.

## Simple Neural Network

In simple_neural_networks.ipynb I implement a couple of different TensorFlow models with maximum accuracy reaching up to 45% on validation. 

## RL taxi Q-Learning algorithm

In rl_taxi_q_learning.ipynb I implement the Q-Learning algorithm to learn an rl-agent taxi (open.ai gym model). The maximum mean reward I could reach is 8.5