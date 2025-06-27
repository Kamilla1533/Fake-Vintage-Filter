# VintageVision: Applying Vintage Film Filters with StyleGAN
## Project Overview
VintageVision is an innovative project that leverages the power of Generative Adversarial Networks (GANs) to transform ordinary digital photographs into unique art pieces, mimicking the defects and aesthetics of old film cameras. The project's goal is not merely to apply simple filters, but to recreate photorealistic artifacts such as film grain, fading, scratches, dust, and vignetting, to give photos an authentic vintage look.
This project demonstrates the practical application of advanced computer vision and deep learning techniques for image stylization and content generation tasks.
## Demo (Future)
[Link to gallery of generated images]
## Features
  - Photorealistic Vintage Defect Imitation: The trained model generates high-quality grain, color shifts, scratches, and other old film artifacts.
  - Flexible Application: Capability to apply vintage effects to new digital images.
  - Utilization of Advanced GAN Architectures: The project is built upon one of the most modern image generation architectures.
  - Scalability: Suitable for processing large volumes of images.
## Technologies
  - Python: Primary development language.
  - PyTorch: Deep learning framework.
  - StyleGAN2: Generative Adversarial Network (GAN) architecture for high-quality image generation.
  - Google Colab: Used for model training.
  - Image Processing Libraries: Pillow, imageio, scipy.
## Used Third-Party StyleGAN Implementation
This project utilizes a simple PyTorch implementation of StyleGAN2 by lucidrains (Abelard) [https://github.com/lucidrains/stylegan2-pytorch]. This version was chosen for its clean code, ease of use, and its adaptation for more modern Python and PyTorch environments, which successfully allowed to circumvent compatibility issues with the official StyleGAN2-ADA version in Google Colab.
