# 🚦 Image Classification: Road Sign Detection

Welcome to my image classification project focused on detecting and classifying **traffic signs** using **Convolutional Neural Networks (CNN)** and **TensorFlow**.

---

## 📌 Introduction

Traffic signs play a crucial role in maintaining safety and order on the roads. However, real-world conditions like lighting, angle, and image quality can make these signs appear differently. This project builds an image classification model using **Computer Vision** and **CNN** to automatically recognize 17 types of traffic signs from images.

The goal is to support intelligent vehicle systems, smart city projects, or traffic education apps with fast and accurate sign recognition.

---

## 🗂 Dataset

The dataset used is titled **Road Sign Detecting**, provided by the **Projects** community via **Roboflow Universe**.

- **Total Classes**: 17 traffic sign categories  
- **License**: CC BY 4.0  
- **Source**: [Roboflow Universe – Road Sign Detecting](https://universe.roboflow.com/projects-xmgv3/road-sign-detecting-aehjf)

Examples of classes:
- `speed-20`, `speed-30`, `speed-50`, ..., `speed-100`
- `stop`, `yield`, `no-entry`
- `road-works`, `slippery-road`, `double-curve`
- and more!

---

## 🛠 Tech Stack

- Python  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  
- OpenCV  
- Roboflow API

---

## 🔄 Workflow

1. **Data Preparation**  
   Downloading and organizing the dataset using Roboflow.

2. **Data Checking**  
   Visual inspection and balance checking across classes.

3. **Data Augmentation**  
   Applying image transformations to improve generalization.

4. **ImageDataGenerator**  
   Using `ImageDataGenerator` for efficient training and validation splitting.

5. **Model Development**  
   Building and training a CNN model for multi-class classification.

---

## 📦 Model Output

- ✅ Trained CNN model in:
  - `TensorFlow SavedModel`
  - `TensorFlow Lite` (for mobile/embedded)
  - `TensorFlow.js` (for web deployment)

---

## 🚀 Future Improvements

- Improve accuracy with deeper architectures (e.g., ResNet, MobileNet)
- Add bounding box detection for real-time sign localization
- Integrate into a mobile or web demo


> "Explore data, learn by doing, and keep improving — one model at a time." 🌱
