# smart-study-planner
## Summary
Smart Study Planner is an AI-powered application that helps students estimate the number of study hours required for an exam using machine learning. The system considers the time available before the exam, subject difficulty, and previous academic performance to provide personalized study recommendations. This project was created as part of the Building AI course to demonstrate how simple AI models can support effective learning and time management.
# Smart Study Planner

Smart Study Planner is an AI-powered system that helps students estimate how many hours they should study for an exam based on the time available, subject difficulty, and previous academic performance.

This project is developed as part of the **Building AI** course and demonstrates how simple machine learning models can assist in better learning and time management decisions.

---

## Problem
Many students struggle to decide how much time they should dedicate to studying for exams. Poor planning can lead to stress or underperformance.

---

## Solution
The Smart Study Planner uses a **Linear Regression** model to recommend study hours based on:
- Days before the exam
- Subject difficulty
- Previous score

---

## Data & AI Methods
- Dataset: Historical study data in CSV
- Model: Linear Regression (scikit-learn)
- Interface: Streamlit web application

---

## How to Run

1. Install requirements:
```bash
pip install streamlit pandas scikit-learn

