# Prediction of Chronic Kidney Disease Using Machine Learning Algorithms

This repository contains code and resources for predicting chronic kidney disease (CKD) using machine learning algorithms. CKD is a significant health concern affecting millions worldwide, and early detection plays a crucial role in effective management and treatment.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Machine Learning Models Developed](#machine-learning-models-developed)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Chronic kidney disease is characterized by the gradual loss of kidney function over time. Early detection and management of CKD are essential to prevent complications such as kidney failure and cardiovascular diseases. This project explores the effectiveness of various machine learning algorithms in predicting CKD based on clinical and demographic features.

## Dataset

The dataset used in this project is sourced from the [Chronic Kidney Disease dataset](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease) available on the UCI Machine Learning Repository. It contains  patient data with clinical and demographic features.The features include both numerical and categorical variables, such as age, blood pressure, specific gravity, albumin, sugar, blood glucose random, blood urea, serum creatinine, sodium, potassium, hemoglobin, red blood cells, pus cell, pus cell clumps, bacteria, packed cell volume, white blood cell count, red blood cell count, hypertension, diabetes mellitus, coronary artery disease, appetite, pedal edema, and anemia.

## Features

- **Numerical Features**:
  - Age
  - Blood pressure (bp)
  - Specific gravity (sg)
  - Albumin (al)
  - Sugar (su)
  - Blood glucose random (bgr)
  - Blood urea (bu)
  - Serum creatinine (sc)
  - Sodium (sod)
  - Potassium (pot)
  - Hemoglobin (hemo)

- **Categorical Features**:
  - Red blood cells (rbc)
  - Pus cell (pc)
  - Pus cell clumps (pcc)
  - Bacteria (ba)
  - Packed cell volume (pcv)
  - White blood cell count (wc)
  - Red blood cell count (rc)
  - Hypertension (htn)
  - Diabetes mellitus (dm)
  - Coronary artery disease (cad)
  - Appetite (appet)
  - Pedal edema (pe)
  - Anemia (ane)

## Machine Learning Models Developed

The following machine learning models were developed for predicting CKD:
1. **Logistic Regression**: A linear classification algorithm that predicts the probability of CKD based on the input features.
2. **Decision Trees**: A non-linear classification algorithm that builds a tree-like structure to make decisions based on the input features.
3. **K-Nearest Neighbors (KNN)**: A non-parametric classification algorithm that assigns a class label based on the majority class among its k nearest neighbors in the feature space.

## Usage

To use this codebase:
1. Clone the repository: `git clone https://github.com/rajamuppidi/ChronicKidneyDisease-Prediction.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks or Python scripts for training and evaluation.

## Contributing

Contributions are welcome! If you have ideas for improvements, new features, or find any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per the terms of the license.

---
