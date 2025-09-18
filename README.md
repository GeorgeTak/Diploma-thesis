# Diploma-thesis

This repository is for academic and research purposes only.
Author: Georgios Takoutis

---

## 🔧 Preprocessing Techniques

Both notebooks include:
- **SMOTE** – Synthetic Minority Oversampling Technique for handling class imbalance  
- **Min–Max Scaler** – Normalization of numerical features  
- **Train/Validation/Test Split** – First step in evaluation strategy  

**NACC notebook (extra methods):**
- **RFE (Recursive Feature Elimination)** – feature selection  
- **PCA (Principal Component Analysis)** – dimensionality reduction  
- **Evaluation strategies:**
  - Simple **percentage split** (train/validation/test)  
  - **Hybrid approach**: percentage split + cross-validation for model robustness  

---

## 🤖 Machine Learning Models

Both datasets are modeled with six ML algorithms:
1. **Support Vector Machines (SVM)**  
2. **Random Forest (RF)**  
3. **Logistic Regression (LR)**  
4. **XGBoost**  
5. **LightGBM**  
6. **Artificial Neural Networks (ANN)**  

---

## 📊 Evaluation

The notebooks generate:
- **Performance metrics** (Accuracy, Precision, Recall, F1-Score)  
- **ROC curves** for **validation and test sets**  
- **Confusion matrices**  
- **LIME explanations** on validation data (for model interpretability)



## 🚀 How to Use in Google Colab (Simple Guide)

1. **Open the notebook**  
   - Click the Colab link for ADNI or NACC (see above).  

2. **Upload the dataset**  
   - On the left side of Colab, click the **folder icon**.  
   - Click the **upload icon** and choose your dataset file from your computer.  

3. **Install extra libraries**  
   - Run the cell in the notebook that says:  
     ```python
     !pip install imbalanced-learn xgboost lightgbm lime
     ```
   - Just press the **play button** next to the cell.  

4. **Run everything**  
   - From the top menu, choose **Runtime → Run all**.  
   - The notebook will do all the steps: preprocessing, training models, showing results, and generating plots.  

5. **See the results**  
   - Scroll down to view performance tables, ROC curves, and LIME explanations.  

---

