# 🧠 Brain Tumor Detection Using CNN

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to automatically detect **brain tumors from MRI images**. Manual MRI analysis is time-consuming and subjective, so this system aims to provide a faster and more consistent classification of MRI scans into:

* ✅ Tumor
* ❌ No Tumor

The model is trained and evaluated using a real MRI dataset and deployed in **Google Colab**.

---

## 👩‍🎓 Team Members

* **Ananya Vaidya** – 1032232438 (G2 Batch)
* **Ananya Porwal** – 1032232297 (G2 Batch)

Course: **Deep Neural Networks – LCA 1**

---

## 🎯 Objectives

* Build a CNN model for brain tumor classification
* Preprocess MRI images
* Train the model on a real dataset
* Evaluate performance using standard metrics
* Predict tumor on new MRI images

---

## 📂 Dataset

**Source:** Kaggle Brain MRI Dataset

### Classes:

* Tumor
* No Tumor

### Dataset Split:

| Type            | Count                        |
| --------------- | ---------------------------- |
| Total Images    | 253                          |
| Training Images | 202 (124 Tumor, 78 No Tumor) |
| Testing Images  | 51 (31 Tumor, 20 No Tumor)   |

Split Ratio: **80% Training / 20% Testing**

Images are uploaded locally in Google Colab.

---

## 🛠 Preprocessing Steps

* Resize images to **224 × 224**
* Normalize pixel values
* Data augmentation:

  * Rotation
  * Zoom
  * Horizontal flip
* Convert folders into labeled datasets

---

## 🧠 CNN Architecture

```
Conv2D
MaxPooling
Conv2D
MaxPooling
Conv2D
MaxPooling
Flatten
Dense (128)
Dropout
Sigmoid Output
```

---

## ⚙️ Training Configuration

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Epochs: 12
* Batch Size: 16
* Platform: Google Colab (GPU)

---

## 📊 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report
* ROC Curve
* Accuracy Graph
* Loss Graph

---

## ✅ Results

* Final Test Accuracy: ~80–85%
* Model successfully classifies MRI images
* Single image prediction implemented
* CNN learns features such as edges, shapes, and tumor patterns

---

## 👍 Advantages

* Automated detection
* Reduces human error
* Fast diagnosis
* Scalable system

---

## ⚠️ Limitations

* Small dataset
* Binary classification only
* Requires medical validation

---

## 🔮 Future Scope

* Multi-class tumor detection
* Larger datasets
* Real hospital integration
* Transfer learning

---

## 📊 Presentation

Download the project PPT:

* **Brain_Tumor_CNN_Presentation.pptx**

---

## 📁 Files in This Repository

* `DNN_LCA1.ipynb` – CNN implementation notebook
* `Brain_Tumor_CNN_Presentation.pptx` – Project presentation
* `README.md` – Project documentation

---

## 🏁 Conclusion

The CNN model successfully classifies brain MRI images with approximately **85% accuracy**, demonstrating the potential of deep learning in medical imaging and automated diagnosis.

---
