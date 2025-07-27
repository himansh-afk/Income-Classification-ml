# Income-Classification-ml
A machine learning project that classifies whether an individual's income exceeds $50K/year using demographic features from the UCI Adult dataset.


# Income Classification Using Machine Learning

This project uses the **UCI Adult Income dataset** to classify whether an individual's income is above or below $50K based on demographic and employment features using machine learning algorithms.

---

## 📊 Dataset Information

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- Records: 48,842
- Features: 14 (age, workclass, education, occupation, capital-gain, hours-per-week, etc.)
- Target: `income` (<=50K or >50K)

---

## 🧠 Objective

To build a machine learning model that predicts a person's income category based on demographic and employment-related attributes.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook / Google Colab
- pandas, numpy, matplotlib, seaborn
- scikit-learn

---

## 📈 ML Models Used

- Logistic Regression
- Decision Tree
- Random Forest

---

## ⚙️ Steps Followed

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Encoding
4. Model Training and Evaluation
5. Result Analysis

---

## 🏁 Results

- **Best Accuracy:** Random Forest (~85%)
- Key influencing features: `education`, `occupation`, `hours-per-week`, `capital-gain`

![Boxplot](images/boxplot_age.png)  
*Example: Age distribution boxplot*

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `IBM_Income_Classification.ipynb` | Full Jupyter Notebook |
| `Project_Presentation.pptx` | Capstone PPT Slides |
| `adult.csv` | Dataset used |
| `README.md` | This file |

---

## 📌 Future Scope

- Add deep learning models (ANN)
- Use SHAP values for explainable AI
- Deploy as a web app using Flask/Django

---

## 🙏 Acknowledgments

- UCI ML Repository
- Scikit-learn Documentation
- EduNet Foundation (if this was part of your course)


