# YOLOv8 Object Detection with Albumentations

## 📌 Overview
This project implements an **object detection pipeline** using the **YOLOv8** model from [Ultralytics](https://github.com/ultralytics/ultralytics).  
It integrates **Albumentations** for advanced image augmentations to improve model robustness and accuracy.  
The project is designed for **custom datasets**, making it adaptable to different detection tasks.

---

## 🎯 Features
- **YOLOv8** (nano model by default, can switch to small/medium/large)
- **Custom Dataset Training** with YAML configuration
- **Advanced Image Augmentations** using Albumentations:
  - Horizontal flipping
  - Brightness/contrast adjustment
  - Random rotation
- **mAP@50 Evaluation**
- **GPU Support** for faster training
- Easy-to-modify training parameters

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **YOLOv8 (Ultralytics)**
- **Albumentations**
- **PyTorch**
- **Google Colab / Local GPU**
