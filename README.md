# CIFAR-10 Image Classification with PyTorch

## Overview

This project shows how to build a simple Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using PyTorch. The CIFAR-10 dataset from the U of T contains 60,000 32x32 color images in 10 classes, with 6,000 images per class. This project is based on the PyTorch tutorial found [here](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html).

## Project Structure

- `main.py`: The main script that includes the entire process, from data loading to model evaluation.
- `README.md`: This file, providing an overview and instructions.

## Getting Started

### 1. Clone the Repository

If you haven't already cloned the repository, do so:

```bash
git clone https://github.com/trinadas0/pytorch-image-classification.git
cd image-classification
```

### 2. Run the Script

You can run the script by executing the following command in your terminal:

```bash
python main.py
```

The script will:
- Download and the CIFAR-10 dataset.
- Define a simple CNN model.
- Train the model on the CIFAR-10 training data.
- Display the model's accuracy.

### 3. Results

After running the script, you should see the training loss decrease with each epoch. The final accuracy of the model on the test set will be printed out.

Example output:
```
[Epoch 1, Batch 2000] loss: 2.230
...
Finished Training
Accuracy of the network on the 10000 test images: 57.24%
```

## Customization

- **Training Duration**: You can increase the number of epochs by modifying the `epoch` value in the training loop.

## Acknowledgments

This project is based on the PyTorch CIFAR-10 tutorial: [CIFAR-10 Tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html).

The CIFAR-10 dataset used in this project was created by the University of Toronto. Special thanks to them for providing this valuable resource to the machine learning community.
