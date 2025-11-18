# AAI521-Group6-ComputerVision-Project


# 🫁 Chest X-Ray Lung Segmentation & Labels  
### *AAI521 – Computer Vision Project (Group 6)*  
Dataset link: https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels

---

## 🚀 Badges

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 👥 Team Members (Group 6)

- **Ved Prakash Dwivedi**  
- **Anugrah Rastogi**  
- **Malla Manu**

---

## 📌 Overview  
This repository contains the complete implementation for **lung segmentation** using the *Chest X-Ray Masks and Labels* dataset.  
The project is developed as part of the **AAI521 – Computer Vision** course and combines preprocessing, segmentation model training, evaluation, and visualization.

The dataset includes chest X-ray images and corresponding lung masks, enabling:

- Lung segmentation  
- Region extraction for disease analysis  
- Preprocessing for downstream classification tasks  

---

## 🎯 Project Objectives

- Develop a robust preprocessing pipeline for chest X-rays  
- Train deep-learning models (e.g., U-Net) for lung segmentation  
- Evaluate segmentation using Dice, IoU, and visual overlays  
- Create reusable & modular code for medical-image workflows  
- Provide a foundation for classification or pathology detection  

---

## 📂 Dataset Summary

### **Selected Dataset:**  
**Chest X-Ray Masks and Labels** (Kaggle)  
https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels

### **Dataset Description:**  
- Chest X-ray images in `.png` / `.jpg` format  
- Corresponding **binary lung masks**  
- Normal & abnormal labels  
- High-resolution medical images suitable for segmentation  

### **Key Details**

| Field | Description |
|------|-------------|
| Total Annotated Images | ~704 images with masks |
| Additional Unmasked Images | ~192 |
| File Size | ~7.5 GB |
| Image Dimensions | Vary (≈1024–3000 px) |
| Labels | Normal / Abnormal |
| Masks | Binary lung segmentation masks |

---

## 🧪 Why This Dataset Matters

Chest X-rays are among the most widely used radiological scans worldwide.  
Accurate lung segmentation improves:

- Disease classification  
- Noise reduction (removing non-lung regions)  
- Model interpretability  
- Localization of abnormalities  

This dataset is ideal for both learning and research.

---

## 🛠️ Recommended Project Structure

AAI521-Group6-Chest-XRay-Segmentation/
│
├── data/
│ ├── images/
│ ├── masks/
│ └── metadata/
│
├── notebooks/
│ ├── 01_exploration.ipynb
│ ├── 02_preprocessing.ipynb
│ ├── 03_train_unet.ipynb
│ └── 04_evaluation.ipynb
│
├── src/
│ ├── dataset.py
│ ├── transforms.py
│ ├── model_unet.py
│ └── train.py
│
├── saved_models/
├── README.md
└── requirements.txt

2. Install dependencies
pip install -r requirements.txt

3. Download the dataset
Place Kaggle images and masks inside:

data/images/
data/masks/

4. Run notebooks

Start with:
notebooks/01_exploration.ipynb

🔬 References

Kaggle Dataset — Chest X-Ray Masks and Labels
U-Net: Convolutional Networks for Biomedical Image Segmentation
Recent lung segmentation literature & research

🤝 Contributing

Contributions are welcome!
Please open an issue or submit a pull request.
If you use this repository or dataset, kindly cite the original Kaggle author.
