# Agricultural Crop Segmentation Platform 🌱

Welcome to the **Agricultural Crop Segmentation Platform**! This platform is designed to assist individuals and organizations in analyzing and segmenting agricultural crops through modern machine learning and computer vision technologies. With advanced deep learning models, users can seamlessly segment and classify agricultural products.

## Introduction 👨‍🌾👩‍🌾

The **Agricultural Crop Segmentation Platform** is a robust web application designed using **Streamlit**, focusing on **image segmentation and classification** of agricultural crops. This tool utilizes **deep learning-based segmentation** to provide accurate analysis of crop health and classification.

---

## Features ✨

### Crop Segmentation & Classification 🌾🍃
This feature leverages powerful deep learning models like **ResNet** to segment and classify agricultural crops. Once the segmentation is complete, the platform provides the following benefits:
- **Accurate Segmentation**: The tool identifies and segments the agricultural crops in an image, ensuring precise results.
- **Detailed Crop Health Analysis**: After segmentation, users can analyze the health of crops based on extracted features.
- **Improved Agricultural Insights**: Provides insights to farmers and researchers for better decision-making.

---

## Technologies Used ⚙️

The Agricultural Crop Segmentation Platform is built using cutting-edge technologies to ensure performance, scalability, and ease of use. Here's an overview of the technologies used:

- **Streamlit**: A powerful Python framework for building interactive data applications.
- **OpenCV**: A computer vision library used for image and video processing.
- **Pre-trained Deep Learning Models**: ResNet models trained on large datasets to provide accurate segmentation and classification results.

---

## Dataset Information 📊

This project uses the **Fruits Classification Dataset** to train and evaluate classification models. The dataset can be downloaded from Kaggle using the link below:

[Download Fruits Classification Dataset](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

### Instructions:
1. Download the dataset from Kaggle.
2. Extract the dataset and place the images into the **`Classification-Nutrition-Guide/agricultural_classification/`** directory.

---

## How to Use 🎯
**Crop Segmentation & Classification Usage 📸**
- From the sidebar, click on Crop Segmentation & Classification.
- Upload an image of an agricultural crop.
- The platform will display the segmented output, along with detailed classification results.
- The platform will also suggest insights based on the segmentation.

---

## Accuracy 📊
The evaluation of the deep learning models used for segmentation and classification demonstrates high performance:

**EfficientNet:** Achieves **97% accuracy**, providing highly reliable results for agricultural product classification.

**VGG16:** Reaches **96% accuracy**, offering robust classification performance.

**ResNet50:** Maintains **95% accuracy**, with solid performance across various agricultural product categories.

These models have been rigorously evaluated and validated on large datasets of agricultural products, ensuring that the platform can reliably classify and segment various crops with high accuracy.

---

## Directory Structure 🗂️

The project has the following directory structure:

agricultural-crop-segmentation/Classification-Nutrition-Guide/  
├── app.py                         # Main Streamlit application file  
├── requirements.txt               # List of required Python dependencies  
├── agricultural_classification/   # Folder for classification models  
│   └── app/                       # Classification app (Streamlit)  
├── segmentation_model.py         # Custom segmentation model  
└── models/                        # Folder containing pretrained models.

---

## Author ✍️
Developed by **Berraho Khalil**

