# 🔢 手写数字识别 (Handwritten Digit Recognition)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaka20022002/new-2025-11-25/blob/main/MNIST_Digit_Recognition.ipynb)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 项目介绍 (Introduction)
这是一个基于 **TensorFlow (Keras)** 的深度学习入门项目。它使用经典的 **MNIST 数据集** 训练了一个神经网络模型，能够识别 0-9 的手写数字。

本项目特别针对**新手入门**设计，代码包含详细注释，并解决了常见的“手写图片识别率低”的问题。

## ✨ 核心功能 (Key Features)
*   **高准确率**：模型在测试集上准确率达到 **98%** 以上。
*   **智能图像预处理**：包含自定义的图像处理算法。
    *   ✅ 自动转灰度与二值化（去除阴影和噪点）。
    *   ✅ **智能裁剪 (Smart Crop)**：自动定位数字并居中，模拟 MNIST 数据格式。
*   **实战测试**：支持上传本地拍摄的手写图片进行预测。

## 🛠️ 环境依赖 (Requirements)
本项目主要依赖以下库：
*   `tensorflow`
*   `numpy`
*   `matplotlib`
*   `pillow` (用于图像处理)

## 🚀 如何运行 (How to Use)

### 方式一：直接在 Colab 运行（推荐）
点击上方蓝色的 **"Open in Colab"** 按钮，即可直接在 Google Colab 中打开并运行代码，无需配置本地环境。

### 方式二：本地运行
1. 克隆项目：
```bash
git clone https://github.com/kaka20022002/new-2025-11-25.git
