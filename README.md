# 🎓 Placement Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a student will be placed or not based on their academic performance, skills, and background using Machine Learning algorithms.

The dataset contains student placement records and various features such as academic percentages, work experience, specialization, and test scores.

---

## 📊 Problem Statement
To build a classification model that predicts **placement status (Placed / Not Placed)** of students using historical data.

---

## 🗂️ Dataset Information
- Source: Campus Placement Dataset
- Total Records: 215
- Target Variable: `status` (Placed / Not Placed)

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Loaded dataset using Pandas
- Handled missing values in `salary` column
- Removed irrelevant columns like `sl_no`, `ssc_b`, `hsc_b`
- Converted categorical variables into numeric format

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of academic percentages
- Visualized placement trends using bar plots and count plots
- Detected and removed outliers using IQR method

---

### 3. Feature Engineering
- Applied Label Encoding for binary categorical features
- Used One-Hot Encoding for multi-category variables like:
  - hsc_s
  - degree_t

---

### 4. Model Building
Implemented multiple classification algorithms:
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)

---

### 5. Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🏆 Results
- Logistic Regression achieved the best performance (~83% accuracy)
- Decision Tree and SVM showed comparatively lower performance

---

## 📈 Key Insights
- Students with higher academic scores have better placement chances
- Work experience positively impacts placement probability
- Specialization and degree type also influence placement outcomes

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run This Project
```bash
# Clone repository
git clone https://github.com/your-username/placement-prediction.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run notebook
jupyter notebook
