# Breast Cancer Detection using Machine Learning

This project builds a machine learning model to classify tumors as **benign or malignant** using structured medical data.

---

## Problem Statement

Breast cancer is one of the most common cancers worldwide. Early detection significantly improves survival rates.

The goal of this project is to develop a model that can accurately classify tumors into:

* **Benign (Non-cancerous)**
* **Malignant (Cancerous)**

---

## Dataset
Test 1
* Source: `sklearn.datasets.load_breast_cancer`
* Contains features computed from digitized images of breast masses

### Features include:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry

Target:

* `0 → Benign`
* `1 → Malignant`

---

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## Workflow

### 1. Data Loading

* Dataset loaded using `sklearn`
* Converted into Pandas DataFrame

### 2. Data Preprocessing

* Features and target separated
* Train-test split performed
* Feature scaling using `StandardScaler`

### 3. Model Training

Trained multiple machine learning models:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### 4. Model Evaluation

* Accuracy comparison across models
* Confusion Matrix
* Classification Report

---

## Results

* All models performed well on the dataset
* Ensemble methods like **Random Forest** generally achieved the best performance
* The model successfully distinguishes between benign and malignant tumors with high accuracy

---

## How to Run

```bash
git clone https://github.com/code-with-bharat/breast-cancer-detection.git
cd breast-cancer-detection
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```
breast_cancer_detection.ipynb
```

---

## Project Structure

```
📁 breast-cancer-detection
 ┣ 📜 breast_cancer_detection.ipynb
 ┣ 📜 README.md
```

---

## Conclusion

This project demonstrates how machine learning can assist in early cancer detection.

Key insights:

* Proper preprocessing improves model performance
* Ensemble models provide strong results
* ML can support real-world healthcare applications

---

## Future Improvements

* Add ROC Curve and AUC score
* Deploy model using Streamlit
* Use deep learning models
* Integrate real-time prediction system

---

## 📬 Contact

* 📧 Email: [choudharybharat0102@gmail.com](mailto:choudharybharat0102@gmail.com)
* 🔗 GitHub: https://github.com/code-with-bharat

---

If you found this project useful, consider giving it a star!
