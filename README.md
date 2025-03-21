# Biomedical-Image-processing

Brain Tumor Segmentation using BraTS-Africa Dataset

A biomedical deep learning project focused on accurate brain tumor detection and segmentation using the *BraTS-Africa dataset*. This project implements multiple neural network architectures and innovative data augmentation and compression techniques for optimized and efficient model performance.


Project Overview

This project aims to develop robust deep learning models to segment and predict brain tumors using MRI scans from the BraTS-Africa dataset. We explored and compared three leading segmentation architectures — *VNet, **UNet, and **SegNet* — to evaluate accuracy, generalization, and computational performance.

In addition to model experimentation, we introduced novel optimization techniques including:

- *Strassen Matrix Multiplication* in place of traditional convolution operations for computational efficiency
- *Huffman Coding* for compressed storage and deployment of model weights

Key Features

- Multi-model segmentation using *VNet, **UNet, and **SegNet*
- Dataset sourced from *BraTS-Africa* (MRI brain scans)
- Efficient convolution approximation using *Strassen Matrix Multiplication*
- Model compression with *Huffman Coding*
- Evaluation based on Dice Score, Precision, Recall, and IoU

 Technologies & Components

| Component / Technology          | Purpose                                              |
|---------------------------------|------------------------------------------------------|
| *BraTS-Africa Dataset*        | MRI brain tumor data from diverse African hospitals  |
| *UNet, VNet, SegNet*          | Deep learning models for segmentation                |
| *Strassen Multiplication*     | Optimization technique for convolution operations    |
| *Huffman Coding*              | Model compression and weight optimization            |
| *PyTorch / TensorFlow*        | Model implementation and training                    |
| *NumPy, OpenCV, Matplotlib*   | Data preprocessing and visualization                 |

Current Status

Completed:
- Preprocessing and loading of BraTS-Africa dataset
- Model architecture implementation: VNet, UNet, SegNet
- Integration of Strassen-based convolution layer
- Model compression using Huffman coding
- Evaluation and visualization of segmentation results

Applications

- Automated tumor diagnosis and segmentation in resource-limited settings
- Assistive tool for radiologists and neurosurgeons
- Deployable low-footprint AI models for mobile or embedded devices

Contributors

- *Nitish Dandu*
- *Sai Harsha*
- *Rahul Chowdary*
- *Salla Shivesh*

