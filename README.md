# 👤 Facial Age Prediction using Computer Vision and Regression

## 📌 Overview

This project presents a Computer Vision approach for predicting a person's age from facial images using feature extraction with EfficientNet and regression algorithms.

The objective is to compare different regression models and evaluate their performance for age estimation.

---

## 🎯 Objectives

- Facial image preprocessing
- Feature extraction using EfficientNet
- Age prediction using regression algorithms
- Performance evaluation
- Model comparison

---

## 📂 Dataset

This project uses the **MORPH** facial image dataset, a benchmark dataset widely used for age estimation research in Computer Vision.

Due to the dataset's **large size** and **licensing restrictions**, the original facial images are **not included** in this repository.

To reproduce the experiments:

1. Obtain the MORPH dataset from an authorized source.
2. Place the images in the appropriate directory.
3. Update the dataset path in the notebook if necessary.

Only the source code, documentation, and processed files required to understand the methodology are included in this repository.

---

## 🤖 Models Evaluated

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression (SVR)

Feature extraction:

- EfficientNet-B1
- EfficientNet-B2
- EfficientNet-B3

---

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 🛠 Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- OpenCV
- Google Colab

---

## 📁 Repository Structure

```
.
├── age_prediction_regression.ipynb
├── README.md
├── LICENSE
├── requirements.txt
├── data/
└── images/
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries.
3. Download the MORPH dataset (if you have access).
4. Update the dataset path in the notebook.
5. Execute all notebook cells.

---

## 📚 Dataset Reference

The experiments were conducted using the **MORPH** facial image dataset.

For information about dataset availability and licensing, please refer to the official sources:

- MORPH Database
- Ricanek, K., & Tesafaye, T. (2006). *MORPH: A Longitudinal Image Database of Normal Adult Age-Progression*. Proceedings of the 7th International Conference on Automatic Face and Gesture Recognition.

---
## 👨‍🏫 Author

**Valberto Feitosa**

Professor • Data Scientist • Statistics • Machine Learning • Computer Vision
