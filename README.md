# 🍄Deep Learning Project – Mushroom Classification

A deep learning project that classifies mushroom images as **edible** or **poisonous** using a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**. This project demonstrates an end-to-end deep learning workflow including **data cleaning**, **image preprocessing**, **model training**, and **performance evaluation**.

---

## 🎯 Project Task
- **Task**: Binary image classification  
- **Input**: 256 × 256 RGB images  
- **Classes**:  
  - 🍄 Edible  
  - ☠️ Poisonous  

---

## 📊 Dataset
**Dataset Name**: Edible & Poisonous Mushroom Classification (Kaggle)  
**Total Images**: 2,820  

### 📁 Dataset Structure
```text
data/
├── train/
│   ├── edible/
│   └── poisonous/
├── val/
│   ├── edible/
│   └── poisonous/
└── test/
    ├── edible/
    └── poisonous/
```

     
🧠 Model Architecture (CNN)

Three convolutional layers with 16, 32, and 64 filters

Max-pooling layers after each convolution

Dropout layers to reduce overfitting

Fully connected dense layer

Sigmoid output layer for binary classification

Optimizer: Adam

Loss Function: Binary Cross-Entropy

🧼 Data Preprocessing

Removed corrupted and unreadable images

Filtered out files smaller than 10 KB

Resized images to 256 × 256

Normalized pixel values to the range [0, 1]


📈 Model Evaluation

Accuracy

Precision

Recall

Confusion Matrix

Training and validation learning curves

▶️ How to Run the Project
📦 Install Dependencies:
pip install tensorflow numpy matplotlib pillow scikit-learn


🎥 Project Presentation
📑 Google Slides presentation explaining the project:
https://docs.google.com/presentation/d/1dX3_35v2c-E8Vc-jmftVvcZB0odMawnXpC5ye1YPJ88/edit?usp=sharing 
