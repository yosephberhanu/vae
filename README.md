# Variational Autoencoders (VAE) and Conditional Variational Autoencoders (CVAE)

This repository contains Jupyter notebooks that demonstrate the concepts and implementation of **Variational Autoencoders (VAE)** and **Conditional Variational Autoencoders (CVAE)**, widely used in generative modeling.

---

## Notebooks

1. **[VAE](vae/vae.ipynb)**
   
   This notebook explains and implements the Variational Autoencoder (VAE) using PyTorch. It demonstrates how to:
   - Encode data into a probabilistic latent space.
   - Decode latent space representations to reconstruct original inputs.
   - Generate new data by sampling from the latent space.

2. **[CVAE](cvae/cvae.ipynb)**  
   
   This notebook extends the VAE to Conditional Variational Autoencoders (CVAEs), allowing for conditional generation of data. Key features include:
   - Conditioning the model on class labels to control the output.
   - Generating data specific to a given condition.
   - Analyzing the impact of conditional information on generative capabilities.

---

## What Are VAEs and CVAEs?

### Variational Autoencoders (VAEs)
A Variational Autoencoder is a generative model that learns to encode input data into a latent space as probability distributions (rather than fixed points). By sampling from these distributions, VAEs can:
- Reconstruct the input data with minimal error.
- Generate entirely new data similar to the training set.

### Conditional Variational Autoencoders (CVAEs)
A Conditional Variational Autoencoder builds upon the VAE by introducing conditional information (e.g., class labels) into the encoding and decoding processes. This allows for more controlled data generation, enabling the model to produce outputs aligned with specific conditions.

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yosephberhanu/vae.git
   
---

## Resources for Further Reading

To learn more about the concepts behind VAEs and CVAEs, check out these resources:
- Kingma, Diederik P., and Max Welling.[Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114) - The foundational paper introducing VAEs.
- Doersch, Carl. [Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908) - A comprehensive tutorial explaining VAEs in detail.
- A quick Tuorial on Autoencoders, VAEs and beyond by [Arxiv Insight](https://www.youtube.com/watch?v=9zKuYvjFFS8)
- [A crash course on VAEs and more](https://ammesatyajit.medium.com/a-crash-course-on-vaes-vq-vaes-and-vae-gans-3fdcc40b059e)