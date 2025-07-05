# Chest X-ray Pneumonia Classifier

A deep learning model trained to detect pneumonia from chest X-ray images using transfer learning (ResNet18).

## 🩻 Features
- Fine-tuned ResNet18
- Handled class imbalance via augmentation & stratified sampling
- Grad-CAM for model explainability

## 📊 Metrics
- Accuracy: **93.5%**
- ROC-AUC: **0.96**
- F1-score improved by ~19% for minority class

## 📁 Dataset
Chest X-ray images from [Kaggle NIH dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## 🛠️ Tech Stack
- Python, PyTorch, torchvision, matplotlib, sklearn
