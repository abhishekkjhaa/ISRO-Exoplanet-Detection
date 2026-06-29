<div align="center">

# 🌌 ExoScan
###  An Explainable Hybrid AI Pipeline for Exoplanet Detection from Noisy Astronomical Light Curves

An end-to-end Artificial Intelligence pipeline for detecting exoplanet transit signals from noisy astronomical light curves using Machine Learning, Deep Learning, Explainable AI, and Uncertainty Estimation.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-success)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-AI-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</div>

---

# 📖 Overview

Exoplanets are planets that orbit stars outside our solar system. Detecting them through transit photometry requires identifying extremely small brightness variations hidden within noisy astronomical observations.

**ExoScan** is an AI-powered detection pipeline that combines classical machine learning, deep learning, explainable AI, and uncertainty estimation to improve the reliability of exoplanet detection from astronomical light curves.

This project was developed as a team submission for the **ISRO BAH Hackathon 2026**.

---

# 🎯 Objectives

- Detect exoplanet transit signals from noisy light curves
- Reduce false positives using robust preprocessing
- Train machine learning and deep learning models
- Explain model predictions using SHAP
- Estimate prediction confidence using uncertainty estimation
- Build an end-to-end reproducible AI pipeline

---

#  Features

- 📊 Data preprocessing and cleaning
- 📈 Exploratory Data Analysis (EDA)
- ⚙️ Feature Engineering
- ⚖️ Class imbalance handling using SMOTE
- 🌳 XGBoost Classification
- 🧠 1D Convolutional Neural Network (CNN)
- 📉 Model Calibration
- 🔍 Explainable AI (XAI) using SHAP to interpret model predictions.
- 🎲 Monte Carlo Dropout for Uncertainty Estimation
- 💾 Model Saving and Loading
- 📋 Performance Evaluation

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, XGBoost |
| Deep Learning | PyTorch |
| Explainability | SHAP |
| Astronomy | Lightkurve |
| Notebook | Jupyter Notebook |

---

# 🔬 Machine Learning Pipeline

```
Raw Light Curves
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Class Balancing (SMOTE)
        │
        ▼
Machine Learning
      (XGBoost)
        │
        ▼
Deep Learning
     (1D CNN)
        │
        ▼
Model Calibration
        │
        ▼
Uncertainty Estimation
        │
        ▼
SHAP Explainability
        │
        ▼
Final Prediction
```

---

# 📂 Repository Structure

```
ISRO-Exoplanet-Detection/
│
├── Final_BAH_Hackathon_Model.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── images/
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/abhishekkjhaa/ISRO-Exoplanet-Detection.git
```

Move into the project directory:

```bash
cd ISRO-Exoplanet-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Open the notebook:

```
Final_BAH_Hackathon_Model.ipynb
```

Run all cells sequentially to reproduce the complete pipeline.

---

# 📊 Expected Outputs

- Processed light curve dataset
- Machine Learning predictions
- Deep Learning predictions
- Performance metrics
- SHAP visualizations
- Confidence estimates
- Model evaluation plots

---

# 👥 Team

| Name | Role |
|------|------|
| Abhishek Kumar Jha | Team Leader |
| Atharv Chawadimani | Team Member |
| Afshan Momin | Team Member |
| Karan Rathod | Team Member |

> Update this table with your team's actual names and roles.

---

#  Future Enhancements

- Transformer-based architectures
- Real-time telescope data integration
- Multi-class exoplanet classification
- Cloud deployment
- Interactive dashboard
- Automated hyperparameter optimization

---

#  Acknowledgements

- Indian Space Research Organisation (ISRO)
- BAH Hackathon
- Open-source Python community
- Scikit-Learn
- PyTorch
- XGBoost
- SHAP
