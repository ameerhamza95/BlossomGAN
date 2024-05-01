# BlossomGAN: Generating photorealistic flower images through GANs

This repository contains the code, trained models, and outputs for a project focused on generating photorealistic images of flowers using Generative Adversarial Networks (GANs). The project explores three different GAN architectures: Vanilla DCGAN, DCGAN enhanced with Wasserstein GAN with Gradient Penalty (WGAN-GP), and StyleGAN.

##Project Overview
The goal of this project is to assess the capabilities of various GAN architectures in producing high-quality, photorealistic images of flowers. This involves evaluating the performance, stability, and image fidelity of each model, using the PyTorch Challenge Flower Dataset from Kaggle as the training data.

##GAN Architectures Explored:
Vanilla DCGAN: A basic GAN model that serves as a baseline.
DCGAN with WGAN-GP: An advanced model incorporating gradient penalties to improve training stability.
StyleGAN: A state-of-the-art model known for its ability to generate highly realistic images.

##Key Features:
Implementation of different GAN architectures.
Analysis of model performance through Fréchet Inception Distance (FID) scores.
Exploration of the truncation trick to balance image diversity and quality.

##Results:
Vanilla DCGAN was discontinued due to insufficient progress.
DCGAN with WGAN-GP achieved an FID score of 164.
StyleGAN demonstrated superior performance with an FID score of 139.

##Repository Contents:
Code: All scripts used to define, train, and evaluate the GAN models.
Trained Models: Checkpoints of the trained models for reproducibility and further experimentation.
Outputs: Generated images at various stages of training for each model.
Analysis: Jupyter notebooks detailing the training process, performance evaluation, and visual results.
