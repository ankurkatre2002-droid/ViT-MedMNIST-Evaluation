# ViT-MedMNIST-Evaluation

## Overview
This repository contains the computational research and evaluation pipelines for analyzing Vision Transformer (ViT) architectures on medical imaging datasets. The primary focus is benchmarking transformer-based models against traditional CNNs for medical image classification using the MedMNIST collection.

## Architectures Evaluated
*   **ResNet-50:** Baseline Convolutional Neural Network.
*   **Vanilla ViT:** Standard Vision Transformer architecture.
*   **PLG-ViT:** Advanced Vision Transformer tailored for complex spatial pattern recognition.

## Research Objectives
This project is currently being formalized for submission to a Scopus-indexed journal. The core objectives include:
1. Measuring classification accuracy and computational overhead across varying model depths.
2. Evaluating spatial attention mechanisms in medical contexts compared to standard convolutional feature extraction.
3. Identifying context retention bottlenecks during long-horizon model training and evaluation.

## Technology Stack
*   **Core:** Python 3
*   **Deep Learning:** PyTorch, torchvision
*   **Data Processing:** NumPy, Pandas, Scikit-learn, OpenCV
*   **Environment:** Google Colab (GPU)

## Google Antigravity Integration (Upcoming)
Future iterations of this evaluation pipeline will be deployed inside Google Antigravity. By leveraging Gemini 4 Carbon's 1M-token window and native `/swarm` multi-agent orchestration, the goal is to fully automate the hyperparameter tuning and model evaluation loops. This will resolve current context exhaustion bottlenecks encountered when managing complex Python training scripts and large-scale model logs.

## License
MIT