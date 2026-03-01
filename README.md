# 🧠 Brain Tumor Detection Model (Notebook)

This notebook contains the complete implementation of a **Deep Learning model** for detecting brain tumors from MRI images using Convolutional Neural Networks (CNN).

---

## 🚀 Overview

The model is trained on MRI brain images to classify tumors into multiple categories.
It uses TensorFlow/Keras for building and training the model.

---

## 🧠 Classes

The model predicts the following classes:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

---

## 📊 Model Details

* Framework: TensorFlow / Keras
* Architecture: CNN / Transfer Learning
* Input Size: 224 × 224
* Activation: ReLU, Softmax
* Loss Function: Sparse Categorical Crossentropy
* Optimizer: Adam

---

## 📂 Dataset

Dataset used: Brain MRI images

You can download dataset from Kaggle:
👉 https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

---

## ⚙️ How to Run

### 1️⃣ Open in Google Colab

Upload the notebook or open directly in Colab.

---

### 2️⃣ Install dependencies

```id="1zj4th"
pip install tensorflow matplotlib numpy
```

---

### 3️⃣ Load dataset

Update dataset path in the notebook:

```id="1f4b4u"
/content/drive/MyDrive/BrainTumour
```

---

### 4️⃣ Train model

Run all cells to train the model.

---

### 5️⃣ Save model

```id="n3og66"
model.save("brain_model")
```

---

## 📈 Output

The notebook shows:

* Training accuracy and loss
* Validation accuracy and loss
* Graphs for performance

---

## 📸 Sample Results

The model predicts tumor type along with confidence score.

---

## ⚠️ Disclaimer

This model is for educational purposes only and should not be used for medical diagnosis.

---

## 👨‍💻 Author

Md Akmal Faraz
_B.Tech CSE_
