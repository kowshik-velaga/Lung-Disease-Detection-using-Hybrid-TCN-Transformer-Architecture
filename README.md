
# 🧠 Lung Disease Detection using Hybrid TCN + Transformer Architecture

This repository contains two deep learning projects designed to detect lung diseases from **X-ray** and **CT-scan** images using a **novel hybrid model** that combines **CNNs**, **Temporal Convolutional Networks (TCNs)**, and **Linformer-based Transformers**.

---

## 🚀 Projects Included

### 1. 🫁 [Lung X-ray Disease Detection](https://www.kaggle.com/code/saikrishnakowshik/lung-xray-disease-detection)
- Detects diseases like pneumonia and fibrosis from chest X-ray images
- Achieves high accuracy on noisy and varied scan quality

### 2. 🫁 [Lung CT-Scan Disease Detection](https://www.kaggle.com/code/saikrishnakowshik/lung-ctscan)
- Identifies diseases from CT scans, capturing fine-grained internal features
- Suitable for COVID-19 and complex thoracic conditions

---

## 🎯 Core Objective
To develop a **single, reusable deep learning pipeline** that can handle both **X-ray** and **CT-scan inputs** using the same architecture, thereby offering a generalizable solution to lung disease diagnosis.

---

## 💡 What's Novel?
- ✅ Combination of **TCNs** and **Linformer Attention** over CNN features  
- ✅ Applicable to **both image modalities** without major redesign  
- ✅ Lightweight yet effective for time-series-like image dependencies  
- ✅ Easy to extend for real-time clinical diagnostics

---

## 🧰 Tech Stack
- Python
- TensorFlow / Keras
- OpenCV, NumPy, Matplotlib
- TA-Lib (for optional time-based indicators)
- Linformer (efficient Transformer)

---

## 🛠 Model Pipeline

```
Input Image (X-ray / CT)
        ↓
   CNN Layers (Feature Extraction)
        ↓
TCN Layers (Temporal Pattern Learning)
        ↓
Linformer Attention (Global Dependency Modeling)
        ↓
   Dense Layers + Softmax
        ↓
   Disease Class Prediction
```

---

## 📈 Results Summary

| Project              | Accuracy | Highlights |
|----------------------|----------|------------|
| X-ray Detection      | ~95%     | Handles various scan qualities, strong generalization |
| CT-scan Detection    | ~94%     | Captures internal texture-based lung pathologies |

---

## 📊 Visualizations
- Loss/accuracy curves
- Confusion matrix
- Actual vs predicted examples

(*Available inside each notebook*)

---

## 📁 File Structure

```
📦 Lung-Disease-Detection
├── lung-xray-disease-detection.ipynb   # Notebook for X-ray classification
├── lung-ctscan.ipynb                   # Notebook for CT scan classification
└── README.md                           # This file
```

---

## 👨‍💻 Author

**Krishna Kowshik**  
📫 [LinkedIn](https://www.linkedin.com/in/sai-krishna-kowshik-velaga-2942a4252/)  
📧 krishnakowshik312@gmail.com

---

## 📜 License

This project is open for academic and non-commercial use. Contact for research or collaboration proposals.

---

## 🙌 Acknowledgements

- Datasets from Kaggle
- Linformer: Efficient Attention Mechanism
- TensorFlow & Keras community
```
