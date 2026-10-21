# Practical-No-04-Image-Generation-using-Deep-Convolutional-GAN-DCGAN-.
Implement and train a Deep Convolutional Generative Adversarial Network (DCGAN) on a standard image dataset. Generate synthetic images using the trained model and evaluate the performance by analyzing the Generator and Discriminator loss curves and the quality of the generated images.
## Introduction

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate synthetic flower images. It consists of a Generator that creates images from random latent vectors and a Discriminator that distinguishes real images from generated images. The objective is to understand adversarial training and explore AI-based image generation using deep learning.

## Dataset

The project uses the **Oxford Flowers 102** dataset, which contains images from 102 different flower categories. The images are resized to 64 × 64 pixels and normalized to the range [-1, 1] to match the Generator's `tanh` output activation. The preprocessed images are used to train the DCGAN model.

## Results

The trained DCGAN generates synthetic flower images that can be visualized using a grid of generated samples. Generator and Discriminator loss curves are used to monitor the training process. The generated images may capture flower-like colors and patterns, although some outputs may be blurry or repetitive. Image quality depends on the model architecture, dataset, and training duration.
