# CXR-Img-Classif

This repository contains a PyTorch image classification pipeline for chest X-ray classification using a ResNet-18 backbone. It includes data loading, preprocessing, training, validation, testing, and early stopping.

## Features
- Custom dataset loading for image folders
- Training/validation/test pipeline
- Data preprocessing and augmentation
- ResNet-18 fine-tuning
- Accuracy tracking and evaluation
- Early stopping and model checkpoint saving

## Dataset
The dataset is not included in this repository.

Expected folder structure:

```text
chest_xray/
  train/
    class_0/
    class_1/
  test/
    class_0/
    class_1/
