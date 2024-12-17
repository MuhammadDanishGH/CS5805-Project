# Comparative Analysis of MaluNet and UNeXt for Medical Image Segmentation

This repository contains the code, logs, and results from our project analyzing the performance of UNeXt and MALUNet for medical image segmentation on the BUSI and ISIC18 datasets. We used these models on the datasets and recorded outputs to evaluate and compare the two models based on F1-Score and Intersection over Union (IoU).

## This project has been implemented as the part of the course Machine Learning CS5805

## Usage
We used UNeXt and MALUNet for medical image segmentation. Below is how we conducted our analysis:

1. **Models**:  
   - UNeXt and MALUNet were applied to the BUSI and ISIC18 datasets.
   - Both models were trained for 50 epochs using their default hyperparameters.
   
2. **Datasets**:  
   - **BUSI**: Medical images of breast cancer using ultrasound scan.
   - **ISIC18**: Medical dermoscopic images (skin lesions).

3. **Outputs**:  
   - F1-Score and IoU were computed to evaluate segmentation quality.
   - Logs were recorded.

## Dataset

- [BUSI](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)
- [ISIC18](https://challenge.isic-archive.com/data/)

## References

- [UNeXt: MLP-based Rapid Medical Image Segmentation Network](https://arxiv.org/abs/2203.04967)
- [MALUNet: A Multi-Attention and Light-weight UNet for Skin Lesion Segmentation](https://arxiv.org/abs/2211.01784)
