# mask-rcnn-image-segmentation
# Mask R-CNN Image Segmentation

This project implements an instance segmentation model using Mask R-CNN to detect and segment objects in images.

The model is trained using deep learning techniques to identify and separate human instances from images.

---

## Overview

Image segmentation is a key task in computer vision that divides an image into multiple meaningful regions.  
This project implements an instance segmentation system based on **Mask R-CNN**, which improves traditional R-CNN based detection models by adding a pixel-level segmentation branch.

The model is capable of performing:

- object detection
- instance segmentation
- image feature extraction

---

## Model Architecture

The model is based on the **Mask R-CNN framework**, which extends Faster R-CNN with an additional segmentation branch.

Key components include:

- Backbone network: **ResNet-50 + Feature Pyramid Network (FPN)**
- Region Proposal Network (RPN)
- ROIAlign layer
- Instance segmentation mask branch

Compared with traditional R-CNN models, Mask R-CNN improves:

- detection accuracy
- segmentation precision
- feature alignment

---

## Dataset

The model is trained using the **VOC2012 dataset**, a commonly used benchmark dataset for object detection and segmentation.

Dataset features include:

- annotated bounding boxes
- pixel-level segmentation labels
- multiple object categories

---

## Training Environment

Operating System: Ubuntu 20.04  

Framework:

- PyTorch
- Python

Hardware:

- NVIDIA RTX 3090 GPU (24GB)

Training parameters:

---

## Evaluation Metrics

The model performance is evaluated using standard object detection metrics:

- IoU (Intersection over Union)
- Precision
- Recall
- mAP (Mean Average Precision)

Example threshold:

---

## Results

The trained model successfully performs instance segmentation on human objects.

Outputs include:

- bounding box detection
- pixel-level segmentation masks
- object classification

The model demonstrates strong capability in separating people from background scenes.

---

## Technologies

- Python
- PyTorch
- Deep Learning
- Computer Vision
- Mask R-CNN
- CNN (Convolutional Neural Networks)

---

## Author

Flandre Dong  
New York University – Urban Data Science
