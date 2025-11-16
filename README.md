# speech-emotion-classification
speech emotion classification using RAVDESS,TESS, SAVEE, and EMO-DB datasets.


# RAVDESS Speech Emotion Classification

## 🎧 Overview

This repository contains **Balasankar Mohan's individual work** for the RAVDESS dataset as part of the Speech Emotion Classification project. The goal is to classify emotions from speech audio using traditional machine learning models.

This repo focuses **only** on:

* RAVDESS dataset
* Feature extraction using Librosa
* Training & evaluating ML models
* Comparing performance across models

---

## 📂 Dataset: RAVDESS

**RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**

* 24 actors (12 male, 12 female)
* 8 emotions:

  * neutral, calm, happy, sad, angry, fearful, disgust, surprised
* High recording quality and speaker diversity

Dataset source (Kaggle):

```
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
```

---

## 🎛 Features Extracted

Using **Librosa**, the following features are extracted from each audio file:

* **MFCCs** (40 coefficients)
* **Chroma Features**
* **Spectral Centroid**
* **Zero Crossing Rate (ZCR)**
* **Spectral Roll-off**

All features are combined into a single feature vector per audio file.

---

## 🤖 Models Implemented

The following machine learning models are trained and compared:

1. **Logistic Regression / Naive Bayes** (Baseline)
2. **k-Nearest Neighbors (kNN)**

   * tuning: k = 3, 5, 7
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)** with RBF kernel

---

## 📊 Evaluation Metrics

Each model is evaluated using:

* Accuracy
* Precision, Recall, F1-score (macro)
* Confusion matrix
* ROC-AUC (macro)

---

## 📁 Project Structure

```
ravdess-emotion-classification/
│
├── data/               # Raw RAVDESS audio files
├── features/           # Extracted .csv feature files
├── models/             # Trained model files (.pkl)
├── notebooks/          # Jupyter notebooks
└── README.md           # Documentation
```

---

## 🚀 Getting Started

### Install Dependencies

```
pip install librosa numpy pandas scikit-learn matplotlib seaborn
```

### Run Feature Extraction

Use the provided notebook or script in `notebooks/`.

### Train Models

Execute the ML training notebook after feature extraction.

---

## 📌 Status

Currently at: **Feature Extraction & Initial Model Training**

---

## ✨ Author

**Balasankar Mohan**

---

If you'd like, I can also add:

* Visual diagrams
* Example output results
* Code usage instructions
* A final results table
