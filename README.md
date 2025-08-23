# GAN on MNIST

This repository contains an implementation of a **Generative Adversarial Network (GAN)** trained on the **MNIST dataset**.  
The purpose of this project is to show the basics of adversarial training and how a generator can learn to create realistic handwritten digits from noise.

---

## 📌 Project Overview
- **Generator (G):** Takes random noise (`z`) as input and outputs fake images resembling MNIST digits.
- **Discriminator (D):** Takes an image (real or fake) and outputs a probability indicating whether it is real or generated.
- **Training Process:**  
  - The generator tries to fool the discriminator by producing realistic images.  
  - The discriminator tries to correctly classify real vs. fake.  
  - Both networks improve in a **minimax game** until the generator produces convincing samples.

---

## 🛠️ Technologies Used
- Python 3
- PyTorch
- Torchvision
- Matplotlib (for visualization)

---
