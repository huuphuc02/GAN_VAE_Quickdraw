# Generative Models for Quick Draw Dataset

This repository contains implementations of Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs) for generating new samples from the Google Quick Draw dataset.

## Overview

In this project, I implement and compare different generative models (GAN and VAE architectures) to generate new drawings from five selected classes of the Quick Draw dataset. The project includes data preprocessing, model implementation, training, evaluation, and visualization of generated samples.

## Dataset

We use the Google Quick Draw dataset, which contains millions of drawings across 345 categories. For this project, we selected 5 classes:
- Crown
- Apple
- Chair
- Panda
- Bowtie

## Repository Contents

- `Quickdraw_GAN_VAE.ipynb`: Main Jupyter notebook containing all code, explanations, and results
- `VAE_model.h5`: Saved weights for the best performing VAE model
- `GAN_discriminator_model.h5`, `GAN_generator_model.h5`: Saved weights for the best performing GAN model
- `README.md`

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Pytorch
- NumPy
- Matplotlib
- Pandas
- scikit-learn
- tqdm

## Acknowledgments
This project was created as part of the Advanced Machine Learning and Data Mining course at Université Clermont Auvergne.
