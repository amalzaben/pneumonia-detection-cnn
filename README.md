# 🫁 Pneumonia Detection using CNN

## 📌 Overview

Deep learning project using Convolutional Neural Networks (CNNs) to classify chest X-ray images as **Normal** or **Pneumonia**.

Includes a comparison between a **baseline CNN** and an **improved deep CNN architecture**.

---

## 📊 Dataset

* Chest X-ray image dataset
* Binary classification: Normal vs Pneumonia
* Images resized to 224×224 and normalized

---

## 🤖 Models

* Baseline CNN (simple architecture)
* Improved CNN (deeper model with:

  * multiple convolutional layers
  * batch normalization
  * dropout
  * global average pooling)

---

## 📈 Key Results

* Baseline Accuracy: ~92.8%
* Improved Model Accuracy: ~94.0%
* Improved model significantly increased **recall (98%)**
* False negatives reduced from **27 → 8**

---

## 🧠 Key Takeaways

* Deeper CNN improves feature extraction and generalization
* Reducing false negatives is critical in medical applications
* Model complexity + regularization improves performance

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📁 Files

* `machine_learning_project2.ipynb` → Code
* `report.pdf` → Full analysis

