# 🍱 ResNet18-ImageDetect-Food101-Fold

This project trains a **ResNet18** deep learning model for **food image classification** using the **Food-101** dataset.  
It employs **K-Fold Cross Validation** for robust model evaluation and includes a **One-vs-Rest ROC Curve** visualization to analyze class-wise performance.

---

## 📘 Overview

- **Model:** ResNet18 (pretrained on ImageNet)  
- **Dataset:** Food-101 (101 food categories)  
- **Framework:** PyTorch  
- **Validation:** 3-Fold Cross Validation  
- **Evaluation:** Accuracy, Precision, Recall, F1-score, and ROC-AUC  

---

## ⚙️ Key Features

✅ Uses **ResNet18** with transfer learning  
✅ **Data augmentation** (flip, rotation, color jitter, normalization)  
✅ **K-Fold Cross Validation** for better generalization  
✅ **Label smoothing** to reduce overconfidence  
✅ **AdamW optimizer** with **cosine learning rate schedule + warmup**  
✅ **ROC (One-vs-Rest)** visualization for multiple classes  
✅ Automatic GPU/CPU device handling  

---

## 🧩 Requirements

Install dependencies:
```bash
pip install torch torchvision scikit-learn matplotlib numpy
