# Brain Tumor Classification using Convolutional Neural Networks

## Overview

This project focuses on the development and evaluation of a Convolutional Neural Network (CNN) model for multi-class classification of brain tumors from MRI images. The goal is to accurately classify tumors into four distinct categories: pituitary, meningioma, glioma, and no tumor. Early and accurate diagnosis is crucial for effective treatment planning and improved patient outcomes. This project addresses the challenges associated with limited dataset sizes, variations in tumor appearance, and potential class imbalance to achieve high diagnostic performance.

## Project Structure

The project is structured as follows:

- `brain-tumor-classification.ipynb`: Jupyter Notebook containing the code for data loading, preprocessing, model building, training, and evaluation.
- `data/`: Directory containing the training and testing datasets.
  - `Training/`: Contains subdirectories for each class (pituitary, meningioma, glioma, notumor), with MRI images in each.
  - `Testing/`: Contains subdirectories for each class (pituitary, meningioma, glioma, notumor), with MRI images in each.
- `README.md`: This file, providing an overview of the project.

## Data Description

The dataset consists of MRI images of the brain, categorized into four classes:

- **Pituitary Tumor:** Tumors arising from the pituitary gland.
- **Meningioma:** Tumors arising from the meninges, the membranes surrounding the brain and spinal cord.
- **Glioma:** Tumors arising from glial cells, which support nerve cells in the brain.
- **No Tumor:** MRI images showing no evidence of a brain tumor.

The dataset is divided into training and testing sets. The distribution of images across the classes is as follows:

- **Training Set:**
  - Pituitary: 1457
  - Notumor: 1595
  - Meningioma: 1339
  - Glioma: 1321
- **Testing Set:**
  - Pituitary: 300
  - Notumor: 405
  - Meningioma: 306
  - Glioma: 300

The images are in `.jpg`, `.jpeg`, or `.png` format.

## Dependencies

The project uses the following Python libraries:

- tensorflow
- pandas
- numpy
- matplotlib
- seaborn
- keras

You can install these dependencies using pip:
