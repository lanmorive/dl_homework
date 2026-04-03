# Deep Learning Homework

## Description

This repository contains the implementation of a neural network framework from scratch using NumPy, along with several applied models built on top of it.

The project is divided into two main parts:

---

## Part 1: Core Components

Implementation of fundamental building blocks for neural networks:

* Layers:

  * Linear
  * Conv2d
  * MaxPool2d / AvgPool2d
  * BatchNormalization
  * ChannelwiseScaling
  * Dropout
  * Flatten

* Activation functions:

  * ReLU / LeakyReLU / ELU
  * SoftPlus
  * GELU
  * SoftMax / LogSoftMax

* Loss functions:

  * NLL (stable and unstable versions)

All components include forward and backward passes and were tested against PyTorch implementations.

---

## Part 2: Models and Training Pipeline

Using the implemented framework, several models were built and trained:

### 1. Optimizers

* SGD (with momentum and weight decay)
* Adam

### 2. Regression Model

* Fully connected neural network (FCNN)
* Uses BatchNorm, Dropout, and different activation functions
* Trained on a tabular dataset (e.g., California Housing)
* Experiments with small, medium, and large architectures

### 3. MNIST Classification Model

* Convolutional neural network (CNN)
* Uses Conv2d, MaxPool2d, Flatten, and SoftMax
* Trained on a reduced MNIST dataset for faster experimentation

### 4. Autoencoder

* Convolutional + fully connected architecture
* Includes BatchNorm and Dropout
* Learns compressed representations of input images

---

## Training Features

Each model includes:

* Train / validation split
* Metric tracking
* Loss curves visualization
* Early stopping
* Learning rate scheduler
* Warmup strategy
* Best model checkpointing
* Ability to switch optimizers and loss functions

---

## Structure

* `homework_modules.ipynb` — core layers and components
* `part2_models_homework.ipynb` — models and experiments

---

## Notes

* All implementations are written from scratch using NumPy
* PyTorch is used only for validation and comparison
* Datasets are automatically downloaded

---
# Deep Learning Homework

## Description

This repository contains the implementation of a neural network framework from scratch using NumPy, along with several applied models built on top of it.

The project is divided into two main parts:

---

## Part 1: Core Components

Implementation of fundamental building blocks for neural networks:

* Layers:

  * Linear
  * Conv2d
  * MaxPool2d / AvgPool2d
  * BatchNormalization
  * ChannelwiseScaling
  * Dropout
  * Flatten

* Activation functions:

  * ReLU / LeakyReLU / ELU
  * SoftPlus
  * GELU
  * SoftMax / LogSoftMax

* Loss functions:

  * NLL (stable and unstable versions)

All components include forward and backward passes and were tested against PyTorch implementations.

---

## Part 2: Models and Training Pipeline

Using the implemented framework, several models were built and trained:

### 1. Optimizers

* SGD (with momentum and weight decay)
* Adam

### 2. Regression Model

* Fully connected neural network (FCNN)
* Uses BatchNorm, Dropout, and different activation functions
* Trained on a tabular dataset (e.g., California Housing)
* Experiments with small, medium, and large architectures

### 3. MNIST Classification Model

* Convolutional neural network (CNN)
* Uses Conv2d, MaxPool2d, Flatten, and SoftMax
* Trained on a reduced MNIST dataset for faster experimentation

### 4. Autoencoder

* Convolutional + fully connected architecture
* Includes BatchNorm and Dropout
* Learns compressed representations of input images

---

## Training Features

Each model includes:

* Train / validation split
* Metric tracking
* Loss curves visualization
* Early stopping
* Learning rate scheduler
* Warmup strategy
* Best model checkpointing
* Ability to switch optimizers and loss functions
---
