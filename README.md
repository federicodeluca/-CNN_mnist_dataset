# 🧠 CNN Classification on MNIST & Fashion-MNIST

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-Enabled-red)
![Colab](https://img.shields.io/badge/Notebook-Colab-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Convolutional Neural Networks (CNN) applied to MNIST and Fashion-MNIST datasets for image classification.

---

## 📌 Overview

This project is part of a series of hands-on deep learning exercises, starting from a theoretical overview of Convolutional Neural Networks (CNNs), followed by practical implementation and model comparison. 

We apply and optimize various CNN architectures to two benchmark datasets: **MNIST** and **Fashion-MNIST**, with the goal of improving classification accuracy through architectural changes like convolutional layers, dropout, pooling, and deeper designs.

---

## 📂 Project Structure

The notebook includes:

- 📊 **Data Loading** from torchvision datasets
- 🧱 **CNN Architecture Design** with ReLU, MaxPooling, Dropout
- 🧪 **Model Training** and evaluation with test accuracy
- 📈 **Model Comparison** across three CNN variants
- 🧵 **Transfer to Fashion-MNIST** for architectural robustness

---

## 🧪 Models Overview

| Model        | Description                         | Accuracy  |
|--------------|-------------------------------------|-----------|
| CNN_3Conv    | 3 conv layers + ReLU + MaxPooling   | 0.9814    |
| CNN_3Conv_Dropout | Same as above + 50% Dropout      | 0.9829    |
| CNN_Deep     | 6-layer deep CNN + Dropout          | 0.9894 ✅ |

---

## 🧠 Theory Highlights

- **CNN Layers**: Feature extraction through local receptive fields.
- **Activation (ReLU)**: Introduces non-linearity.
- **Pooling**: Reduces spatial dimensions.
- **Dropout**: Helps prevent overfitting.
- **Evaluation**: Test accuracy and model comparison guide the design iteration.

---

## 📁 Dataset Used

- **MNIST**: Handwritten digit images (28x28, grayscale)
- **Fashion-MNIST**: Fashion product images (28x28, grayscale)

Both datasets are loaded directly via `torchvision.datasets`.

---

## 🚀 How to Run

You can open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1P_smtfl71kGOWisejECKJtNUVkclxq-P)

---

## 📌 Author

**Federico De Luca**  
_MSc in Management Engineering – Data Analytics_  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/federico-de-luca-23certosa)

---

## 📜 License

This repository is licensed under the MIT License. See the `LICENSE` file for more information.

