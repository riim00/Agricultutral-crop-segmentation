# 🌱 Agricultural Crop Segmentation Platform

Welcome to the **Agricultural Crop Segmentation Platform** – a powerful tool that uses deep learning and computer vision to analyze, segment, and classify agricultural crops.  
This platform is designed to support both individuals and organizations in improving crop health assessment and agricultural decision-making.

---

## 👨‍🌾 Introduction

This is a robust web-based solution built with **Streamlit**, focused on **image segmentation** and **classification** of crops.  
By integrating deep learning models like **ResNet**, the platform offers accurate segmentation and insightful analysis for various types of agricultural products.

---

## Features ✨

### 🌾 Crop Segmentation & Classification

Harnessing the power of deep learning, the platform provides:

- ✅ **Precise segmentation** of crops from images  
- 📊 **Detailed health analysis** of segmented crops based on visual features  
- 🌍 **Smart insights** to assist farmers and researchers in decision-making 

---

## Technologies Used ⚙️

- **Streamlit** – for building the interactive web interface  
- **OpenCV** – for image and video processing  
- **ResNet, VGG16, EfficientNet** – deep learning models trained for classification and segmentation tasks  

---

## Dataset Information 📊

The project uses the [Fruits Classification Dataset](https://www.kaggle.com/datasets) available on Kaggle.

**Setup instructions:**

1. Download the dataset from Kaggle  
2. Extract the contents  
3. Place the images in:  Classification-Nutrition-Guide/agricultural_classification/

---

## 🎯 How to Use

### Crop Segmentation & Classification Flow

1. Launch the app using Streamlit  
2. Use the sidebar and select **Crop Segmentation & Classification**  
3. Upload an image of an agricultural crop  
4. The app will:
- Display the segmented image  
- Classify the crop type  
- Suggest relevant insights based on the analysis  

---

## 📈 Model Accuracy

| Model        | Accuracy  |
|--------------|-----------|
| **EfficientNet** | 97%        |
| **VGG16**        | 96%        |
| **ResNet50**     | 95%        |

All models have been trained and validated on diverse datasets, ensuring robust and consistent performance across various crop types.

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

## 👥 Team

This project was developed collaboratively by:

- **Rim Taouab** 
- **Berraho Khalil**  
- **Aymane Souiles**  
- **Akestaf Ahmed**
- **Yasser Salhi**

> Each member actively contributed to the design, development, training, and testing of the platform. A true team effort!

