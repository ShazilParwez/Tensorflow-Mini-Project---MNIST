# Tensorflow-Mini-Project
# ✨ MNIST Handwritten Digit Classification 

## 📌 Problem Statement
The goal of this project is to **classify handwritten digits (0–9)** using the **MNIST dataset**, which is a benchmark dataset in machine learning and deep learning.  

---

## 📊 Dataset
- **Source:** [MNIST dataset](http://yann.lecun.com/exdb/mnist/) (via TensorFlow/Keras)  
- **Training samples:** 60,000 images  
- **Test samples:** 10,000 images  
- Each image is **28x28 pixels**, grayscale.  
- Target: **Digit labels (0–9)**  

---

## 🔎 Workflow
1. **Data Loading** – Loaded MNIST dataset directly from TensorFlow/Keras.  
2. **Exploratory Analysis** – Visualized sample images and label distribution.  
3. **Preprocessing** –  
   - Normalized pixel values (0–1)  
   - Reshaped images to fit the TensorFlow model input  
   - One-hot encoded labels  
4. **Model Building** –  
   - Built a **simple neural network** using TensorFlow/Keras.  
   - Layers: Input → Dense → Hidden → Output (Softmax).  
5. **Training** – Trained the model with **categorical cross-entropy loss** and **Adam optimizer**.  
6. **Evaluation** – Tested the model on unseen data and measured accuracy.  

---

## 📈 Results
- **Accuracy:** ~97–98% on test data  
- Model successfully recognizes handwritten digits.  

---

## 🛠 Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Matplotlib (for visualization)  

---
