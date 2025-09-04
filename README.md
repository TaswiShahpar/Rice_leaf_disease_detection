# Rice_leaf_disease_detection
## Overview

This project focuses on detecting and classifying rice leaf diseases using Computer Vision and Deep Learning. Agriculture is a backbone of many countries, and rice is a staple crop for billions of people. Early detection of rice leaf diseases can help farmers take timely action, prevent large-scale crop damage, and increase yield.

We explored image processing, machine learning, and deep learning techniques to segment, classify, and analyze rice leaf diseases effectively.

## Objectives

- Detect and classify rice leaf diseases from images.

- Segment infected vs healthy regions using OpenCV & Deep Learning.

- Explore CycleGAN for disease-specific image transformation.

- Provide a scalable and farmer-friendly solution to support smart agriculture.

## Dataset
We used multiple rice leaf datasets:

### Rice_Leaf_AUG Dataset

### Categories:

- Healthy Rice Leaf

- Bacterial Leaf Blight

- Leaf Blast

- Leaf Scald

- Narrow Brown Leaf Spot

- Neck Blast

- Rice Hispa

- Sheath Blight

## Methodology
### Preprocessing:-

- Image resizing and normalization

- Color filtering for extracting leaf regions

- Gaussian blur for noise removal

### Segmentation

- OpenCV-based filtering to isolate diseased regions

- U-Net / Mask R-CNN models for precise infected-area segmentation

### Classification

- Machine Learning models (Random Forest, SVM) for baseline results

- Deep Learning (CNN-based models) for improved accuracy

- Performance evaluated with accuracy, precision, recall, and F1-score

### CycleGAN Experiments

- Applied CycleGAN for style transfer across disease categories

- CPU-compatible implementation for low-resource environments (Google Colab)

## Workflow
In GANs, there are two networks: the generator (whichcreates fake images) and the discriminator (which tries to tell if images are real or fake). Normally, if you only have small dataset, the discriminator can start "memorizing" the few real images it has seen instead of learning general patterns. This leads to overfitting, which means the GAN doesn't learn to create realistic new images.

<img width="300" height="350" alt="image" src="https://github.com/user-attachments/assets/3290f45c-38f0-4f69-a351-b8f3ea262a9f" />



## Results
- **Segmentation**: U-Net performed better than traditional OpenCV methods

<img width="560" height="270" alt="image" src="https://github.com/user-attachments/assets/9e33cdb0-59ce-4c24-ae11-63d2894745d7" />


- **Classification**: CNN outperformed ML models with higher accuracy

- **CycleGAN**: Useful for data augmentation and disease simulation

<img width="560" height="270" alt="image" src="https://github.com/user-attachments/assets/4ce4922e-7c4f-4520-b24b-ba4b081286d3" />


