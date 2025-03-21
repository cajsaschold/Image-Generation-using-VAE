# Variational Autoencoder for Image Generation

This project explores image generation using Variational Autoencoders (VAEs) and compares the results to a diffusion-based generative model, using the CIFAR-10 dataset. The models are evaluated both qualitatively (generated image samples) and quantitatively using the Structural Similarity Index (SSIM).

## Repository Structure

- **`Project_Report.pdf`**  
  Contains the full project report, including methodology, implementation details, results, evaluation, and ethical discussion.

- **`VAE/`**  
  Implements a **Variational Autoencoder** from scratch using PyTorch.  
  - Model architecture  
  - Training scripts  
  - Image sampling and visualization  
  - SSIM evaluation

- **`diffusion_model/`**  
  Contains an implementation of a **diffusion-based generative model**.  
  - Model setup and training  
  - Image generation and comparison with VAE

## Objectives

- Train and evaluate a **VAE** on CIFAR-10.
- Generate and visualize samples from the trained model.
- Evaluate image quality using **SSIM**.
- Compare the VAE to a **diffusion model** in terms of visual quality and performance.
- Reflect on the **ethical implications** of generative models.

## Technologies Used

- Python  
- PyTorch  
- NumPy  
- Matplotlib  
- CIFAR-10 Dataset

---

 *See the full analysis and findings in `Project_Report.pdf`.*
