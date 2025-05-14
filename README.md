# 🫁 Pneumonia Detection from Chest X-rays using Deep Learning ⚕️

## 📌 **Project Overview**
Welcome to the **Pneumonia Chest X-ray Classification** project! This deep learning-based solution classifies chest X-ray images to detect the presence of pneumonia. It is designed to assist radiologists and healthcare professionals with rapid and accurate diagnosis.

## 📂 **Dataset Information**

📄 **Dataset Name:** Chest X-ray Images (Pneumonia) – Kaggle  
🧷 **Classes:**
- Normal
- Pneumonia

## 🖼️ **Image Features**

Each X-ray image is labeled as either showing signs of pneumonia or as normal. The model identifies visual indicators like:
- Lung opacity
- Fluid buildup
- Structural anomalies

## 🔍 **Model Implementation**

📜 **File:** PRAICP_1012_Pneumonia_chest_x_ray_classification.ipynb

🛠️ **Steps Followed:**
- 🧹 **Data Preprocessing** – Image resizing, normalization, augmentation
- 📊 **EDA (Exploratory Data Analysis)** – Class distribution, sample images
- 🧠 **Model Building** – A CNN model tailored for binary classification
- 🎯 **Model Evaluation** – Accuracy, loss curves, confusion matrix
- 📷 **Prediction** – Classifying new or unseen X-ray images

## 🤖 **Deep Learning Architecture**

- 📦 Convolutional Layers
- 🌀 Max Pooling Layers
- 🧮 Dense Layers for decision making
- 💧 Dropout for regularization
- 🧠 Sigmoid Activation for binary classification

## 📉 **Metrics Used**

- 📌 Accuracy
- 📌 Loss
- 📌 Confusion Matrix
- 📌 Precision, Recall, F1-Score

## 🧪 **Technologies Used**

- TensorFlow / Keras
- NumPy & Pandas
- OpenCV
- Matplotlib & Seaborn
- Jupyter Notebook

## 🔑 **Key Insights**

- 🧠 CNN effectively detects pneumonia with high accuracy.
- 📊 Data augmentation helped combat overfitting.
- ✅ The model generalizes well to unseen data.

## 🎯 **Conclusion**

This project illustrates the power of CNNs in the medical imaging domain. The model can be further optimized and deployed in clinical settings to assist doctors in early and efficient pneumonia diagnosis, especially in remote or resource-limited areas.

---
