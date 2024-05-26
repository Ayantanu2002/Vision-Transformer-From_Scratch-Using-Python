# Vision Transformer from Scratch

This repository contains code to implement a Vision Transformer (ViT) from scratch using PyTorch.

## Overview

The Vision Transformer (ViT) is a powerful deep learning architecture introduced in the paper ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929) by Dosovitskiy et al. Unlike traditional convolutional neural networks (CNNs), ViT relies entirely on self-attention mechanisms to capture global and local dependencies in images.

This implementation provides a basic structure to build a Vision Transformer model from scratch, including:

- Patch embedding
- Positional encoding
- Multi-head self-attention
- MLP (Multi-Layer Perceptron) head for classification
