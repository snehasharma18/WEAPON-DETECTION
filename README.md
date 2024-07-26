# Weapon-Detection

This project focuses on weapon detection using Convolutional Neural Networks (CNN) and Vision Transformers. Leveraging a dataset of 4679 images exported from Roboflow.com, with 4666 images annotated in COCO format, the models are trained to identify weapons accurately.

Dataset and Pre-processing
Dataset Source: Roboflow.com
Total Images: 4679 (4666 annotated)

Pre-processing Steps:
Auto-orientation of pixel data (EXIF-orientation stripping)
Resizing to 416x416 pixels
No image augmentation techniques applied

Models and Performance
CNN:
Accuracy: 90%
Correct Predictions: 766 out of 896

Vision Transformers:
Accuracy: 86%
Weighted Average F1-score: 85%
