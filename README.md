# Cassava Leaf Disease Classification: An Architectural Benchmarking Study

This repository contains a comprehensive study on image classification for Cassava Leaf Disease. The project focuses on benchmarking a baseline Custom CNN against State-of-the-Art (SOTA) pretrained architectures and proposes an Ensemble Solution that achieves superior performance.

🚀 Project Overview

Cassava is a critical staple crop. Identifying diseases early through Computer Vision can significantly impact food security. This project aims to find the most robust architectural approach by comparing:

Baseline Model: A Custom-built CNN.

Pretrained Models: Transfer learning using EfficientNet-B4 and ResNet50.

Ensemble Models: Strategic combinations to leverage the strengths of multiple architectures.

📊 Performance Results

The experimental results demonstrate that the Ensemble approach (Custom + EfficientNet-B4) is the most effective, outperforming both standalone pretrained models and the baseline.


## 🥇 1

Ens: Custom + EffNet

Ensemble

81.36%

## 🥈 2

EfficientNet-B4

Pretrained

79.50%

## 🥉 3

Custom CNN

Baseline

77.11%

## 4

Ens: Custom + ResNet

Ensemble

76.72%

## 5

ResNet50

Pretrained

70.29%

Key Insights:

Ensemble Edge: The top-performing ensemble model provided a ~4% accuracy boost over the strongest single model (EfficientNet-B4).

Significant Growth: The final architecture achieved a 16% improvement in accuracy compared to the ResNet50 baseline.

OpenCV Integration: Used OpenCV for sophisticated image preprocessing, including noise reduction and feature enhancement, to improve model interpretability.

🛠️ Technical Stack

Language: Python

Computer Vision: OpenCV

Libraries: Scikit-learn, NumPy, Pandas, Matplotlib

