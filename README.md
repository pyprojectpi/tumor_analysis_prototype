# Brain Tumor Analysis & Diagnosis System

This project implements an AI-powered system for **brain tumor classification, detection, and segmentation** using MRI images. It combines state-of-the-art deep learning models to provide an end-to-end pipeline wrapped in an interactive web application.

---

## 🚀 Project Overview

- **Tumor Classification:** Uses a custom-trained **ResNet-18** CNN model to classify brain MRI images into four classes:  
  - Glioma Tumor  
  - Meningioma Tumor  
  - No Tumor  
  - Pituitary Tumor

- **Tumor Detection:** Employs the **YOLOv12** object detection model to localize tumor regions in the MRI scans.

- **Tumor Segmentation:** Applies the **Segment Anything Model (SAM)** with a ViT-H backbone for fine-grained segmentation of the detected tumor area.

- **Web Interface:** Uses **Gradio** to provide an easy-to-use, interactive web UI where users can upload MRI images and get real-time predictions and visualizations.

---

