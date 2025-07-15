---
title: title: "🎉 The research on MultiScale-GreenViT: A Vision Transformer Framework for High-Precision Urban Green Space Segmentation and Quantification has been successfully completed"
summary: "A more in-depth study is currently underway~"
date: 2025-04-05
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"
authors:
  - admin
tags:
  - Academic
---


🎉 Welcome 👋

{{< toc mobile_only=true is_open=true >}}

## Research Background 📌 

Urban green spaces play a crucial role in mitigating urban heat islands, purifying air, and improving public health. With the rapid pace of urbanization, accurate monitoring of green areas has become increasingly important for sustainable city planning.

However, traditional monitoring methods—such as manual surveys or HSV-based image analysis—face serious limitations in accuracy, scalability, and adaptability to complex urban scenes. Convolutional Neural Networks (CNNs), though successful in remote sensing tasks, suffer from limited receptive fields and struggle to model long-range dependencies, often resulting in poor boundary delineation.

To address these challenges, this study introduces MultiScale-GreenViT, an improved Vision Transformer (ViT)-based framework designed to perform precise segmentation and area measurement of urban green spaces.

[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Research Methodology 🔍

1️⃣ **Multi-Scale Feature Fusion**
- A pyramid-based architecture is adopted to combine local and global features across multiple resolutions (14×14 to 224×224 pixels). This enhances the model’s ability to detect narrow, scattered, or shadowed green patches in urban environments.

2️⃣ **Hybrid Loss Function**
- A weighted combination of Cross-Entropy Loss and Dice Loss addresses class imbalance and improves both pixel-wise accuracy and region-level consistency in segmentation.

3️⃣ **Accurate Area Measurement**
- The framework integrates geospatial information to convert pixel-level segmentation outputs into real-world area estimations, achieving 99.64% accuracy in green space measurement.

4️⃣ **Optimized Deep ViT Architecture**
- The model utilizes 24 transformer layers with 16 attention heads, enabling better learning of long-range dependencies and complex spatial relationships.

5️⃣ **Data Augmentation & Sliding Window Sampling**
- To handle ultra-high-resolution images, a sliding window method (224×224 window with 112 stride) is used, along with data augmentation techniques such as flipping, rotation, and color jitter to improve generalization.

## Experimental Environment 💻

**Hardware**
  GPU: NVIDIA GeForce RTX 3090
  RAM: 128 GB
  OS: Windows 11

**Environment**
  Python 3.9
  PyTorch 2.3.1
  CUDA 11.8
  OpenCV 4.10.0

⚠️ **When the paper is officially published, I will share more details and provide the link to the full article** 🦄✨


