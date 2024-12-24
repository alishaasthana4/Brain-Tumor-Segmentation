# BRAIN TUMOR SEGMENTATION USING U-NET
## Overview 🧠
This project implements a Brain Tumor Segmentation model using the U-Net architecture. It leverages the BraTS2020 dataset, a Kaggle notebook environment, and Tesla T4 x2 GPU accelerators for training and evaluation. The goal is to accurately segment brain tumor regions from MRI images, enabling effective medical analysis and research.

## Features 🎯
- **Deep Learning Architecture**: U-Net, a convolutional neural network designed for biomedical image segmentation.
- **Dataset**: BraTS2020, a publicly available dataset for brain tumor segmentation.
- **High Performance**: Achieved superior evaluation metrics with optimized GPU acceleration.
- **Collaborative**: Open for contributions and enhancements.

## Sample Dataset 📂

The BraTS dataset includes MRI images in four modalities:

1. `T1-weighted images`: These images provide detailed structural information of the brain.
2. `T2-weighted images`: These images provide information about the structure and pathology of the brain, often used to identify edema.
3. `FLAIR images` : Useful for detecting lesions in the brain, including tumors.
4. `Contrast-enhanced T1-weighted images` : These images help identify tumor regions, especially enhancing tumors.

Here is an example of the dataset used in this project:

## Evaluation Metrics ⚙️
The performance of the U-Net model was evaluated using standard metrics:

- **Dice Similarity Coefficient (DSC)**: 0.9764 (excellent overlap between predicted and ground truth regions).
- **Accuracy**: 0.9864 (reliable classification of tumor and non-tumor regions).
- **Sensitivity (Recall)**: 0.98 (high detection rate for true positives).
- **Specificity**: 0.99 (accurately identifying non-tumor regions as true negatives).
- **Precision**: 0.97 (accuracy of positive predictions).

## Technologies Used 💻
- **Deep Learning Framework**: TensorFlow/Keras
- **Hardware**: Tesla T4 x2 GPU accelerators
- **Development Environment**: Kaggle Notebook

## Model Output ⭐
Below is a visualization of the segmentation results:



## Results 🚀
The U-Net model demonstrated outstanding performance:
- **DSC**: 0.9764
- **Accuracy**: 0.9864
- **Sensitivity**: 0.98
- **Specificity**: 0.99
- **Precision**: 0.97

These results emphasize the robustness and reliability of the model for brain tumor segmentation tasks.









