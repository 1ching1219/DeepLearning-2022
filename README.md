# Deep Learning Course Assignments (PyTorch-based)

This repository contains assignments completed as part of a deep learning course. Each assignment covers a core concept in modern deep learning, implemented using PyTorch. Below is a summary of each assignment.

## 📦 Contents

- [Assignment 1: PyTorch Warm-Up](#assignment-1-pytorch-warm-up)
- [Assignment 2: Binary Classification](#assignment-2-binary-classification)
- [Assignment 3: Flower Classification](#assignment-3-flower-classification)
- [Assignment 4: Multi-Task Learning Model](#assignment-4-multi-task-learning-model)
- [Assignment 5: Sentiment Classification](#assignment-5-sentiment-classification)
- [Assignment 6: Image Captioning](#assignment-6-image-captioning)

---

## Assignment 1: PyTorch Warm-Up

A simple warm-up to get familiar with PyTorch operations, including tensor manipulation and gradient tracking.

---

## Assignment 2: Binary Classification

### 🧠 Part 1: Logistic Regression from Scratch
- Implement logistic regression using only PyTorch tensors and operations.
- Train on the **UCI Adult Income Dataset** to classify individuals as "rich" or "poor".

### ⚙️ Part 2: Logistic Regression with `nn.Module`
- Re-implement logistic regression using PyTorch’s high-level API.

### 🔁 Part 3: Multi-Layer Perceptron (MLP)
- Build and train a simple MLP for improved classification performance.

---

## Assignment 3: Flower Classification

- Classify flower images into five categories: **daisy**, **tulip**, **rose**, **sunflower**, and **dandelion**.
- Dataset: 1,724 flower images (40% of a larger set).
- Images vary in size and resolution (~320x240 px).
- **Note:** No external images allowed.

---

## Assignment 4: Build Multi-Task Learning (MTL) Model

- Construct a multi-task model capable of solving multiple objectives simultaneously.
- Focus on designing a shared representation while handling diverse outputs.

---

## Assignment 5: Sentiment Classification

- Classify sentiment in tweets as **positive**, **negative**, or **neutral**.
- Options:
  - Train an RNN-based model.
  - Fine-tune a pre-trained transformer model (e.g., BERT).

---

## Assignment 6: Image Captioning

### 📷 Part 1: Image Captioning
- Build a model from scratch to generate natural language descriptions for images.
- You may use pre-trained CNNs (e.g., ResNet) and RNNs (e.g., LSTM) as backbones.

### 🎯 Part 2: Image Captioning with Attention
- Enhance the model with an attention mechanism.
- Highlight relevant spatial features in images during caption generation.

---

## 🛠 Requirements

- Python 3.8+
- PyTorch
- torchvision
- NumPy
- tqdm
- matplotlib
- scikit-learn
- nltk
- transformers (for BERT)

