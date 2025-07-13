# 📘 Student Performance Predictor for Eduquest Coaching

This project was created as part of the **YBI Foundation Internship**. It uses a machine learning model to predict student performance based on various academic, demographic, and behavioral factors provided by Eduquest Coaching.

The dataset, **Student Performance Predictor for EduQuest Coaching.csv**, contains student-level data such as past exam scores, attendance rate, family income, and more.

---

## 🔧 Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- Google Colab

---

## 🧠 What the Project Does
- Loads and cleans student data  
- Handles missing values  
- Encodes categorical columns such as gender, parental education, internet access, and extracurricular involvement  
- Trains a **Linear Regression** model to predict the final exam score  
- Evaluates the model using **Mean Absolute Percentage Error (MAPE)**

---

## 📊 Dataset Features

| Feature                          | Description                              |
|----------------------------------|------------------------------------------|
| `gender`                         | Student's gender                         |
| `age`                            | Student's age                            |
| `parental_education`             | Highest education level of parents       |
| `family_income`                  | Family's monthly income (in currency)    |
| `internet_access`                | Internet availability at home (Yes/No)  |
| `previous_exam_score`           | Score from the previous exam             |
| `attendance_rate`               | Class attendance rate (%)                |
| `homework_completion_rate`      | Homework completion rate (%)             |
| `class_participation_score`     | Score for classroom participation        |
| `number_of_absences`            | Total absences                           |
| `extra_curricular_involvement`  | Level of involvement (Low/Moderate/High)|
| `learning_hours_per_week`       | Average study hours per week             |
| `tutor_support`                 | Whether the student receives tutoring    |
| `final_exam_score`              | Target variable (score to be predicted)  |

---

## 📈 Result
- The Linear Regression model achieved a **MAPE of 5.7%**
- This indicates an approximate prediction accuracy of **94.3%**

---

## 📁 Files
- `student_performance_predictor.ipynb` – Main Google Colab
- `Student Performance Predictor for EduQuest Coaching.csv` – Dataset used for training and testing
- `README.md` – Project overview and details

---
