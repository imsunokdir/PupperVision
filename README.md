# PupperVision

# End-to-End Multiclass dog breed Classification

This notebook builds an end-to-end multiclass image classifier using tensorflow and tensorflow hub

## 1. Problem

Identifying the breed of dog given an image of a dog.

## 2. Data

The data we are using is from kaggle dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so its probably best we use deep/learning/transfer learning.
* There are 10 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ image in the traininig set (these images have labels)
* There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them)
