# Mini Stable Diffusion from Scratch

This repository provides a **minimal PyTorch implementation** of Stable Diffusion, built from the ground up for learning and experimentation.  
It covers the major components — Variational Autoencoder (VAE), U-Net, CLIP text encoder, and the diffusion process — without relying on pre-built diffusion frameworks.

---

## Features
- Implementation of **forward and reverse diffusion** process  
- **U-Net architecture** for denoising  
- **VAE** for latent space representation  
- **CLIP text encoder** for text-to-image conditioning  
- Training loop with PyTorch  
- Inference pipeline for generating images  

---

## Dataset
We use the **CelebA dataset** as a proxy for training, since it contains over 200,000 celebrity face images with diverse attributes.

- Available via `torchvision.datasets`  
- Lightweight and easy to integrate for quick experimentation  

