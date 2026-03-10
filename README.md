# Weather-Image-Classification-using-CNN

This repository contains the code and report for a deep learning assignment focused on classifying weather images into four categories: cloudy, rain, shine, and sunrise. The project explores dataset curation, CNN model building with regularization techniques, and performance evaluation.

## Overview

The dataset consists of 1125 images divided into 4 classes. The project involves:
- Dataset preparation: Loading, checking for corrupted files, splitting into train/test (70/30), and visualization.
- Model development: Building a CNN with convolutional and max pooling layers, using ReLU and Softmax activations.
- Regularization: Data augmentation (rotation, shift, shear, zoom, flip), early stopping, and batch normalization to address overfitting.
- Evaluation: Accuracy and loss metrics for training and testing.

Key findings: The optimized model with batch normalization and early stopping achieved approximately 0.8 accuracy on the test set, resolving overfitting issues observed in initial models.

Dataset source: Weather images (details in the report).

## Requirements

- Python 3.x
- Libraries: NumPy, TensorFlow/Keras, Matplotlib, OS, Shutil, Random, Glob, PIL

## usage
Run the notebook:
- `DeepLearningAssignment_1158931_V3.ipynb`: Full implementation including data processing, model training, and evaluation.
Note: The dataset (`dataset2.zip`) should be unzipped and organized into class directories.

## Results

- Initial CNN: High training accuracy (1.0) but lower test accuracy (0.926), indicating overfitting.
- With augmentation: Improved test accuracy (0.917).
- With early stopping: Efficient training (11 mins), test accuracy 0.947.
- Optimized model (batch norm): Test accuracy 0.788, balanced performance without overfitting.

Detailed comparisons and plots in the report and notebook.

## Files

- `Chandreen_Liyanage_1158931Report-2-18.pdf`: Comprehensive report with methodology, results, and discussion.
- `DeepLearningAssignment_1158931_V3.ipynb`: Jupyter notebook with code implementation.
