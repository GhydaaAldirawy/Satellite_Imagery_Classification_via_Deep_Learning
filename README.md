🛰️ Satellite Imagery Classification: Agricultural vs Non-Agricultural Land
This project is an AI-powered solution for classifying satellite imagery into Agricultural and Non-Agricultural land. It explores various Deep Learning architectures, ranging from traditional CNNs to cutting-edge Vision Transformers (ViTs) and Hybrid Models.

📌 Project Overview
As part of an AI Capstone Project, this repository demonstrates the ability to process large-scale satellite datasets and build robust classification models. The goal is to assist industries like agriculture and urban planning in automating land usage analysis with high precision (>95% accuracy).

🛠️ Tech Stack
Languages: Python

Deep Learning Frameworks: PyTorch, TensorFlow/Keras

Libraries: NumPy, Matplotlib, OpenCV, Scikit-learn, Tqdm

Environment: Jupyter Notebooks / Google Colab

🏗️ Project Architecture
The project is divided into four main modules:

1. Data Engineering & Augmentation
Memory Management: Implemented Lazy Loading and Generators to handle large image datasets without crashing system memory.

Preprocessing: Resizing (64x64), normalization, and balanced sampling.

Augmentation: Applied RandomHorizontalFlip, RandomRotation, and VerticalFlip to improve model generalization.

2. CNN Implementation (Keras vs PyTorch)
Keras: Built a structured CNN with 4 Conv2D layers and 5 Dense layers for rapid prototyping.

PyTorch: Custom implementation using nn.Module for granular control over the forward pass and backpropagation.

Evaluation: Comparative analysis using Confusion Matrices, Precision, Recall, and F1-Score.

3. Advanced Models: Vision Transformers (ViT)
Implemented ViT architectures that treat images as sequences of patches.

Built CNN-ViT Hybrid Models to leverage local feature extraction (CNN) and global context understanding (Self-Attention).

4. Integration & Final Evaluation
Hyperparameter tuning (Batch size, Learning rate, Transformer depth).

Visualizing Training vs. Validation Loss to detect and prevent Overfitting.

The final accuracy achieved:
<img width="445" height="177" alt="image" src="https://github.com/user-attachments/assets/85542bf0-6e2e-4b5f-97ea-562c4163a27e" />
