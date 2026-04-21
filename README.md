# 🧠 Shallow CNN vs Deep CNN on Fashion-MNIST

![Python](https://img.shields.io/badge/Python-3.11-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Dataset](https://img.shields.io/badge/Dataset-Fashion--MNIST-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Objective
👉 View full implementation: [Jupyter Notebook](cnn.ipynb)
This project compares the performance of a **Shallow CNN** and a **Deep CNN** on the Fashion-MNIST dataset.

The goal is to analyze:
- Accuracy
- Efficiency
- Generalization
- Model complexity

---

## 📊 Dataset
- 60,000 training images  
- 10,000 test images  
- 10 classes (fashion categories)  
- Image size: 28×28 grayscale  

---

## ⚙️ Models Used

### 🔹 Shallow CNN
- 1 Convolution Layer
- 1 MaxPooling Layer
- Dense Layer

### 🔹 Deep CNN
- 3 Convolution Layers
- 2 MaxPooling Layers
- Dense Layer

---

## 📈 Model Performance

### 🔹 Shallow CNN Accuracy
![Shallow Accuracy](shallow_accuracy.png)

### 🔹 Shallow CNN Loss
![Shallow Loss](shallow_loss.png)

### 🔹 Deep CNN Accuracy
![Deep Accuracy](deep_accuracy.png)

### 🔹 Deep CNN Loss
![Deep Loss](deep_loss.png)

---

## 🔍 Prediction Analysis

### ✅ Correct Predictions (Shallow CNN)
![Shallow Correct](shallow_correct.png)

### ❌ Incorrect Predictions (Shallow CNN)
![Shallow Incorrect](shallow_incorrect.png)

### ✅ Correct Predictions (Deep CNN)
![Deep Correct](deep_correct.png)

### ❌ Incorrect Predictions (Deep CNN)
![Deep Incorrect](deep_incorrect.png)

---

## 📊 Confusion Matrices

### 🔹 Shallow CNN
![Shallow CM](shallow_confusion_matrix.png)

### 🔹 Deep CNN
![Deep CM](deep_confusion_matrix.png)

---

## 📌 Key Insights

- Shallow CNN achieved **higher accuracy**
- Deep CNN was **more efficient (faster & fewer parameters)**
- Both models struggled with **similar-looking classes**
- Increasing depth did **not significantly improve performance**

---

## 🏁 Conclusion

- ✅ Recommended Model: **Shallow CNN**
- ⚡ Most Efficient: **Deep CNN**
- 🎯 Most Accurate: **Shallow CNN**

👉 Simpler models can outperform deeper ones on relatively simple datasets like Fashion-MNIST.
