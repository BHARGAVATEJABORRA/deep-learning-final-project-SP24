# 🧠 Deep Learning Final Project – Spring 2024

This repository showcases a comprehensive deep learning project that covers multiple computer vision tasks including classification, object detection, and semantic segmentation. Models were trained and evaluated using CIFAR-10, Tiny ImageNet, ADE20K, and custom datasets.

---

## 📁 Project Structure

| Folder       | Contents |
|--------------|----------|
| `code/`      | Jupyter Notebooks for each experiment |
| `datasets/`  | Dataset files like `.xlsx` |
| `images/`    | Input and result images |
| `models/`    | Trained models (`.h5` files) |
| `docs/`      | Final project report |

---

## 🧪 Experiments & Models

### ✅ Classification
- **Custom CNN** on CIFAR-10
- Final Test Accuracy: **75.6%**
- VGG19: **61.9%**
- ResNet50: **36.8%**

### ✅ Fine-tuning
- **Custom CNN** on Tiny ImageNet
- Final Accuracy: **0.6%** (200-class challenge)

### ✅ Object Detection
- **YOLOv8** on a self-driving car dataset
- Detects cars, trucks, pedestrians, etc. using bounding boxes

### ✅ Semantic Segmentation
- **SegFormer** (Transformer-based model)
- Dataset: ADE20K (150 classes)
- IoU: ~0.97 on sample set

---

## ▶️ Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BHARGAVATEJABORRA/deep-learning-final-project-SP24)

You can explore the notebooks interactively below:

- 📦 [Object Detection (YOLOv8)](https://colab.research.google.com/github/BHARGAVATEJABORRA/deep-learning-final-project-SP24/blob/main/code/Object_detection_by_using_YOLOv8.ipynb)
- 🧩 [Segmentation (SegFormer)](https://colab.research.google.com/github/BHARGAVATEJABORRA/deep-learning-final-project-SP24/blob/main/code/Fine_tune_SegFormer.ipynb)
- 📊 [Image Classification (CNN, VGG19, ResNet50)](https://colab.research.google.com/github/BHARGAVATEJABORRA/deep-learning-final-project-SP24/blob/main/code/experiment_part_a.ipynb)

> ⚠️ To reproduce results, upload any required `.h5` models and input images to the Colab environment from the `models/` and `images/` folders.

---

## 🛠️ Tech Stack

- Python
- PyTorch
- TensorFlow
- OpenCV
- Transformers
- Jupyter Notebooks / Google Colab

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
