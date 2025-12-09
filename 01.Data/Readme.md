# Chest Xray Masks and Labels Dataset

**Source:** [Kaggle – Chest Xray Masks and Labels](https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels/data)

## 1. Overview
This dataset contains chest X-ray images along with **pixel-level lung masks** and label information.  
It is widely used for training and evaluating **medical image segmentation** and **classification** models.

The dataset is suitable for:
- Lung segmentation tasks  
- Preprocessing pipelines for disease detection  
- Computer vision research in radiology  

---

## 📁 2. Dataset Contents
- A set of frontal chest X-ray images (`.png` / `.jpg`)
- Corresponding **binary lung masks**  
- Some images **do not have masks** — mask availability is not 100%
- Label metadata indicating normal/abnormal lung conditions (varies by dataset subset)

---

## 📊 3. Key Statistics
- Often referenced as containing **~704 X-ray images with masks**  
- Some sources list an extended version with **896 images** and **1627 labeled lung objects**  
- Mask availability is uneven — important for segmentation workflows  
- Images vary in resolution and quality (typical for real clinical imaging)



---

## 🩺 4. Use Cases
- Training U-Net / Attention U-Net for lung segmentation  
- Preprocessing for downstream disease classification (e.g., pneumonia, tuberculosis)  
- Region-of-interest (ROI) isolation for cleaner training  
- Benchmarking segmentation models in medical AI research  

---

## 🧹 5. Recommended Preprocessing
- Validate image–mask pairs (skip images without masks if required)
- Resize images and masks consistently  
- Normalize pixel intensity  
- Use medically appropriate augmentations (rotation, elastic transforms)  
- Ensure augmentations apply **identically** to image and mask  

---

## ⚠️ 6. Limitations
- **Missing masks** for many images  
- **Class imbalance** may appear in normal vs abnormal labels  
- **General lung region masks only** — not lesion-specific  
- Moderate dataset size → risk of overfitting in deep models  

---

## 🔧 7. Workflow Integration
1. **Train a segmentation model (e.g., U-Net)** using available image-mask pairs  
2. **Extract lung regions** using segmentation outputs  
3. Feed segmented images into a **classification or anomaly detection** model  
4. Track segmentation performance using IoU, Dice, Precision/Recall  
5. Maintain structured train/val/test splits for reproducibility  

---

## 📄 8. Licensing & Attribution
Please refer to the Kaggle dataset page for:
- Usage rights  
- Redistribution constraints  
- Proper citation guidelines  

**Dataset Author:** Nikhil Pandey  
**Link:** https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels/data

---

