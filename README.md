# 🎗️ Breast Cancer Diagnosis Analysis using Machine Learning

This project analyzes the **Breast Cancer Wisconsin Diagnostic Dataset** using machine learning techniques to classify tumors as **Malignant** or **Benign**.  
The workflow includes data preprocessing, feature engineering, exploratory analysis, and training ML models to support early cancer detection.

---

## 📌 Project Overview

The goal of this project is to build accurate models that can classify breast cancer tumors based on numerical medical measurements extracted from digitized images of breast masses.

The project explores:

- Key medical features affecting diagnosis  
- Differences between malignant and benign tumors  
- Model accuracy and prediction performance  
- Feature impacts on classification  

Two ML models were implemented:

- **Logistic Regression**  
- **Random Forest Classifier**

---

## 📂 Dataset Used

Dataset: **Breast Cancer Wisconsin Diagnostic Dataset**

Contains:

- **569 samples**  
- **30 numeric features** (cell radius, texture, perimeter, smoothness, concavity, etc.)  
- **Diagnosis:**  
  - **M = Malignant**  
  - **B = Benign**

Key features include:

- Radius mean  
- Area mean  
- Texture mean  
- Smoothness  
- Compactness  
- Symmetry  
- Fractal dimension  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Python Script  

---

## 🧹 Data Preprocessing

✔ Loaded dataset  
✔ Checked for missing values  
✔ Encoded target variable into numerical classes  
✔ Normalized/standardized features  
✔ Split dataset into training & testing sets  
✔ Prepared feature matrix for ML models  

---

## 🔍 Analysis Steps

### **1️⃣ Load the Dataset**
Using Pandas, view structure, and examine feature correlation.

### **2️⃣ Clean & Prepare Data**
- Handle missing values  
- Encode malignant/benign labels  
- Normalize feature values  

### **3️⃣ Train ML Models**
- Logistic Regression  
- Random Forest Classifier  

### **4️⃣ Evaluate Model Performance**
- Accuracy score  
- Confusion matrix  
- Classification report  

---

## 🤖 Machine Learning Models

### **✔ Logistic Regression**
A strong baseline model for binary medical classification.

### **✔ Random Forest Classifier**
Achieves higher performance with multiple decision trees.

**Evaluation Metrics:**

- Accuracy  
- Precision  
- Recall  
- F1-Score  

---

## 📊 Key Insights

- Several cell features strongly correlate with cancer diagnosis  
- Random Forest provides better prediction accuracy than Logistic Regression  
- ML can significantly aid early detection & decision support  
- Clear separation between malignant and benign feature distributions  

---

## 🚀 How to Run the Project

### **Install dependencies:**

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
Run the script:
bash
Copy code
python breast_cancer_diagnosis_analysis.py
This will output:

Model accuracy

Classification reports

Predictions

Confusion matrices

📁 Project Structure
Copy code
breast-cancer-diagnosis/
│── breast_cancer_diagnosis_analysis.py
│── breast_cancer_data.csv
│── README.md
📬 Contact
Created by Asem Ahmed
