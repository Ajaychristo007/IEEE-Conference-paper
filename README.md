# AI-Based Waste Segregation using CNN & DNN

## 📌 Overview
This project focuses on AI-driven waste segregation using Convolutional Neural Networks (CNN) and Deep Neural Networks (DNN) to automate waste classification and improve recycling efficiency. The system classifies waste materials such as plastic, glass, metal, paper, cardboard, and trash using deep learning models and image processing techniques. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objective
The main objective of this project is to develop an intelligent waste classification system that:
- Reduces manual waste sorting efforts
- Improves recycling accuracy
- Supports sustainable waste management
- Enables smart city and IoT-based waste solutions

---

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- PyTorch
- CNN (Convolutional Neural Networks)
- DNN (Deep Neural Networks)
- OpenCV
- Deep Learning
- Computer Vision

---

## 📂 Datasets Used
- TrashNet Dataset
- TrashBox Dataset
- Kaggle Garbage Dataset

The datasets include labeled waste images across categories such as:
- Plastic
- Glass
- Metal
- Paper
- Cardboard
- Trash
- E-Waste
- Medical Waste :contentReference[oaicite:1]{index=1}

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Image resizing (224×224)
- Normalization
- Data augmentation
  - Rotation
  - Flipping
  - Cropping
  - Color jitter

### 2. Model Architectures
The project evaluates multiple deep learning models:
- VGG16
- ResNet50 / ResNet101
- DenseNet121
- Inception-v3
- EfficientNet
- MobileNetV2
- ResNeXt-101

### 3. Training
- Transfer Learning
- Adam Optimizer
- Cross-Entropy Loss
- GPU-based training
- Early stopping and dropout regularization

### 4. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Results
The CNN models significantly outperformed traditional DNN approaches.

| Model | Accuracy |
|-------|-----------|
| DenseNet121 | ~95% |
| ResNeXt-101 | ~90% |
| ResNet50 | ~87% |
| MobileNetV2 | ~80% |
| DNN Baseline | ~65% |

DenseNet121 achieved the highest performance with strong precision, recall, and F1-score values. :contentReference[oaicite:2]{index=2}

---

## 🚀 Features
- Automated waste classification
- High accuracy image recognition
- Smart recycling support
- IoT-compatible lightweight models
- Real-time waste monitoring capability
- Scalable smart city integration

---

## 🌍 Real-World Applications
- Smart waste bins
- Recycling plant automation
- Municipal waste management
- IoT-enabled smart cities
- Industrial waste segregation systems

---

## ⚠️ Challenges
- Small and imbalanced datasets
- Real-time deployment constraints
- High computational cost for deep models
- Misclassification between visually similar waste categories

---

## 🔮 Future Enhancements
- Federated Learning
- Explainable AI (XAI)
- Lightweight edge deployment models
- Sensor-integrated waste detection
- Advanced IoT integration
- Smart autonomous waste management systems

---

## 📚 Research Paper
This project is based on the research paper:

**"AI-Based Waste Segregation: A CNN and DNN Approach"** by  
Ajay Christo P, Shahanas M, Dharanidharan S, Koteeswarar MM, and Chandragandhi S. :contentReference[oaicite:3]{index=3}

---

## 👨‍💻 Authors
- Ajay Christo P
- Shahanas M
- Dharanidharan S
- Koteeswarar MM
- Chandragandhi S
