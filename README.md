# CIFAR-10 Capacity Enhanced SE-ResNet

This repository contains a custom implementation of a **ResNet** architecture augmented with **Squeeze-and-Excitation (SE)** attention blocks for image classification on the **CIFAR-10** dataset.

The model is engineered for enhanced learning capacity using state-of-the-art optimization techniques, achieving high accuracy with a custom lightweight design.

## 📊 Performance

Evaluated on the CIFAR-10 test set after 10 epochs:

| Metric | Value |
| :--- | :--- |
| **Test Accuracy** | **88.61%** |
| **Test Loss** | **0.7758** |

## 🚀 Key Features

* **Architecture:** Customized ResNet with **Squeeze-and-Excitation (SE)** blocks for channel-wise attention.
* **Activation:** Implements **GELU** (Gaussian Error Linear Unit) for better gradient flow.
* **Optimization:** Uses **AdamW** optimizer with **Cosine Decay** learning rate schedule.
* **Regularization:** Incorporates **Spatial Dropout** and **Label Smoothing (0.1)** to prevent overfitting.

## 🛠️ Requirements

* Python 3.x
* TensorFlow / Keras 2.x
* Matplotlib
* NumPy

Install dependencies:
```bash
pip install tensorflow matplotlib numpy
