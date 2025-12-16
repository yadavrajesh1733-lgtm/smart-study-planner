<!-- Final project README for the Building AI course
created by Reaktor Innovations and University of Helsinki -->

# Smart Study Planner

Final project for the Building AI course

## Summary
Smart Study Planner is an AI-powered application that helps students estimate how many hours they should study for an exam. It uses simple machine learning to analyze time before the exam, subject difficulty, and previous performance to provide personalized study hour recommendations.

## Background
Many students struggle with time management and often do not know how much time to dedicate to studying for exams. This problem is very common among school and college students, especially during exam periods.

My motivation for this project comes from my own academic experience, where improper study planning led to stress and inefficient preparation. This topic is important because better planning can improve performance while reducing anxiety and burnout.

Problems addressed:
* Poor study time estimation
* Inefficient exam preparation
* High stress due to last-minute studying

## How is it used?
The user opens the application and provides basic inputs such as:
- Number of days remaining before the exam  
- Difficulty level of the subject  
- Previous exam score  

Based on these inputs, the system predicts the recommended number of study hours.  
The solution is useful for students during exam preparation periods and can be accessed anytime through a simple web interface. The primary users are students who want better time management and personalized study guidance.

## Data sources and AI methods
The project uses a small, structured dataset containing historical study behavior and outcomes. The data is stored in CSV format and is used only for demonstration purposes.

AI methods used:
- Linear Regression (supervised machine learning)
- Data preprocessing using pandas
- Model implementation using scikit-learn

## Challenges
This project does not consider individual learning styles, mental health factors, or external responsibilities such as part-time jobs. The predictions are approximate and should not be treated as exact rules.

Ethical considerations include:
- Avoiding over-reliance on AI recommendations
- Ensuring no personal or sensitive data is collected
- Using the system only as a supportive tool

## What next?
In the future, this project could be improved by:
- Adding personalized learning preferences
- Using more advanced machine learning models
- Integrating progress tracking and reminders
- Expanding the dataset for better accuracy

## Acknowledgments
* Building AI course by Reaktor Innovations and University of Helsinki
* scikit-learn documentation
* Streamlit documentation

pip install streamlit pandas scikit-learn

