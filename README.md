# smart-study-planner
import streamlit as st
import pandas as pd
from sklearn.linear_model import LinearRegression

data = pd.read_csv("data/study_data.csv")
X = data[["days_before_exam", "difficulty", "previous_score"]]
y = data["study_hours"]

model = LinearRegression()
model.fit(X, y)

st.title("Smart Study Planner")

days = st.slider("Days before exam", 1, 60, 15)
difficulty = st.slider("Subject difficulty (1–5)", 1, 5, 3)
score = st.slider("Previous score (%)", 0, 100, 70)

prediction = model.predict([[days, difficulty, score]])
st.write(f"Recommended study hours: {prediction[0]:.1f}")
