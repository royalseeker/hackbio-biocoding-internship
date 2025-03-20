# Drug Discovery: Chemical Space Analysis and Docking Score Prediction

![Chemical Space Visualization](https://img.shields.io/badge/Visualization-PCA%20%2B%20KMeans-blue)
![Regression](https://img.shields.io/badge/Prediction-RandomForest%20%2F%20XGBoost-green)

This project analyzes chemical descriptors of 10,000+ small molecules to study their binding affinity to **adenosine deaminase (ADA)**, a protein target associated with diseases. The analysis includes chemical space visualization and docking score prediction using machine learning.

---

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)


---

## Overview

### Objectives
1. **Chemical Space Representation**  
   - Use PCA and K-means clustering to visualize chemical diversity.  
   - Identify clusters with preferential docking scores (binding energy).  

2. **Docking Score Prediction**  
   - Train regression models to predict docking scores from chemical features.  
   - Interpret feature importance for drug optimization.  

### Dataset
- **Source**: [drug_class_struct.txt](https://github.com/HackBio-Internship/2025_project_collection/raw/main/Python/Dataset/drug_class_struct.txt)  
- **Features**: 20+ chemical descriptors (e.g., `MW`, `XLogP`, `HBA`, `HBD`, `TPSA_NO`).  
- **Target**: `score` (docking energy; lower values indicate stronger binding).  

---

## Installation

### Requirements
- Python 3.8+
- Libraries:  
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost
