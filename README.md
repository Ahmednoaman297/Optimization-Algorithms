# Optimization Algorithms Comparison on CIFAR-10

This repository demonstrates the performance comparison of various optimization algorithms using a shallow neural network trained on the CIFAR-10 dataset. The training times, accuracy, and other metrics are analyzed for each optimizer.

## Optimization Algorithms Evaluated
1. **Stochastic Gradient Descent (SGD) with Warm Restarts**
2. **Nesterov Accelerated Gradient (NAG)**
3. **RMSProp**
4. **Nadam**
5. **Learning Rate Schedulers**
   - Exponential Decay
   - Step Decay

## Dataset
The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class:
- 50,000 training images
- 10,000 test images

## Project Objectives
1. Compare the performance of different optimization algorithms.
2. Measure and record the training time for each optimizer.
3. Analyze accuracy and loss curves.
4. Evaluate the impact of learning rate schedules.

## Model Architecture
The shallow neural network architecture includes:
- Input Layer: 32x32x3
- Hidden Layers: Fully connected layers with ReLU activation
- Output Layer: 10 classes with Softmax activation
- Loss Function: Categorical Crossentropy

## Requirements
To run the project, install the following dependencies:
```bash
pip install tensorflow numpy matplotlib
