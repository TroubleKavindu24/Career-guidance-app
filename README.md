# Career-guidance-app

Overview
A mobile-based, gamified platform designed to guide Sri Lankan post-A/L students toward IT careers. Identifies individual strengths through profiling, skill assessments, and simulations. Categorizes students into four types: problem solvers, creatives, analytical thinkers, and leaders. Generates personalized career roadmaps using machine learning and gamification. Aims to make career exploration engaging, adaptive, and aligned with each student’s potential.

Objectives
Leadership and Organizational Strengths Skill Assessment - 
problem-solving skill Assessment - The problem-solving skill assessment evaluates a student's logical reasoning, critical thinking, and algorithmic approach through adaptive quizzes. The system progressively presents questions of increasing difficulty based on performance, categorizing students into levels (Beginner, Intermediate, Advanced) to recommend suitable career paths and learning resources.
Artistic and Creative Talents Assessment - 
Strong Analytical Skill Assessment - 

Key Features
Skill-based quizzes to assess student strengths (creative, analytical, leadership, problem-solving)
AI-powered career recommendations and level classification
Gamified learning paths with course suggestions and progress tracking
Visual career roadmap and analytics dashboard
Final career prediction using collaborative filtering and ML models

Technologies Used
Frontend - React.js, Tailwind CSS
Backend - Node js
Data processing and Analysis - Numpy, Pandas, Matplotlib
Software Requerments - Python, JavaScript
ML-Analytics - TensorFlow, PuTorch
Database - Mongo DB

Setup Instructions
1. Clone the repository: git clone <repo_url>
2. Navigate to frontend and run
    cd frontend  
    npm install  
    npm run dev
3. Navigate to backend and run
    cd backend  
    npm install  
    npm run start
4. For model testing (Python)
    cd ml-model  
    pip install -r requirements.txt  
    python train.py

Group Members:
1. Wijesundara S.D.
2. Rukshan M.K.
3. Hewawitharana M.P.
4. Galanga A.I.


# component 01 - Career Recommendation Engine for Students with Strong Analytical Skills 🎓
This Component  aims to create an adaptive quiz system that assesses users’ skills in key areas like data interpretation, critical thinking, pattern recognition, and statistics. Based on the user's quiz performance, the system provides personalized career path recommendations and offers actionable next steps to help them grow. This solution is designed to guide students, professionals, and career changers into data-driven careers, such as data science, business analytics, and machine learning.

## Function 1: Adaptive Quiz Engine for Career Path Recommendation

This function implements an adaptive quiz engine that dynamically adjusts the quiz difficulty based on the user’s responses. The quiz starts with easy-level questions, progresses to medium-level, and eventually includes hard-level questions, depending on how well the user performs.

1. Initial User Assessment: Easy questions are asked initially to assess baseline skills.

2. Adaptive Learning: The system adapts to the user’s performance, asking more difficult questions if the user answers correctly, or providing easier ones if they struggle.

3. Personalized Career Path: After completing the quiz, the system evaluates the user’s skill level and recommends a career path (e.g., Data Analyst, Machine Learning Engineer).

## Function 2: Career Path Prediction Using Machine Learning

After the user completes the quiz, the trained neural network model predicts their skill level and suggests the best career paths aligned with their abilities. The model is trained using a large dataset of user responses, enabling it to make accurate predictions about which career paths are most suitable.

1. Model Training: The model is trained with historical data and user responses to predict the appropriate career path.

2. Real-Time Prediction: Once the user finishes the quiz, the system uses the trained model to predict the user’s skill level (Beginner, Intermediate, or Advanced).

3. Recommended Career Path: The system suggests a tailored career path and provides next steps such as courses, certifications, or projects to further develop the user’s skills.

   

## 💡 Key Features

1.Dynamic Quiz Engine: Adjusts quiz difficulty in real-time based on user performance.

2.Career Path Prediction: Predicts the most suitable career path based on user skills and quiz performance.

3.Actionable Next Steps: Recommends practical steps (like courses and certifications) to help users advance in their chosen field.

4.Real-Time Feedback: Provides immediate feedback on user progress and skill level.

## 🛠️ Technologies Used
Frontend: React, Tailwind CSS (for responsive UI design)

Backend: Flask (Python) for serving the model and handling requests

Machine Learning: TensorFlow for training and deploying the model

Database: Optional (e.g., SQL/NoSQL) for storing user data and quiz results

API: Flask REST API for integration between frontend and backend

 ## Setup Instructions


Node.js (for React frontend)

Python 3.X (for backend and machine learning model)

TensorFlow (for training and running the machine learning model)

Flask (for backend API)

Tailwind CSS (for styling)




