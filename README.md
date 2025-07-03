
# 🧠 Breast Cancer Classification using Support Vector Machine (SVM)

This project is part of the AI & ML Internship - Task 7.

## 🔍 Objective

Use Support Vector Machines (SVM) with both **linear** and **RBF** kernels for binary classification on the **Breast Cancer dataset**.

---

## 📁 Dataset

- Dataset used: `breast-cancer.csv`  
- Target column: `diagnosis` (`M` = Malignant, `B` = Benign)  
- Converted to binary: `1` for malignant, `0` for benign

---

## ⚙️ Steps Performed

1. Loaded and cleaned the dataset
2. Preprocessed features using `StandardScaler`
3. Trained SVM with:
   - Linear kernel
   - RBF kernel
4. Tuned hyperparameters (`C`, `gamma`) using `GridSearchCV`
5. Evaluated using:
   - Confusion Matrix
   - Classification Report
   - Cross-validation

---

## 🔧 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 📊 Results

- Best model: **SVM with RBF kernel**
- Accuracy: ~97% (after tuning)
- Parameters: `C=10`, `gamma=0.01`

---

## 📌 How to Run

1. Upload `breast-cancer.csv` to Colab
2. Run the Jupyter Notebook (`.ipynb`)
3. Cleaned dataset will be auto-downloaded
4. Model training, testing, and evaluation shown in output cells

---

## 🗂 Repository Structure


---

## ✅ Submission

- GitHub Repository Link: _[paste your link here]_
- Submitted on: _[your submission date]_

---
