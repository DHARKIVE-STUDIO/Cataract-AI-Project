# 👁️ Cataract-AI: Automated Ocular Diagnostic Studio
**Deep Learning for Early-Stage Cataract Detection**

## 📌 Project Overview
Cataracts are a leading cause of vision impairment globally. This project leverages **Computer Vision** to provide an automated screening tool that can identify cataracts from digital ocular images. By utilizing a **Convolutional Neural Network (CNN)**, the model classifies images into "Cataract" and "Normal" categories, aiming to bridge the gap in accessible eye care through rapid AI diagnostics.

---

## 🔬 Technical Workflow

### 1. Medical Image Preprocessing
Ocular images often contain noise or varying lighting conditions. The pipeline includes:
* **Grayscale Conversion & Normalization:** Standardizing pixel values for model consistency.
* **Gaussian Blurring:** Reducing noise to focus the CNN on significant structural anomalies in the lens.
* **Data Augmentation:** Using random rotations and zooms to help the model generalize across different camera angles and patient positions.



### 2. Architecture: Custom CNN
The model architecture is designed to capture fine-grained textures in the eye:
* **Feature Extraction:** Multiple Convolutional layers to identify clouding patterns in the lens.
* **Pooling:** Dimensionality reduction to ensure the model remains computationally efficient.
* **Dense Layers:** Fully connected layers with a Dropout rate of 0.5 to prevent overfitting on the training set.
* **Activation:** Sigmoid output for precise binary classification.

---

## 📊 Evaluation Metrics
In medical AI, "Accuracy" isn't enough; we focus on reliability:
* **Sensitivity (Recall):** Ensuring we minimize "False Negatives" (missing a cataract).
* **Specificity:** Ensuring healthy eyes are not misclassified.
* **Confusion Matrix:** Providing a transparent view of the model's diagnostic performance.



---

## 🛠 Tech Stack
* **Deep Learning:** TensorFlow / Keras
* **Image Processing:** OpenCV, PIL
* **Data Analysis:** NumPy, Pandas
* **Visualization:** Matplotlib, Seaborn

## ⚠️ Disclaimer
This project is for educational and research purposes only. It is intended to assist medical professionals, not to replace professional clinical diagnosis.

---
Maintained by **DHARKIVE-STUDIO**

