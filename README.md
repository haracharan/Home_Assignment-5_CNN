# Home_Assignment-5_CNN
# AI Ethics & Security Assignments

This repository contains two Python-based implementations for coursework involving Generative Adversarial Networks (GANs) and data poisoning simulations in sentiment analysis.

---

## 1. Basic GAN on MNIST

### 📌 Description
This project implements a simple Generative Adversarial Network (GAN) using PyTorch to generate handwritten digits similar to those in the MNIST dataset.

### 🚀 Features
- Custom Generator and Discriminator architectures
- Adversarial training with alternating optimization
- Image samples saved at Epochs 0, 50, and 100
- Loss curve plotted for Generator and Discriminator

### 🧠 Technologies
- PyTorch
- torchvision
- matplotlib

### 📂 Output
- `gan_outputs/sample_epoch_0.png`
- `gan_outputs/sample_epoch_50.png`
- `gan_outputs/sample_epoch_100.png`
- `gan_outputs/loss_plot.png`

---

## 2. Data Poisoning Simulation: Sentiment Classifier

### 📌 Description
This project simulates a data poisoning attack on a logistic regression-based sentiment classifier. It flips sentiment labels for texts containing a specific entity (e.g., "UC Berkeley") to observe model degradation.

### ⚠️ Attack Method
- Injected label-flipping for sentences containing "UC Berkeley"
- Evaluated performance before and after poisoning

### 📈 Outputs
- Accuracy before and after the attack
- Confusion matrix heatmaps before and after poisoning

### 🧠 Technologies
- scikit-learn
- pandas
- seaborn
- matplotlib

---

## 📊 Ethical Discussion Highlights

### GAN Training Architecture
- Generator tries to fool the Discriminator
- Discriminator learns to distinguish real from fake
- Competitive training leads to realistic outputs

### AI Harm Examples
- Memorization of private data (e.g., names, emails)
- Generation of copyrighted text (e.g., Harry Potter)
- Bias metric: False Negative Rate Parity using Aequitas

---

## 📁 Structure
