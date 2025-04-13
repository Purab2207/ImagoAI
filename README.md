# ML Intern Task – Vomitoxin Prediction from Hyperspectral Data

## 📌 Project Overview

This project implements a machine learning pipeline to predict **vomitoxin_ppb** levels from hyperspectral reflectance data. The notebook includes:
- Preprocessing
- Dimensionality Reduction (PCA)
- 1D Convolutional Neural Network for Regression

---

## ⚙️ Installation Instructions

1. **Clone this repository:**
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Install the dependencies:**
```
pip install -r requirements.txt
```

Required libraries include:
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `tensorflow` (>=2.x)

---

## 🚀 Running the Notebook

1. Ensure the dataset file `TASK-ML-INTERN.csv` is in the same folder.
2. Launch Jupyter Notebook:
```
jupyter notebook MLINTERN_TASK.ipynb
```
3. Run all cells in order to perform preprocessing, PCA, visualization, and model training.

---

## 📁 Repository Structure

```
MLINTERN_TASK/
│
├── MLINTERN_TASK.ipynb         # Main notebook
├── TASK-ML-INTERN.csv          # Input dataset (place it in the root directory)
├── README.md                   # This file
└── requirements.txt            # Dependency list
```

---

## 📈 Output

- PCA scatter plots of spectral features
- Heatmaps and average reflectance visualizations
- Trained CNN model for vomitoxin prediction

---

## 🧠 Author Notes

- Data filtered for outliers (`vomitoxin_ppb` > 8000 removed)
- PCA provided insights into variance explained
- 1D CNN trained on full spectral features (normalized)

---
