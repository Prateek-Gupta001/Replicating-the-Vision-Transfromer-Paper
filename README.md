# Vision Transformer (ViT) Implementation 🌟✨

This repository contains a **PyTorch reimplementation** of the seminal paper, ["An Image is Worth 16x16 Words"](https://arxiv.org/abs/2010.11929) by Dosovitskiy et al.

## Overview 🖼️
The paper utilizes a **vanilla Transformer** for image classification and achieves state-of-the-art results. It demonstrates that Transformers can outperform previous state-of-the-art CNNs when trained on a large corpus of image data.

## Key Concepts 🔑
- **Image Processing:** Images are divided into patches, which are then converted into vector embeddings by combining patch embeddings with position embeddings.
- **Custom Implementation:** All components, including patch and position embeddings, have been created from scratch.
- **Training:** At the end, We fine-tune a pretrained Vision Transformer (ViT) on our custom food dataset. (due to lack of compute resources to train it from scratch on a large dataset)

## Architecture 📊
![Architecture Overview](https://raw.githubusercontent.com/mrdbourke/pytorch-deep-learning/main/images/08-vit-paper-figure-1-architecture-overview.png)

![Equations](https://raw.githubusercontent.com/mrdbourke/pytorch-deep-learning/main/images/08-vit-paper-four-equations.png)

## Conclusion 🏁
This implementation aims to provide insights into how Transformers can be effectively applied to image classification tasks, paving the way for future research and applications.
