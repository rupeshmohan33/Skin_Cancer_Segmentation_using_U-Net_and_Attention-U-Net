# Skin Cancer Segmentation using U-Net and Attention U-Net

## Overview
This repository contains the implementation of **Skin Cancer Segmentation** using **U-Net** and **Attention U-Net** architectures. The models are designed to segment skin lesions from dermoscopic images, aiding in early detection and diagnosis of skin cancer.

## Models Included
- **U-Net** – A convolutional neural network designed for biomedical image segmentation.
- **Attention U-Net** – An improved version of U-Net incorporating attention mechanisms to enhance feature selection.

## Implementation
Each notebook includes:
- Data preprocessing (image resizing, normalization, augmentation).
- Model architecture setup and training.
- Loss functions (Binary Cross-Entropy, Dice Loss) and optimization.
- Evaluation using segmentation metrics.

## Dataset
- The model is trained on publicly available skin cancer datasets such as **ISIC Challenge datasets**.
- Images are preprocessed and augmented to improve generalization.

## Dependencies
To run the notebooks, install the necessary dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Skin-Cancer-Segmentation.git
   ```
2. Open the Jupyter Notebook and run the training script.

## Evaluation Metrics
- **Dice Coefficient**
- **Jaccard Index (IoU)**
- **Precision, Recall, and F1-score**

## Future Enhancements
- Fine-tuning with additional medical datasets.
- Deploying as a web application for real-time predictions.
- Experimenting with transformer-based segmentation models.

## Author
Mahankali N V R Pavan Sai Mohan
