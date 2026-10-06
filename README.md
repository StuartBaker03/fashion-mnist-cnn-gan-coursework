# Fashion-MNIST CNN & GAN Coursework

PyTorch coursework exploring **CNN-based image classification** and **GAN-based image generation** on the Fashion-MNIST dataset.

## Overview

The project consists of three parts:

- Building and optimising a 5-layer CNN for Fashion-MNIST classification
- Training an unconditional GAN to generate Fashion-MNIST-style images
- Modifying the GAN using a least-squares loss and evaluating its effect on image quality and diversity

The trained CNN is also used to evaluate generated images by measuring classifier confidence and predicted class distribution.

## Highlights

- Best CNN test accuracy: **92.19%**
- Compared multiple learning rates and the effect of batch normalisation
- Evaluated GAN outputs throughout training using the CNN classifier
- Compared a standard BCE GAN with an **LSGAN-style** objective
- Investigated the trade-off between generated-image quality and diversity

## Tech

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Running the Project

Install the dependencies:

```bash
pip install torch torchvision numpy matplotlib tqdm jupyter
```

Then launch Jupyter:

```bash
jupyter notebook
```

Open the notebook and run the cells in order. Fashion-MNIST is downloaded automatically through `torchvision`.

## Repository Structure

```text
fashion-mnist-cnn-gan-coursework/
├── README.md
└── 285160.ipynb
```

The notebook contains the full implementation, experiments, figures, results, and discussion.

## About

Completed as part of a university Neural Networks assessment focused on convolutional neural networks, generative adversarial networks, model optimisation, and experimental evaluation.