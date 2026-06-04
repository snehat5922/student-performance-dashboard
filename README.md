# 🎓 Student Performance Analytics Dashboard

A comprehensive Streamlit-based data analytics dashboard designed to analyze factors affecting student academic performance. This project provides interactive visualizations, performance insights, and machine learning-based score prediction using student demographic, academic, family, and lifestyle data.

---

## 📌 Project Overview

Student performance is influenced by multiple factors including study habits, attendance, parental involvement, lifestyle, and previous academic achievements.

This dashboard helps educators, students, and researchers understand:

* Academic performance trends
* Study habit effectiveness
* Family background influence
* Lifestyle impacts on learning
* Student success prediction

---

## 🚀 Features

### 📊 Executive Dashboard

* Student KPIs
* Average Exam Score
* Attendance Analysis
* Study Hours Overview
* Performance Distribution

### 📚 Academic Performance Analysis

* Study Hours vs Exam Score
* Attendance vs Exam Score
* Score Distribution
* Performance Trends

### 📖 Study Habits Analysis

* Motivation Level Impact
* Tutoring Sessions Analysis
* Study Time Evaluation
* Learning Pattern Insights

### 👨‍👩‍👧 Family Background Analysis

* Family Income Impact
* Parental Education Analysis
* Academic Support Evaluation
* Socioeconomic Factors

### 🏃 Lifestyle Impact Analysis

* Sleep Hours vs Exam Score
* Physical Activity Impact
* Health and Academic Performance
* Student Wellbeing Insights

### 🤖 Performance Prediction

* Machine Learning Model
* Exam Score Prediction
* Interactive Input Parameters
* Academic Outcome Estimation

---

## 📂 Dataset Information

The dataset contains approximately:

* 6,607 Student Records
* 20 Features
* Academic Indicators
* Lifestyle Factors
* Family Background Attributes
* Performance Metrics

### Example Features

| Feature           | Description                   |
| ----------------- | ----------------------------- |
| Hours_Studied     | Daily study hours             |
| Attendance        | Attendance percentage         |
| Previous_Scores   | Previous academic performance |
| Sleep_Hours       | Daily sleep duration          |
| Physical_Activity | Exercise frequency            |
| Family_Income     | Family economic status        |
| Motivation_Level  | Student motivation category   |
| Exam_Score        | Final examination score       |

---

## 🛠 Technology Stack

### Frontend

* Streamlit

### Data Processing

* Pandas
* NumPy

### Visualization

* Plotly
* Matplotlib

### Machine Learning

* Scikit-Learn

### Deployment

* Streamlit Community Cloud

---

## 📁 Project Structure

student-performance-dashboard/

├── app.py

├── data/
│   └── StudentPerformanceFactors.csv

├── pages/
│   ├── 1_Executive_Summary.py
│   ├── 2_Academic_Performance.py
│   ├── 3_Study_Habits_Analysis.py
│   ├── 4_Family_Background_Analysis.py
│   ├── 5_Lifestyle_Impact.py
│   └── 6_Performance_Predictor.py

├── assets/
│   ├── logo.png
│   └── banner.png

├── utils/
│   ├── data_loader.py
│   ├── charts.py
│   └── insights.py

├── requirements.txt

├── README.md

└── .streamlit/
└── config.toml

---

## ⚙ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-performance-dashboard.git
cd student-performance-dashboard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the dashboard:

```bash
streamlit run app.py
```

---

## 📈 Dashboard Pages

### 1️⃣ Executive Summary

Provides a high-level overview of student performance metrics.

### 2️⃣ Academic Performance

Analyzes relationships between attendance, study habits, and exam scores.

### 3️⃣ Study Habits Analysis

Examines how motivation and tutoring influence academic success.

### 4️⃣ Family Background Analysis

Explores family-related factors affecting performance.

### 5️⃣ Lifestyle Impact

Studies the influence of sleep and physical activity on academic outcomes.

### 6️⃣ Performance Predictor

Uses Machine Learning to predict exam scores based on student inputs.

---

## 🤖 Machine Learning Model

Model Used:

* Random Forest Regressor

Input Features:

* Hours Studied
* Attendance
* Previous Scores
* Sleep Hours
* Tutoring Sessions
* Physical Activity

Output:

* Predicted Exam Score

---

## 📊 Sample Insights

* Students with higher attendance generally achieve better exam scores.
* Study hours positively correlate with academic performance.
* Previous academic achievement is a strong predictor of future success.
* Adequate sleep contributes to improved examination results.
* Higher motivation levels are associated with stronger performance.

---

## 🌐 Deployment

Deploy easily using Streamlit Cloud:

1. Push project to GitHub
2. Open Streamlit Community Cloud
3. Connect GitHub repository
4. Select app.py
5. Deploy

---

## 🎯 Future Enhancements

* Advanced ML Models
* Student Risk Classification
* PDF Report Generation
* Performance Trend Forecasting
* AI-Powered Recommendations
* Interactive Data Export

---

## 👨‍💻 Author

Student Performance Analytics Dashboard

Built using Python, Streamlit, Plotly, Pandas, and Scikit-Learn.

---

## 📄 License

This project is intended for educational and academic purposes.
