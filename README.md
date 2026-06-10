# Deepfake Detection using CNN-GAN-Attention

## Project Overview

This project presents a hybrid deep learning framework for detecting deepfake facial images and videos using advanced AI techniques including:

* Convolutional Neural Networks (CNN)
* Generative Adversarial Networks (GAN)
* Spatial Attention Mechanism

The system is designed to identify manipulated facial content with high accuracy while improving interpretability through attention visualization techniques.

---

## Features

* High-accuracy deepfake detection system
* CNN-based feature extraction
* GAN-based synthetic data augmentation
* Spatial Attention Mechanism for enhanced detection
* Attention map visualization
* Cross-dataset evaluation
* Real-time prediction support
* Easy-to-use training pipeline

---

## Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 92.6% |
| AUC Score | 98.9% |

---

## Project Structure

```bash
Deepfake-Detection-CNN-GAN/
│
├── data/                 # Dataset samples
├── src/                  # Training and model source code
├── results/              # Output graphs and prediction results
├── models/               # Saved trained models
├── report.pdf            # IEEE research paper
├── requirements.txt      # Required dependencies
└── README.md
```

---

## Datasets Used

* FaceForensics++
* Celeb-DF v2

---

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/mohammed-umarfarooq/Deepfake-Detection-CNN-GAN.git
cd Deepfake-Detection-CNN-GAN
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Training

```bash
python src/train.py
```

### 4. Run Prediction

```bash
python src/predict.py
```

---

## Research Objective

The objective of this project is to develop a robust and interpretable deepfake detection system capable of identifying manipulated media using attention-guided CNN architectures combined with GAN-enhanced training methodologies.

---

## Future Improvements

* Transformer-based architecture integration
* Real-time webcam detection
* Video-level temporal analysis
* Streamlit web deployment
* Explainable AI heatmaps

---

## Authors

* Mohammed Umar Farooq
* Mohammed Rayyan Ul Asgar
* Mohith D

---

## Academic Note

This repository was developed as a collaborative academic group project focused on deepfake image detection using deep learning techniques.
