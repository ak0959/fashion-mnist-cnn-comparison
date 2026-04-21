# 🧠 Shallow CNN vs Deep CNN on Fashion-MNIST

![Python](https://img.shields.io/badge/Python-3.11-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Dataset](https://img.shields.io/badge/Dataset-Fashion--MNIST-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 🚀 Project Overview

This project performs a comparative analysis between a **Shallow Convolutional Neural Network (CNN)** and a **Deep CNN** on the Fashion-MNIST dataset.

It explores how increasing model complexity impacts:
- Learning capability
- Generalization
- Computational efficiency

📌 **Key Result:** A simpler shallow CNN slightly outperforms a deeper model on this dataset.

---

## 📊 Dataset

- 60,000 training images  
- 10,000 test images  
- 10 classes (fashion categories)  
- Image size: 28×28 grayscale  

Fashion-MNIST is a benchmark dataset used for evaluating image classification models.

---

## ⚙️ Models Used

### 🔹 Shallow CNN
- 1 Convolution Layer (32 filters)
- 1 MaxPooling Layer
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (Softmax)

### 🔹 Deep CNN
- 3 Convolution Layers (32 → 64 → 128 filters)
- 2 MaxPooling Layers
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (Softmax)

---

## 🧾 Results Summary

| Model        | Test Accuracy | Training Time | Parameters |
|-------------|--------------|--------------|------------|
| Shallow CNN | **91.85%**   | ~217 sec     | 693K       |
| Deep CNN    | 91.12%       | ~120 sec     | 241K       |

👉 **Insight:** Increasing depth did not improve performance significantly.

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
- Increasing model depth did **not significantly improve performance**

---

## 📚 What This Project Shows

- CNN depth does not always improve accuracy  
- Simpler architectures can generalize better  
- Model efficiency and performance must be balanced  
- Dataset complexity should guide model design  

---

## 🏁 Conclusion

- ✅ Recommended Model: **Shallow CNN**
- ⚡ Most Efficient Model: **Deep CNN**
- 🎯 Most Accurate Model: **Shallow CNN**

👉 A well-designed shallow CNN is sufficient for datasets like Fashion-MNIST, showing that complexity should be applied thoughtfully.

---

## 📎 Project Files

- `cnn.ipynb` → Full implementation  
- Plots and images → Performance & analysis visuals  

---

## 📬 Final Note

This project demonstrates practical deep learning concepts including:
- CNN architecture design
- Model comparison
- Overfitting analysis
- Error interpretation

It highlights that **better models are not always deeper models**.
