# MIT-BIH ECG Classification

This repository contains the code and trained model for classifying electrocardiogram (ECG) signals using a deep learning approach. The project leverages the [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/) and PyTorch to build a 1D Convolutional Neural Network (CNN) for automated arrhythmia detection.

---

## 📚 Dataset Source

**MIT-BIH Arrhythmia Database:**  
- **Link:** [https://physionet.org/content/mitdb/1.0.0/](https://physionet.org/content/mitdb/1.0.0/)  
- **Description:** This public dataset, hosted by [PhysioNet](https://physionet.org/), contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects. It is widely used as a benchmark for ECG signal classification and arrhythmia detection research.

---

## 📝 Project Description

This project aims to automate the classification of ECG signals to help with the detection of cardiac arrhythmias.  
Using the MIT-BIH dataset, we preprocess the ECG recordings, segment the signals, and train a 1D CNN to distinguish between different heartbeat classes (e.g., Normal vs. Abnormal). The model is evaluated on standard metrics such as accuracy and F1-score. All code is provided in a Jupyter notebook for easy reproducibility.

---

## 📦 Repository Contents

- **test2.ipynb** — Main Jupyter Notebook for data loading, preprocessing, model training, and evaluation.
- **model.pth** — Trained PyTorch model weights (if present).
- **README.md** — This project documentation.

---

