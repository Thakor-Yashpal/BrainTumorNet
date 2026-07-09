# 🧠 BrainVision: Comparing CNN Architectures for Brain Tumor MRI Classification

BrainVision is a PyTorch-based deep learning project that compares multiple convolutional neural network architectures for classifying brain tumors from MRI images.

---

## 📌 Overview

This project benchmarks several CNN architectures on a four-class brain MRI dataset.

Classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

The objective is to compare model performance and identify the most effective architecture for brain tumor classification.

---

## 🚀 Models

- CNN (From Scratch)
- ResNet18
- ResNet50
- EfficientNet-B0
- DenseNet121
- MobileNetV3

---

## 📂 Dataset

This project uses the **Brain Tumor MRI Dataset** created by **Masoud Nickparvar**, available on Kaggle.

**Dataset Link**

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset :contentReference[oaicite:0]{index=0}

### Dataset Structure

```
Dataset/
│
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
│
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/
```

### Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

The dataset contains brain MRI images organized into four categories for multi-class image classification. It is designed for developing and evaluating deep learning models for automatic brain tumor classification. :contentReference[oaicite:1]{index=1}

---

## 🛠 Technologies

- Python
- PyTorch
- TorchVision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Docker
- Jupyter Notebook

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📦 Installation

```bash
git clone https://github.com/Thakor-Yashpal/BrainTumorNet

cd BrainVision-CNN-Architecture-Comparison
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
jupyter notebook
```

Open

```
BrainVision.ipynb
```

---

## 🐳 Docker

Build

```bash
docker build -t brainvision .
```

Run

```bash
docker run -it -p 8888:8888 brainvision
```

---

## 🧠 Models

This project benchmarks multiple Convolutional Neural Network (CNN) architectures for multi-class brain tumor MRI classification.

| Model | Type | Status |
|--------|------|--------|
| CNN | Custom CNN (Built from Scratch) | ✅ |
| ResNet18 | Transfer Learning | ✅ |
| ResNet50 | Transfer Learning | 🚧 |
| EfficientNet-B0 | Transfer Learning | 🚧 |
| DenseNet121 | Transfer Learning | 🚧 |
| MobileNetV3 | Transfer Learning | 🚧 |

**Legend**

- ✅ Completed
- 🚧 Planned / In Progress

---

## 📌 Future Improvements

- Vision Transformer (ViT)
- ConvNeXt
- Swin Transformer
- Grad-CAM
- TensorBoard
- Streamlit Deployment

---

## 👨‍💻 Author

Yashpalsinh Thakor

GitHub

https://github.com/thakor-yashpal

Portfolio

https://thakor-yashpal.github.io/

---

⭐ If you like this project, consider giving it a star.