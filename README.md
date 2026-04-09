# Medical Image-Segmentation using Deep Learning

A deep learning-based medical imaging project for automatic brain tumor segmentation from multimodal MRI scans using a U-Net architecture. This system is designed to assist in medical image analysis by providing accurate, pixel-level tumor localization.

---

## 🚀 Project Overview

This project focuses on developing an end-to-end pipeline for brain tumor segmentation using the BraTS2020 dataset. It processes multimodal MRI scans, applies preprocessing and augmentation techniques, and generates precise segmentation masks using a convolutional neural network.

The main objective is to support healthcare professionals by improving the speed and consistency of tumor detection in medical imaging.

---

## 🏗️ Model Architecture

- **Model Type:** U-Net (Encoder–Decoder Architecture)  
- **Task:** Semantic Segmentation  
- **Input:** Multimodal MRI brain scans  
- **Output:** Pixel-wise tumor segmentation mask  
- **Focus:** High-resolution medical image segmentation  

---

## 📊 Performance Metrics

The model demonstrates strong performance on validation data:

- **Dice Score:** 0.9237  
- **Accuracy:** 96.32%  

These results indicate reliable segmentation performance and strong overlap between predicted and ground truth tumor regions.

---

## 🧪 Data Processing Pipeline

The dataset (BraTS2020) was processed using the following steps:

- Intensity normalization using MinMax scaling  
- Handling class imbalance in medical segmentation data  
- Processing multimodal MRI image slices  
- Data augmentation to improve model generalization  
- Preparation of volumetric medical imaging data for training  

---

## ⚙️ Key Features

### 🔹 End-to-End Workflow
Complete pipeline from MRI input to tumor mask output.

### 🔹 Medical Image Optimization
Special preprocessing techniques for noisy and imbalanced medical data.

### 🔹 High Precision Segmentation
Accurate pixel-level prediction of tumor boundaries.

### 🔹 Interactive Deployment
Streamlit-based web application for real-time inference and visualization.

---

## 🌐 Web Application

The project includes an interactive Streamlit interface that allows users to:

- Upload MRI scans  
- Generate segmentation masks instantly  
- Visualize tumor regions in real time  

This makes the system accessible for research, learning, and demonstration purposes.

---

## 💡 Applications

- Clinical decision support systems  
- Early brain tumor detection  
- Radiology workflow automation  
- Medical research and dataset analysis  
- Treatment planning assistance  

---

## 🧠 Technical Highlights

- U-Net based deep learning model  
- Custom training strategy for imbalanced medical data  
- Robust preprocessing pipeline for MRI modalities  
- Real-time inference using Streamlit  

---

## 📌 Conclusion

This project demonstrates the application of deep learning in medical imaging for accurate brain tumor segmentation. It aims to bridge the gap between AI research and practical healthcare applications through an efficient and deployable solution.
