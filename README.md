# student-performance-analysis
# 🎓 Student Performance Prediction

This project applies supervised machine learning to predict whether a student will **pass or fail** based on academic, demographic, and social factors. It demonstrates end-to-end steps including data exploration, feature engineering, and model evaluation using real-world educational data.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- **File**: `student-mat.csv` (Math course dataset)
- **Records**: 395 students
- **Features include**:
  - Demographics (age, gender, address, etc.)
  - Social background (parent education, family support)
  - Study habits (study time, absences, failures)
  - Academic grades (`G1`, `G2`, `G3`)

---

## 🧠 ML Workflow

1. **Load and clean the dataset**
2. **EDA (Exploratory Data Analysis)**:
   - Distribution plots
   - Boxplots
   - Correlation heatmaps
   - Violin plots and bar charts
3. **Feature Engineering**:
   - One-hot encoding of categoricals
   - Derived binary column `pass_fail` from `G3`
4. **Model Training & Evaluation**:
   - Logistic Regression
   - Decision Tree Classifier
5. **Evaluation Metrics**:
   - Accuracy score
   - Confusion matrix
   - Classification report

---

## 🔍 Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | ~83%     |
| Decision Tree       | ~81%     |

Both models performed decently, with Logistic Regression slightly outperforming the decision tree. Study time, past failures, and absences were strong predictors of student success.

---

## 📌 Conclusion

This project demonstrates how simple machine learning models can be used to **analyze and predict educational outcomes**. Using a real dataset from Portuguese schools, we found that student performance can be meaningfully predicted using features related to behavior, study habits, and social background.

> Future improvements could include adding ensemble models, hyperparameter tuning, and deploying the model using a web interface.

---

## 🔧 Tech Stack

- Python (Jupyter Notebook)
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

---

## 📁 Project Structure
Student-Performance-Prediction/
├── README.md
├── student-mat.csv 
├── student_performance.ipynb 
└── LICENSE )

---

## 👩‍💻 Author

**Sneha Jha**  
BCA (Data Science), 5th Semester  
Aspiring Data Scientist

---

## 📝 License

This project is open-source and available under the [MIT License](./LICENSE).
