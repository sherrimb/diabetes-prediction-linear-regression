# 🩺 Diabetes Progression Prediction with Linear Regression

This project demonstrates how to use linear regression to predict diabetes progression scores using patient data. It uses the built-in diabetes dataset from scikit-learn and compares two models: one using all features and one using just BMI.

---

## 📘 Overview

This notebook explores the relationship between patient features such as age, BMI, and blood pressure with the goal of predicting disease progression.

The project walks through:
- Loading and examining the dataset
- Visualizing feature distributions and relationships
- Training a linear regression model on all features
- Training a simpler model on only the most important feature
- Evaluating both models using RMSE and scatter plots

---

## 🧪 Models & Results

| Model               | Features Used      | RMSE   |
|--------------------|--------------------|--------|
| Full Regression     | All 10 features     | 53.85  |
| Simple Regression   | Only `bmi`          | 63.73  |

The lower RMSE in the full model suggests that combining features provides a more accurate prediction than using BMI alone.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/diabetes-prediction-linear-regression.git
2.	Install required libraries:
pip install -r requirements.txt
3. Open Notebook
jupyter notebook diabetes_regression.ipynb

📷 Sample Output

A scatter plot comparing actual vs predicted diabetes scores helps visualize model accuracy.

⸻
💡 What I Learned
	•	How to apply linear regression with scikit-learn
	•	The value of feature exploration and correlation
	•	Why BMI is a powerful feature for predicting diabetes
	•	How simpler models compare to more complex ones

🌟 Author

Created with ❤️ by Sherri Killough
 | AI & Fitness Enthusiast | Based in Ruskin, FL
	•	🔗 https://www.linkedin.com/in/sherrikillough
	•	🐙 GitHub  https://github.com/sherrimb
