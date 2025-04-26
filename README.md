# Emotion_Recognisation

## Facial Emotion Recognition - Data Preprocessing and Augmentation

This repository contains a Jupyter Notebook that prepares a **Facial Emotion Recognition** dataset for machine learning workflows. It handles downloading, cleaning, augmenting, normalizing, and converting the dataset into a TensorFlow-ready format.

---

## Overview

The notebook performs:

- 📥 Downloading the dataset from Kaggle
- 🧹 Cleaning unnecessary files
- 🛠️ Augmenting images (rotation, brightness, contrast, flipping)
- 📏 Normalizing images based on ImageNet mean and std
- ⚡ Creating batched and prefetched TensorFlow datasets

---

## Features

- Download and automatically extract dataset
- Advanced data augmentation for better model generalization
- Image normalization for efficient training
- TensorFlow-ready dataset creation
- Easy to extend and modify

---

## Requirements

Install the necessary libraries:

```bash
pip install tensorflow numpy opencv-python pillow matplotlib kaggle
```
---
## Usage
Clone this repository:
```bash
https://github.com/CaptianErek/Emotion_Recognisation.git
cd your-repo-name
```
Place your kaggle.json file into the working directory
---
