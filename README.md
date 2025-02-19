# 🌍 SAR Image Colorization with Deep Learning

## 🚀 Project Overview
This project tackles the challenge of **colorizing grayscale Synthetic Aperture Radar (SAR) images**, making them visually interpretable and useful for further analysis. By leveraging a **GAN-based architecture**, we can transform SAR images into colorized optical-like images, enhancing their usability in real-world applications such as environmental monitoring and disaster response.

## 🏗️ Model Architecture
- **Generator:** Variational AutoEncoder (VAE) for structured and meaningful colorization
- **Discriminator:** PatchGAN to ensure realistic and high-quality outputs

## 📂 Dataset
- **Size:** ~20,000 pairs of SAR-optical images
- **Preprocessing Pipeline:** Image normalization, resizing, and conversion to tensors

## 📊 Training and Performance
- **Loss Functions Used:**
  - L1 Loss (for pixel-wise accuracy)
  - Adversarial Loss (GAN-based improvement)
  - Perceptual Loss (to maintain feature integrity)
  - Chromatic Loss (to ensure realistic colors)

- **Discriminator Loss:** Incorporates **VGG-19 feature weights** for enhanced perceptual quality
- **Optimizer:** Adam optimizer with a decay rate of **0.01**
- **Evaluation Metric:** Achieves an impressive **PSNR ~30 dB** (example value) for high-quality colorized outputs

## 🌟 Why This Project Matters
🎨 **Bridging the Gap:** SAR images lack intuitive interpretability. This model enables colorized outputs that make analysis more accessible.

⚡ **Cutting-Edge GANs:** Integrates **Variational AutoEncoders** and **PatchGAN** to ensure high-quality results.

📊 **Real-World Applications:** Useful in **remote sensing, climate monitoring, and disaster management**, making critical SAR data more actionable.

## 🔗 Get Started
Want to try it out? Clone the repo, preprocess your dataset, and generate stunning SAR colorizations! 🚀🌍

---

Contributions and feedback are welcome! Let's push the boundaries of satellite image processing together! 🛰️

