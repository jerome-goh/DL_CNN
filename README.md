# Deep Learning with hyperparameter search and optimization

## Motivation
For most image classification tasks in computer vision, especially in Kaggle competitions, transfer learning is a popular and preferred method of training a neural network on an image dataset to make predictions.

However, there are instances such as this project where transfer learning fails to produce good results or when the pre-trained model architecture is incompatible with the training data.

This project explores the use of an automated hyperparameter search algorithm (namely GridSearch and RandomSearch) in keras.Tuner, aided by hypermodels, to accurately predict esoteric images. 

See *"resnet.ipynb"* for the Python script
