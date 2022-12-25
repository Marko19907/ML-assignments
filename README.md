# ML assignments

This repository contains the mandatory assignments from NTNU's "Machine Learning" (IE500618) course, fall 2022. 

These assignments are mandatory but do not count towards the final grade in the subject.


## Contents

### [A1: Mushroom Classification](/A1-Mushroom-Classification)
* [x] Use the [UCI Mushroom data set](https://archive.ics.uci.edu/ml/datasets/mushroom)
* [x] Use a multilayer perceptron (MLP) classifier.
* [x] Clean and split the data into training, validation, and testing.
* [x] Present the results:
    * [x] Plot the accuracy and loss.
    * [x] Create a confusion matrix.

### [A2: Distributed ML](/A2-Distributed-ML)
* [x] Simulate distributed machine learning using ensemble learning and compare it to a monolithic model.
* [x] Use the [MNIST data set](http://yann.lecun.com/exdb/mnist/)
* [x] Use a multilayer perceptron (MLP) classifier.
* [x] For the ensemble model:
  * [x] Divide the data into 3 local sections, by digits: 0-2, 3-5, and 5-9.
  * [x] Train each local model with only one of the sections.
  * [x] Aggregate the 3 local models into a single ensemble model.
* [x] Present the results:
  * [x] Plot the accuracy and loss.
  * [x] Create a confusion matrix.
  * [x] Make comparisons between the ensemble model and the monolithic model trained on the full dataset.

### [A3: ResNet50 (transfer learning) with CIFAR100](/A3-ResNet50-(transfer-learning)-with-CIFAR100)
* [x] Use the ResNet50 model (transfer learning) for classification.
* [x] Use the [CIFAR-100 data set](https://www.cs.toronto.edu/~kriz/cifar.html)
* [x] Present the results:
  * [x] Plot the accuracy and loss.
  * [x] Create a confusion matrix.
