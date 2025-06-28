# 🎓 Student Performance Analysis

This project uses machine learning to predict students' final grades (`G3`) based on a variety of academic and personal features. It was built as part of an internship selection process and demonstrates key steps in data science, including EDA, modeling, and evaluation.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository – Student Performance Dataset
- **Attributes**: Prior grades, study time, failures, absences, family background, and more
- **Target Variable**: Final grade (`G3`)

---

## 📊 Project Workflow

### ✅ Step 1: Import Libraries & Load Dataset
- Imported pandas, numpy, matplotlib, seaborn, and scikit-learn
- Loaded CSV data and inspected structure

### ✅ Step 2: Data Preprocessing
- One-hot encoded categorical features
- Checked for nulls, cleaned column types

### ✅ Step 3: Exploratory Data Analysis (EDA)
- Visualized distribution of final grades (`G3`)
- Created heatmap to explore correlations
- Boxplots for understanding feature impact

### ✅ Step 4: Model Building (Linear Regression)
- Split data into training and test sets
- Trained a Linear Regression model
- Evaluated using:
  - R² Score: **0.72**
  - Mean Absolute Error: **1.65**
- Added residual analysis for error patterns
- Applied 5-fold cross-validation  
  - Mean R²: **0.78**

### ✅ Step 5: Insights & Conclusion
- G1 and G2 (prior grades) are the strongest predictors
- Study time and past failures also impact G3
- Built a solid baseline model for student performance prediction

---

## 🚀 Key Technologies

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📌 Results Summary

| Metric               | Value  |
|----------------------|--------|
| R² Score             | 0.72   |
| Mean Absolute Error  | 1.65   |
| Cross-Validated R²   | 0.78   |

---

## ✅ How to Run

1. Clone this repo or download the `.ipynb` file
2. Install dependencies:  
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Run the notebook step-by-step in Jupyter or Google Colab

---

## 📄 Disclaimer

This project was created for educational and internship evaluation purposes. The dataset is public, and all work is original.

---

## 📬 Contact

**Sneha**  
Student, BCA (Data Science)  
Email: snehajha.3006@gmail.com 
