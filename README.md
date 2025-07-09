# 🌱 Dry Bean Classification using Machine Learning

### 📊 Project Title: Dry Bean Variety Prediction Model  
**Author**: Drusya Krishnakumar  
**Organization**: Entri Elevate  
**Date**: July 2025  

---

## 📌 Problem Statement

Accurate classification of dry beans is essential in agricultural processing, quality control, and commercial sorting. Given the subtle variations between bean varieties, manual identification is inefficient. This project uses machine learning techniques to automate the classification of **7 registered varieties** of dry beans based on image-derived shape and dimension features.

---

## 🎯 Objective

To develop an efficient and accurate ML model to classify dry bean varieties using computer vision-extracted features.

---

## 📁 Dataset Description

- **Dataset Name**: Dry Bean Dataset  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)  
- **Records**: 13,611  
- **Features**: 16 numerical shape descriptors + 1 target class  
- **Target Classes**:
  - Seker, Barbunya, Bombay, Cali, Dermason, Horoz, Sira

---

## 📌 Project Workflow

| Step | Task |
|------|------|
| 1️⃣ | Problem Overview & Objective |
| 2️⃣ | Data Collection |
| 3️⃣ | Data Cleaning & Preprocessing |
| 4️⃣ | Exploratory Data Analysis (EDA) |
| 5️⃣ | Feature Engineering & Encoding |
| 6️⃣ | Feature Selection (RandomForest, SelectKBest) |
| 7️⃣ | Handling Class Imbalance (SMOTE) |
| 8️⃣ | Train-Test Split |
| 9️⃣ | Feature Scaling |
| 🔟 | Model Building (MLP, RF, SVM, LR, GB) |
| 🔍 | Model Evaluation (Accuracy, F1, ROC AUC) |
| 💾 | Save Model using `joblib` |
| 🧪 | Prediction on Unseen Data |
| 📈 | Interpretation of Results |
| 🔮 | Future Work |

---

## 🧠 Algorithms Used

- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- Gradient Boosting  
- Multi-layer Perceptron (MLP Classifier)

---

## 🏆 Best Model: MLP Classifier

| Metric          | Score      |
|-----------------|------------|
| Accuracy        | 90.11%     |
| ROC AUC Score   | 0.991      |
| Macro F1 Score  | 0.91       |

---

## 📉 Challenges Addressed

- ✅ Skewed feature distributions (corrected using `PowerTransformer`)
- ✅ Outlier removal using IQR method
- ✅ Class imbalance handled using SMOTE
- ✅ Feature selection based on Random Forest importance & statistical scoring

---

## 💡 Future Work

- Try deep learning directly on bean images (CNNs)
- Integrate additional image features (color, texture)
- Build an interactive prediction web or mobile app
- Deploy as REST API for scalable use

---

## 🗂️ Files

- `Dry_Bean_Dataset.xlsx` — original dataset  
- `dry_bean_classifier.ipynb` — full Colab notebook  
- `model_mlp_classifier.joblib` — saved model  
- `README.md` — project documentation  

---




📧 **Drusya Krishnakumar**  

📍 Kerala, India

---

> “Machine learning is not about learning from data, it's about discovering patterns to make smart decisions.”  
> – Adapted for Agriculture 🌾
# Dry_bean_classifier
Dry bean classifier model
