# 🫁 Respiratory Disease Detection from Chest X-rays

A deep learning-based project that classifies chest X-ray images into five disease categories using advanced CNN architectures. The model aims to assist in the early detection of respiratory conditions including COVID-19 and tuberculosis, enhancing diagnostic efficiency and accuracy.

---

## 📌 Overview

This project uses convolutional neural networks and transfer learning techniques to classify chest X-ray images into the following five categories:

- **Normal**
- **Viral Pneumonia**
- **Bacterial Pneumonia**
- **COVID-19**
- **Tuberculosis (TB)**

Due to limited dataset size, **data augmentation**, **dropout**, and **early stopping** were applied to reduce overfitting and improve generalization.

---

## 🗃️ Dataset

- Sourced from **Kaggle** (link can be added here)
- Contains labeled X-ray images across 5 classes
- Balanced through data augmentation techniques (e.g., rotation, flipping, zooming)

---

## 🧠 Models & Performance

| Model                           | Accuracy (%) |
|--------------------------------|--------------|
| **Custom CNN**                 | 87%          |
| **DenseNet**                   | 94%          |
| **MobileNet + EfficientNet**   | 90%          |
| **ResNet + DenseNet Hybrid**   | 93%          |
| **ResNet**                     | 95%          |

All models were evaluated using validation accuracy and trained with early stopping to prevent overfitting.

---

## ⚙️ Techniques Used

- **Data Augmentation** – To increase data diversity
- **Dropout Layers** – To prevent overfitting
- **Early Stopping** – To halt training once validation loss stops improving
- **Transfer Learning** – Leveraging pretrained models like ResNet, DenseNet, and EfficientNet
- **Hybrid Architectures** – Combining model strengths for improved accuracy

---

##  Tech Stack

- **Python**  
- **TensorFlow / Keras**  
- **Matplotlib, NumPy, Pandas**    

---


  
