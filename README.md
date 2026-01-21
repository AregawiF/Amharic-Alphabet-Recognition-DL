# Amharic Alphabet Family Recognition Using Deep Learning

## 📌 Project Overview
This project focuses on recognizing **Amharic alphabetical family characters (ሀ to በ)** using deep learning techniques.  
The goal is to build an end-to-end deep learning system starting from **custom data collection** to **model design, training, and evaluation**.

---

## 🎯 Objectives
- Collect a **custom dataset** of Amharic alphabetical family characters (ሀ to በ)
- Preprocess and label the dataset
- Design and train a **deep learning model** for character recognition
- Evaluate model performance using appropriate metrics
- Document the full workflow clearly
- Submit clean, well-organized code via GitHub

---

## 🔠 Alphabet Classes
The project focuses on the following Amharic alphabet family characters:

- ሀ
- ለ
- ሐ
- መ
- ሠ
- ረ
- ሰ
- ሸ
- ቀ
- በ

---

## 📊 Dataset Collection
- The dataset was **collected manually by the project team**
- Characters were written by multiple individuals to ensure diversity
- Images were captured using mobile phone cameras and scanners
- Each image was labeled according to its corresponding Amharic character
- No open-source or publicly available datasets were used

---

## 🧹 Data Preprocessing
- Image resizing and normalization
- Noise removal and grayscale conversion
- Dataset splitting:
  - Training set
  - Validation set
  - Test set

---

## 🧠 Model Architecture
- Convolutional Neural Network (CNN)
- Key components:
  - Convolutional layers
  - ReLU activation
  - Max pooling
  - Fully connected layers
  - Softmax output layer

The model is trained to classify input images into one of the 10 Amharic alphabet family classes.

---

## ⚙️ Tools & Technologies
- Python
- NumPy
- OpenCV
- Matplotlib
- Google Colab / Local Machine

---

## 📈 Evaluation Metrics
- Accuracy
- Loss
- Confusion Matrix
- Training vs Validation curves

## 📁 Project Structure
Amharic-Alphabet-Family-Recognition-Using-Deep-Learning/
│
├── dataset/
│
├── preprocessing/
│   └── preprocess.py
│
├── model/
│   ├── model.py
│   └── train.py
│
├── evaluation/
│   └── evaluate.py
│
├── results/
│   ├── accuracy.png
│   ├── loss.png
│   └── confusion_matrix.png
│
├── notebooks/
│   └── experiment.ipynb
│
├── README.md
└── requirements.txt
