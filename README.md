
# Biomedical Image Segmentation with U-Net

## Overview

This project focuses on biomedical image segmentation using the U-Net deep learning architecture.

The objective is to train a convolutional neural network to segment regions of interest in medical images using the BUSI (Breast Ultrasound Images) dataset.

## Dataset

The project uses the Breast Ultrasound Images (BUSI) dataset, available on Kaggle:

[BUSI Dataset – Kaggle](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)

The dataset contains breast ultrasound images and their corresponding ground-truth masks.

## Model Architecture

The U-Net architecture is composed of:

- Encoder (contracting path)
- Bottleneck
- Decoder (expanding path)
- Skip connections
- Sigmoid output layer for binary segmentation

## Implementation

The notebook covers the following steps:

1. Importing the required libraries.
2. Loading and preprocessing the BUSI dataset.
3. Preparing training and validation data.
4. Building the U-Net architecture.
5. Compiling and training the model.
6. Evaluating segmentation performance using Intersection over Union (IoU).
7. Visualizing segmentation predictions.
8. Visualizing feature maps from different U-Net layers.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## Project Structure

```text
biomedical-image-segmentation-unet/
│
├── tutoriel_Unet.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/ikramelghidouni59/biomedical-image-segmentation-unet.git
```

2. Open the notebook using Google Colab or Jupyter Notebook.

3. Install the required dependencies if necessary.

4. Run the notebook cells in order.

**Note:** The dataset is downloaded separately from Kaggle. Follow the instructions in the notebook to access it.

## Author

**Ikram EL GHIDOUNI**


