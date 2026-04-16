# Malware Detection and Classification Using Machine Learning Models

A full machine‑learning pipeline for malware detection and classification. This project explores baseline models, feature engineering, Random Forest development, and external validation using real‑world datasets.

---

## 📁 Project Structure
```
FinalYearProject/
│
├── data/
│   └── top50_features.json
│
├── notebooks/
│   ├── Baseline_Model_LR.ipynb
│   ├── Baseline_Model_LSVM.ipynb
│   ├── Baseline_Model_RF.ipynb
│   ├── External_Validation_EMBER_RF.ipynb
│   ├── RF_Development.ipynb
│   ├── TF1_ByteEntropy.ipynb
│   └── TF1_Processed.ipynb
│
├── figures/
│   ├── PR_CurveOverlay.png
│   └── ROC_CurveOverlay.png
│
└── README.md
```

---

## 🚀 Overview

This project investigates how machine‑learning models can be used to detect and classify malware based on engineered features extracted from binary files.  
The workflow includes:

- **Baseline model development** (Logistic Regression, Linear SVM, Random Forest)  
- **Feature extraction and transformation**  
- **Random Forest tuning and optimisation**  
- **External validation using the EMBER dataset**  
- **Performance visualisation** through ROC and PR curves  
- **Feature importance analysis** using the top‑50 ranked features  

The repository is designed to be readable, reproducible, and easy to evaluate.

---

## 🧠 Notebooks

All notebooks are located in the `notebooks/` directory.

### **Baseline Models**
- `Baseline_Model_LR.ipynb` — Logistic Regression baseline  
- `Baseline_Model_LSVM.ipynb` — Linear SVM baseline  
- `Baseline_Model_RF.ipynb` — Random Forest baseline  

These notebooks establish initial performance benchmarks for malware classification.

### **Feature Engineering**
- `TF1_ByteEntropy.ipynb` — Byte‑entropy feature extraction  
- `TF1_Processed.ipynb` — Processed feature transformations  
- `data/top50_features.json` — Ranked feature importance list used for model refinement  

### **Model Development**
- `RF_Development.ipynb` — Random Forest optimisation, hyperparameter tuning, and performance analysis  

### **External Validation**
- `External_Validation_EMBER_RF.ipynb` — Evaluates model generalisation using the EMBER dataset  

---

## 📊 Figures

Stored in the `figures/` directory:

- `ROC_CurveOverlay.png` — ROC curve comparison across models  
- `PR_CurveOverlay.png` — Precision‑Recall curve comparison  

These visualisations support performance evaluation and reporting.

---

## 🛠️ Getting Started

### **Requirements**
- Python 3.8+
- Jupyter Notebook / JupyterLab  
- Recommended libraries:
  - pandas  
  - numpy  
  - scikit‑learn  
  - matplotlib / seaborn  

### **Run the Notebooks**
```bash
git clone https://github.com/filzatahir/FinalYearProject
cd FinalYearProject
jupyter notebook
```

Open any notebook from the `notebooks/` folder and run all cells.

---

## 🎯 Purpose

This project demonstrates:

- End‑to‑end malware classification workflow design  
- Feature engineering for binary analysis  
- Model benchmarking and optimisation  
- External dataset validation for robustness  
- Clear documentation and reproducible experimentation  

---

## 👤 Author

**Filza Tahir**  
Final Year Project — Malware Detection and Classification Using Machine Learning Models

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.
