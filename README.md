# Tensorflow/Keras: Digit Recognition

This is a submission to [Kaggle's Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) competition using a neural network built in Keras.

From Kaggle:

> MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

First submission was a sequential Network with two hidden layers. The first hidden layer has 128 nodes, the second has 32 nodes. The linear rectifier is used as the activation function for the hidden layers, followed by softmax for the output layer.  This network has 0.96171 accuracy on the kaggle testing data.  The second submission made with a CNN with two hidden layers, two pooling layers, and two pooling layers.  This got the same accuracy on the Kaggle test set as the first network.  

NOTE: MNIST data not included in REPO, get from the kaggle link above.
