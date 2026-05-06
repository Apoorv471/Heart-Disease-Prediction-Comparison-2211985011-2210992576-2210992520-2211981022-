# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Overview
This project focuses on **early prediction of heart disease** using Machine Learning techniques. It includes a comparative analysis of multiple classification models along with feature selection and dimensionality reduction methods to improve prediction performance.

The study evaluates how different techniques impact accuracy, recall, and overall model effectiveness, with a strong focus on **minimizing false negatives**, which is critical in healthcare applications.

---

## 🎯 Objectives
- Predict heart disease using patient medical data
- Compare multiple ML models
- Evaluate feature selection techniques:
  - Chi-Square
  - Recursive Feature Elimination (RFE)
- Analyze dimensionality reduction using PCA
- Identify the best-performing model for real-world use

---

## 🧠 Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## ⚙️ Techniques Implemented

### 🔹 Feature Selection
- **Chi-Square Test**
- **Recursive Feature Elimination (RFE)**

### 🔹 Dimensionality Reduction
- **Principal Component Analysis (PCA)**

---

## 📊 Evaluation Metrics
Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

> ⚠️ Special focus was given to **Recall**, as missing a heart disease case (false negative) is critical in medical diagnosis.

---

## 📈 Results Summary

| Experiment | Best Model | Accuracy | Key Insight |
|----------|----------|--------|------------|
| Baseline | Random Forest | ~85–90% | Good performance |
| Chi-Square | Random Forest | Improved | Removed irrelevant features |
| RFE | **Random Forest** | **88.5%** | 🔥 Best overall |
| PCA | SVM | ~83.6% | Reduced dimensionality |

---

## 🏆 Final Conclusion

- **RFE + Random Forest** achieved the best performance
- Achieved **100% Recall**, ensuring no diseased patients were missed
- Feature selection proved more effective than PCA for this dataset

> 📌 Feature selection preserves important medical attributes, while PCA may lose interpretability.

---

## 📁 Dataset

- Heart Disease Dataset (UCI / Kaggle)
- Features include:
  - Age, Sex, Chest Pain Type
  - Blood Pressure, Cholesterol
  - Heart Rate, ECG Results, etc.

---

## 🚀 How to Run

1. Open Google Colab or Jupyter Notebook  
2. Upload `heart.csv` dataset  
3. Run the notebook step-by-step:
   - Data preprocessing  
   - Model training  
   - Feature selection experiments  
   - Evaluation  

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 📌 Key Highlights

- End-to-end ML pipeline
- Comparative research approach
- Focus on healthcare-critical metrics
- Clean and reproducible implementation

---

## 🔮 Future Work

- Hyperparameter tuning (GridSearchCV)
- Deep Learning models (ANN)
- Deployment as a web app
- Real-time patient data integration

---

## 👨‍💻 Author

**Apoorv Chaubey**  
B.Tech Computer Science Engineering  

---

## ⭐ If you found this useful

Give this repo a ⭐ and feel free to fork or contribute!
