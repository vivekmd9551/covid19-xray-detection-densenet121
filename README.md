# 🩺 COVID-19 Detection using Chest X-Ray Images

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=for-the-badge&logo=keras)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

</p>

---

# 📖 Project Overview

This project uses **Deep Learning** and **Transfer Learning** to detect **COVID-19** from **Chest X-Ray Images**.

A **DenseNet121** pre-trained model is fine-tuned to classify X-ray images into four medical categories.

The project demonstrates a complete Deep Learning workflow including:

- 📂 Data Loading
- 🧹 Image Preprocessing
- 🔄 Data Augmentation
- 🧠 Transfer Learning
- 📊 Model Training
- 📈 Performance Evaluation
- 📉 Accuracy & Loss Visualization

---

# 🎯 Classification Classes

| Class | Description |
|--------|-------------|
| 🦠 COVID-19 | COVID Positive Chest X-Ray |
| ❤️ Normal | Healthy Chest X-Ray |
| 🫁 Lung Opacity | Lung Opacity Cases |
| 🦠 Viral Pneumonia | Viral Pneumonia Cases |

---

# 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Programming Language |
| 🤖 TensorFlow | Deep Learning |
| 🔥 Keras | Neural Networks |
| 👁 OpenCV | Image Processing |
| 📊 NumPy | Numerical Computing |
| 📝 Pandas | Data Handling |
| 📉 Matplotlib | Visualization |
| 📚 Scikit-Learn | Model Evaluation |

---

# 🏗️ Model Architecture

✅ Transfer Learning

✅ DenseNet121 (Pre-trained on ImageNet)

✅ Global Average Pooling

✅ Dense Layer (ReLU)

✅ Dropout Layer

✅ Softmax Output Layer

---

# 🔄 Data Preprocessing

✔ Image Resizing (224×224)

✔ Pixel Normalization

✔ Data Augmentation

- Rotation
- Horizontal Flip
- Zoom
- Width & Height Shift

---

# ⚙ Training Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Learning Rate | 0.001 |
| Image Size | 224 × 224 |
| Transfer Learning | DenseNet121 |

---

# 📊 Model Performance

| Metric | Score |
|--------|-------|
| 🎯 Test Accuracy | **86.11%** |
| ✅ COVID Precision | **91%** |
| 🔍 COVID Recall | **64%** |

---

# 📈 Project Workflow

```text
Chest X-Ray Images
        │
        ▼
Data Preprocessing
        │
        ▼
Image Augmentation
        │
        ▼
DenseNet121
(Transfer Learning)
        │
        ▼
Model Training
        │
        ▼
Prediction
        │
        ▼
Performance Evaluation
```

---

# 📂 Repository Structure

```
📦 covid19-xray-detection-densenet121
│
├── 📄 COVID_19_Detection_using_X_Ray_Images.ipynb
├── 📄 README.md
└── 📄 requirements.txt (Optional)
```

---

# 🚀 Future Improvements

- Improve COVID Recall
- Hyperparameter Tuning
- Fine-Tuning DenseNet121
- Model Deployment using Flask/Streamlit
- Ensemble Learning

---

# 📚 Dataset

**COVID-19 Radiography Database**

Classes:

- COVID
- Normal
- Lung Opacity
- Viral Pneumonia

---

# 🎓 Internship Project

This project was completed as part of my **Data Science Internship** to demonstrate practical skills in:

- Machine Learning
- Deep Learning
- Computer Vision
- Medical Image Classification
- Transfer Learning

---

# 👨‍💻 Author

**Vivek M D**

🎓 Data Science Enthusiast

💡 Passionate about AI, Machine Learning & Deep Learning

⭐ If you found this project helpful, consider giving it a **Star**!
