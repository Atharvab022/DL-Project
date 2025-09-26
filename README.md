# 🐕 End-to-End Multi-Class Dog Breed Classification

This project implements an **image classification model** to identify the **breed of a dog** given an input image.  
It uses **TensorFlow** and **TensorFlow Hub** for deep learning, trained on the **Kaggle Dog Breed dataset**.

---

## 📌 Problem Statement
Classify dog breeds from images using a multi-class image classifier.

---

## 📂 Dataset
- Source: [Kaggle Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification)
- Data type: **Unstructured image data**
- Preprocessing: Images are converted into **Tensors**, resized, and normalized before training.

---

## 🧠 Approach
1. **Data Preparation** – Load dataset, create training/validation splits, preprocess images.  
2. **Model Building** – Use **TensorFlow Hub feature extractors** with a **Keras Sequential model**.  
3. **Callbacks** – 
   - `TensorBoard` for training visualization  
   - `EarlyStopping` to prevent overfitting  
4. **Training** – Model trained first on a subset, then full dataset.  
5. **Evaluation** – Validation accuracy checked, overfitting analyzed.  

---

## 🛠 Requirements
- Python 3.x
- TensorFlow
- TensorFlow Hub
- Matplotlib, NumPy, Pandas
- Jupyter Notebook / Google Colab

Install all dependencies:
```bash
pip install -r requirements.txt

