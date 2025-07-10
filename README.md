# 🧠 Credit Score Classification using Machine Learning

A real-world ML project that predicts a customer's credit score category — **Poor**, **Standard**, or **Good** — using behavioral and financial data. This end-to-end solution includes data cleaning, feature selection, model tuning, explainability (SHAP), and result packaging.

---

## 🚀 Project Overview

| Stage                     | Details                                                                 |
|--------------------------|-------------------------------------------------------------------------|
| 🔍 Problem               | Predict credit score category based on customer profile                 |
| 📦 Dataset              | Provided `train.csv`, `test.csv`, and sample output                     |
| 🧹 Preprocessing        | Missing value imputation, outlier handling, categorical encoding        |
| 📊 Feature Selection     | Mutual Info + RFE to select top 15 impactful features                   |
| 🤖 Models Used           | Random Forest, XGBoost, LightGBM (best selected via CV)                 |
| 📈 Evaluation            | Accuracy, F1-score, Confusion Matrix, Feature Importances               |
| 🔍 Explainability        | SHAP summary plot for interpretability                                  |
| 📄 Outputs               | PDF report, plots, predictions, and ZIP packaging for deployment        |

---

## 🧪 Model Performance

- **Best Model**: `RandomForestClassifier`
- **Validation Accuracy**: ~78%
- **Cross-Validation Accuracy**: ~75%

📉 Classification Report (on validation set):

| Class     | Precision | Recall | F1-score |
|-----------|-----------|--------|----------|
| Poor      | 0.78      | 0.77   | 0.77     |
| Standard  | 0.79      | 0.80   | 0.80     |
| Good      | 0.71      | 0.69   | 0.70     |

---

## 📁 Project Structure

📦 credit-score-classification/
├── credit_score_final.ipynb # Jupyter notebook (main code)
├── final_predictions.csv # Test predictions
├── report.pdf # PDF summary report
├── shap_summary.png # SHAP plot (feature importance)
├── confusion_matrix.png # Model confusion matrix
├── feature_importance.png # Top 15 feature importances
├── Sample_Output.csv # Provided sample for submission format
└── README.md # This file


---

## 🔍 Key Features

- ✅ Feature Selection (MI + RFE)
- ✅ Ensemble Models (RF, XGB, LGBM)
- ✅ Explainable AI (SHAP)
- ✅ Clean pipeline with reproducible results
- ✅ Visuals + PDF Report + Final Submission ZIP

---

## 🎯 Real-World Application

This model can be used by:

- **Banks/Fintechs** for real-time credit risk profiling
- **NBFCs** to assess customer eligibility for loans/BNPL
- **Marketers** for segmentation and personalized offers

---

## 👨‍💻 Author

**Shivam Soni** — Aspiring Data Scientist | PGP-DSE @ Great Learning  
📧 [LinkedIn Profile] (www.linkedin.com/in/shivam-soni-481430344)

---

## 🧠 Try It Live (Coming Soon...)

A Streamlit web app version of this project will be launched soon for interactive predictions.

---

