# MNIST-Digit-Generator-GAN
A GAN-based model that generates handwritten digit images similar to the MNIST dataset.

This project uses a **Generative Adversarial Network (GAN)** to generate handwritten digit images similar to those in the MNIST dataset.

## 🧾 Overview

A **GAN** consists of two models:
- **Generator**: Creates fake images from random noise.
- **Discriminator**: Distinguishes between real and fake images.

They are trained together in a game-like setup until the generator produces realistic images.

## 🛠️ Tech Stack

- Python 🐍
- TensorFlow / Keras
- NumPy
- Matplotlib

## 🧪 How It Works

1. Load and preprocess MNIST data.
2. Build the generator and discriminator models.
3. Combine them into a GAN model.
4. Train:
   - Discriminator on real and fake data.
   - Generator via GAN to fool the discriminator.
5. Save generated images every 100 epochs.

## 📦 Installation

```bash
pip install tensorflow numpy matplotlib
