# Diabetic Retinopathy Detection with Deep Learning

## Overview
Diabetic Retinopathy (DR) is one of the leading causes of vision loss globally and is commonly associated with long-term diabetes (Kropp _et al_., 2023). Early detection and intervention can prevent severe complications (Kropp _et al_., 2023). This project leverages deep learning techniques to classify the severity of diabetic retinopathy from retinal fundus images. The model implementation focuses on data preprocessing, data augmentation, and building a ResNet50-based convolutional neural network to enhance predictive accuracy.

This project aims to assist researchers and healthcare professionals in automating DR detection and improve accessibility to quality diagnosis, especially in remote areas or healthcare settings with limited resources.


## Features
-Multi-Class Classification: Automatically classifies retinal fundus images into various stages of diabetic retinopathy severity (e.g., No DR, Mild, Moderate, Severe, and Proliferative DR).

-Data Augmentation: Implements techniques such as rotation, flipping, and brightness adjustments to increase the diversity of training data and improve model robustness.

-Transfer Learning: Fine-tunes the **ResNet50** architecture pre-trained on ImageNet to achieve better generalisation on the DR dataset.



## Dataset
The dataset used for this project is sourced from the **APTOS 2019 Blindness Detection Challenge on Kaggle**, which includes thousands of high-resolution retinal fundus images labeled with five severity levels:

0 - No DR: No signs of diabetic retinopathy.

1 - Mild DR: Early-stage symptoms such as microaneurysms.

2 - Moderate DR: Signs of damage to blood vessels in the retina.

3 - Severe DR: More significant retinal damage with possible hemorrhages.

4 - Proliferative DR: Advanced DR with the formation of new abnormal blood vessels.

The dataset is highly imbalanced, with a majority of images labeled as "No DR." Balancing the dataset through augmentation and oversampling techniques is a critical step in the pipeline.


## How to Use
1. Clone the repository: 
   ```bash
   git clone https://github.com/dswaseem17/diabetic-retinopathy-detection.git

### References ###
Kropp, M. et al. (2023) ‘Diabetic retinopathy as the leading cause of blindness and early predictor of cascading complications—risks and mitigation’, EPMA Journal, 14(1), pp. 21–42. doi:10.1007/s13167-023-00314-8. 
