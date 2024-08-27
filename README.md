# GAN_Intro

This repository provides an introduction to Generative Adversarial Networks (GANs) using PyTorch. It contains two Google Colab notebooks that demonstrate the implementation of:

1. **Simple GAN** on the MNIST dataset.
2. **Wasserstein GAN (WGAN)** on the CelebA dataset using Wasserstein Loss.

## Contents

- `Simple_GAN_MNIST.ipynb`: A basic implementation of a GAN on the MNIST dataset. This notebook walks through the process of creating a simple GAN architecture, training it, and generating new images of handwritten digits.

- `WGAN_CelebA.ipynb`: An implementation of a Wasserstein GAN (WGAN) on the CelebA dataset. This notebook demonstrates the usage of the Wasserstein Loss function to improve the stability of GAN training and generate realistic images of faces.

## Requirements

To run these notebooks, you will need the following dependencies:

- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib
- Google Colab (recommended for ease of use)

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/Daimon5/GAN_Intro.git
    ```
2. Open the desired notebook in Google Colab by uploading it or using the GitHub link directly.

## How to Use

- **Simple GAN**: 
    - Follow the notebook to understand how a basic GAN works.
    - Train the GAN on the MNIST dataset.
    - Generate new images of handwritten digits.

- **Wasserstein GAN (WGAN)**:
    - Explore the advantages of using Wasserstein Loss in GANs.
    - Train the WGAN on the CelebA dataset.
    - Generate realistic images of human faces.

## References

- [Original GAN Paper](https://arxiv.org/abs/1406.2661)
- [Wasserstein GAN Paper](https://arxiv.org/abs/1701.07875)
- [PyTorch Documentation](https://pytorch.org/docs/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
