# Predictive-Modeling-for-ADHD-Detection-using-EEG-Signal-Amplitudes

## 📌 Project Overview
This project presents an end-to-end deep learning pipeline for detecting Attention Deficit Hyperactivity Disorder (ADHD) using EEG (Electroencephalogram) signals. It integrates signal preprocessing, time-series modeling, and advanced neural network architectures to classify ADHD vs Non-ADHD subjects.

The approach explores multiple deep learning models to capture both spatial and temporal characteristics of EEG signals for accurate prediction.

---

## 🎯 Objectives
- Analyze EEG signal patterns associated with ADHD  
- Preprocess and structure raw EEG time-series data  
- Develop and compare multiple deep learning models  
- Evaluate model performance for predictive classification  
- Build a reliable ADHD detection system  

---

## 📂 Dataset Description
- Multi-channel EEG signal recordings  
- Large-scale time-series dataset  
- Labeled data (ADHD vs Non-ADHD)  
- High-frequency neurological signals  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Noise filtering and signal cleaning  
- Normalization and scaling  
- Time-series segmentation  

### 2. Feature Representation
- Channel-wise EEG structuring  
- Transformation into model-compatible input shapes  
- Sequence preparation for deep learning models  

### 3. Model Development
The following deep learning models were implemented and evaluated:

- **EEGNet**  
  Lightweight architecture specifically designed for EEG signal classification  

- **Convolutional Neural Network (CNN)**  
  Extracts spatial features from EEG signals  

- **Bidirectional LSTM (BiLSTM)**  
  Captures temporal dependencies in both directions  

- **Temporal Convolutional Network (TCN)**  
  Efficient for long-range sequence modeling  

- **ResNet (1D CNN variant)**  
  Enables deep feature learning with residual connections  

- **Inception1D**  
  Advanced architecture using multi-scale convolution filters for capturing complex signal patterns  

---

## 📊 Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 📈 Results
- Successfully classified ADHD vs Non-ADHD subjects using EEG data  
- Progressive improvement observed across model architectures  
- Advanced models like Inception1D captured complex signal patterns more effectively  



---

## 📊 Visualizations
- Raw EEG signal plots  
- Preprocessed signal comparisons  
- Channel-wise EEG visualization  
- Model performance plots (confusion matrix, metrics)  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  

- **Libraries & Frameworks:**
  - NumPy  
  - Pandas  
  - SciPy  
  - Scikit-learn  
  - TensorFlow / Keras or PyTorch  
  - Matplotlib  
  - Seaborn  
  - MNE (EEG processing)  

---

## ▶️ How to Run

### 1. Install Dependencies
```bash
pip install numpy pandas scipy scikit-learn matplotlib seaborn mne tensorflow
