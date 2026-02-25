# ResNet-14 on CIFAR-10 with PyTorch and Weights & Biases

## Overview

This project implements a **ResNet-14 convolutional neural network** from scratch using **PyTorch** to classify images from the **CIFAR-10** dataset.

**Weights & Biases (W&B)** is used to track, visualize, and monitor the training process, including loss curves, accuracy metrics, and experiment configurations.

This assignment demonstrates:

- Implementation of residual connections  
- CNN training on CIFAR-10  
- Experiment tracking and visualization with W&B  

---

## Dataset

### CIFAR-10

- 60,000 32x32 color images  
- 10 classes  
- 50,000 training images  
- 10,000 test images  

**Classes:**

- Airplane  
- Automobile  
- Bird  
- Cat  
- Deer  
- Dog  
- Frog  
- Horse  
- Ship  
- Truck  

---

## Model Architecture

ResNet-14 consists of:

- Initial convolution layer  
- Residual blocks with skip connections  
- Batch normalization  
- ReLU activations  
- Global average pooling  
- Fully connected classification layer  

Residual connections help mitigate vanishing gradients and enable deeper network training.

---

## Technologies Used

- Python  
- PyTorch  
- torchvision  
- Weights & Biases (wandb)  
- NumPy  
- Matplotlib (optional)  

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/resnet14-cifar10-pytorch.git
cd resnet14-cifar10-pytorch
