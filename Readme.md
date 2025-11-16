# Speech Emotion Classification

## 📌 Overview

This project performs **comparative analysis of traditional machine learning models** for **Speech Emotion Recognition (SER)** across four well-known public emotional speech datasets:

* **RAVDESS** (Balasankar Mohan)
* **TESS** (Chinmay Ajith)
* **SAVEE** (Gouri K)
* **EMO-DB** (Nandita Rajesh)

The project aims to evaluate the generalization and interpretability of ML models using standardized audio features extracted via **Librosa**.

---

## 🎯 Project Goals

* Classify emotions such as *happiness, sadness, anger, and neutrality* from speech audio.
* Compare the performance of **kNN, Random Forest, SVM, and Logistic Regression/Naive Bayes**.
* Evaluate models across different datasets for robustness.
* Produce a unified comparative report.

---

## 📂 Dataset Overview

| Dataset     | Members Responsible | Key Characteristics                     |
| ----------- | ------------------- | --------------------------------------- |
| **RAVDESS** | Balasankar Mohan    | 24 actors, 8 emotions, high variability |
| **TESS**    | Chinmay Ajith       | 2 female speakers, 7 emotions           |
| **SAVEE**   | Gouri K             | 4 male British speakers                 |
| **EMO-DB**  | Nandita Rajesh      | 10 German actors, 7 emotions            |

Each team member preprocesses, trains models on, and evaluates **their assigned dataset**.

---

## 🧪 Feature Engineering

The following audio features are extracted using **Librosa**:

* **MFCCs** (Mel Frequency Cepstral Coefficients)
* **Chroma Features**
* **Spectral Centroid**
* **Zero Crossing Rate (ZCR)**
* **Spectral Roll-off**

Preprocessing includes:

* Feature normalization
* Label encoding
* Train-test splitting
* Dataset balancing (if needed)

---

## 🤖 Models Implemented

Each dataset is trained and evaluated on the following models:

1. **k-Nearest Neighbors (kNN)**
2. **Decision Tree / Random Forest**
3. **Support Vector Machine (SVM)** (RBF Kernel)
4. **Logistic Regression or Naive Bayes** (baseline)

---

## 📊 Evaluation Metrics

Models will be compared based on:

* **Accuracy**
* **Precision, Recall, F1-score** (macro-average)
* **Confusion Matrix**
* **ROC-AUC** (macro)
* **Training Time**
* **Inference Latency**
* **Feature Importance** (for tree-based methods)

---

## 📁 Project Structure

```
speech-emotion-classification/
│
├── data/                 # Raw datasets (not uploaded to GitHub)
├── ravdess/              # RAVDESS dataset files
```


---

---

## 📌 Status

Project currently in: **Feature Extraction & Model Training Phase**

---


Just tell me what you want added!
