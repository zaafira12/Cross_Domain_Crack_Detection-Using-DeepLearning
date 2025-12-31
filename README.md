# Cross_Domain_Crack_Detection_Using_DeepLearning

This repository contains the implementation of a deep learning-based system for automated crack detection across visually different domains — concrete structures and photovoltaic (PV) solar panels.
The models where trained on  concerete dataset and tested on solar panel images.

The project evaluates multiple CNN and detection architectures trained on concrete crack images and tested on solar panel images to analyze domain shift and generalization performance.

##  Project Overview

- Task: Crack detection and classification
- Training Domain: Concrete crack images
- Testing Domain: Solar panel crack images
- Goal: Evaluate cross-domain generalization and identify the most robust architecture

### Models Used
- EfficientNet-B0
- EfficientNet-B3
- MobileNetV2
- Faster R-CNN

##  Methodology

1. Data preprocessing and augmentation using `ImageDataGenerator`
2. Transfer learning with pretrained ImageNet weights
3. Training using Adam optimizer with EarlyStopping
4. Evaluation using accuracy, precision, recall, F1-score, and confusion matrices
5. Visualization of predictions using OpenCV


##  Results Summary

| Model            | Accuracy (%) |
|------------------|--------------|
| EfficientNet-B3  | 50.25        |
| MobileNetV2      | 67.00        |
| Faster R-CNN     | 80.00        |
| EfficientNet-B0  | **98.46**    |

EfficientNet-B0 demonstrated the best cross-domain generalization and is recommended for real-world deployment.


##  Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas, Matplotlib
- Google Colab / GPU

## Authors

Sk. Zaafira Yumn

Rachumallu Viswanadh

Botlagunta Thoushik

M. Narendra Kumar


