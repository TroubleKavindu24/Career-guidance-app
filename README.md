# Overview
This project introduces a personalized gamified platform that helps post-A/L students in Sri Lanka explore and pursue IT-related career paths through skill-based assessments, dynamic recommendations, and guided learning journeys.

## Group Members:
1. Wijesundara S.D.
2. Rukshan M.K.
3. Hewawitharana M.P.
4. Galanga A.I.

# component 01 - Career Recommendation Engine for Students with Strong Analytical Skills 
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

   

##  Key Features

1.Dynamic Quiz Engine: Adjusts quiz difficulty in real-time based on user performance.

2.Career Path Prediction: Predicts the most suitable career path based on user skills and quiz performance.

3.Actionable Next Steps: Recommends practical steps (like courses and certifications) to help users advance in their chosen field.

4.Real-Time Feedback: Provides immediate feedback on user progress and skill level.

##  Technologies Used
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


# Component 02 - Problem-Solving Skill Assessment

# Overview
The problem-solving skill assessment evaluates a student's logical reasoning, critical thinking, and algorithmic approach through adaptive quizzes. The system progressively presents questions of increasing difficulty based on performance, categorizing students into levels (Beginner, Intermediate, Advanced) to recommend suitable career paths and learning resources.

# Objectives
Dataset - https://www.kaggle.com/datasets/thedevastator/dataset-for-solving-math-word-problems

# Key Features
1. AI-powered career recommendations and level classification
2. Gamified learning paths with course suggestions and progress tracking
3. Visual career roadmap and analytics dashboard
4. Final career prediction using collaborative filtering and ML models

# Technologies Used
1. Frontend - React.js, Tailwind CSS
2. Backend - Node js
3. Data processing and Analysis - Numpy, Pandas, Matplotlib
4. Software Requerments - Python, JavaScript
5. ML-Analytics - TensorFlow, PuTorch
6. Database - Mongo DB

# Setup Instructions
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


# Component 3: Leadership Assessment Component for Post-A/L Students

This project is part of the **NEXT platform**, a gamified and interactive career guidance system aimed at empowering post-A/L students in Sri Lanka. This component focuses on identifying and nurturing students with strong **leadership and organizational skills**, guiding them toward **leadership-oriented IT careers**.

---

##  Component Focus: Students with Leadership/Organizational Strengths

- Identify students with exceptional **leadership, decision-making, planning, and team management** capabilities.
- Use **scenario-based simulations, strategic problem-solving, and personality tests** to assess these strengths.
- Generate a **personalized career roadmap** toward roles such as:
  - IT Project Manager  
  - Technology Consultant  
  - Tech Entrepreneur
- Use **gamification** and **visual analytics** to keep students engaged and motivated.

---

##  Key Requirements

###  User Requirements
- Take leadership and personality assessments  
- Experience interactive decision-making simulations  
- View skill reports and visual feedback  
- Get a personalized career roadmap  
- Earn badges/points for engagement  
- Track leadership growth over time  

###  Functional Requirements
- Run Unity-based simulations for leadership assessment  
- Analyze decisions and actions to evaluate leadership traits  
- Generate dashboards and visual reports  
- Map user profiles to leadership IT careers  
- Display adaptive career roadmaps  
- Persist user progress and skill data  
- Integrate gamification and achievement tracking  

---

##  Technologies Used

###  Frontend
- **Framework:** React Native  
- **State Management:** Redux  
- **Tool:** Visual Studio Code  

###  Backend
- **Framework:** Node.js + Express.js  
- **Authentication:** Firebase Auth (Google login)  
- **Database:** MongoDB Atlas  
- **Tool:** Visual Studio Code  

###  Machine Learning
- **Framework:** FastAPI  
- **Libraries:** Scikit-learn / TensorFlow, Pandas, NumPy  
- **Tool:** Google Colab  

###  Other Tools
- **APIs:** REST APIs for communication  
- **Version Control:** Git & GitHub  

---

##  Getting Started

### Prerequisites
- Node.js and npm  
- MongoDB Atlas account  
- Firebase project with Google Authentication  
- Python 3.8+ (for FastAPI model)  

---

### 🎨 ***Component 04 - Personalized Career Planner for Students with Artistic and Creative Talents***

This component focuses on empowering students with strong artistic and creative abilities by guiding them toward technology-integrated creative careers such as UI/UX Design, Game Design, Multimedia Arts, and Creative Development. The system evaluates creative skills using adaptive assessments and portfolio-based analysis. Based on the results, it recommends personalized career paths and skill-building courses, allowing users to grow from beginner to expert in their chosen creative domain.


## 🔢 **Functions**

---

### **Function 1: Adaptive Quiz & Creative Skill Categorization**

This function delivers an adaptive quiz system that evaluates users based on their performance in creativity-based tasks such as:

- Visual design understanding  
- Storytelling  
- Innovation  
- Problem-solving  

Users are assessed progressively from easy to hard levels.

**Key Mechanics:**
- **Initial Skill Diagnosis**: Easy-level questions identify baseline creative aptitude.
- **Adaptive Progression**: Users are promoted to medium and hard-level questions based on their correct responses or reverted to easier levels if they struggle.
- **Creative Tier Classification**: After the quiz, users are placed into one of three tiers:
  - Intermediate  
  - Advanced  
  - Expert

---

### **Function 2: Portfolio Analysis & ML-Driven Recommendation**

This function allows users to submit creative portfolios (e.g., designs, sketches, mockups), which are analyzed using computer vision and scoring logic. Combined with quiz performance, this data feeds into a trained ML model.

**Steps Involved:**
- **Portfolio Upload**: Users upload samples of their creative work (images, PDFs, videos).
- **Creative Pattern Recognition**: 
  - Uses OpenCV and TensorFlow to detect:
    - Innovation  
    - Style consistency  
    - Design language
- **Career Path Matching**: 
  - Uses collaborative filtering to suggest career paths followed by similar creative profiles, such as:
    - Visual Designer  
    - Game Artist  
    - UI Developer

---

### **Function 3: Progressive Skill Growth & Auto-Upgrading**

As users complete recommended courses (e.g., from Udemy) and upload completion certificates, the system automatically tracks their progress and upgrades their creative tier level.

**Core Features:**
- **Skill Upgrade System**: Completion of learning objectives results in promotion to the next creative level.
- **Final Stage**: Upon reaching the “Expert” level:
  - The system finalizes career recommendations.
  - A personalized roadmap toward relevant job roles is visualized.

---

## 💡 **Key Features**

- **Creative Adaptive Quiz**: Dynamically adjusts question difficulty and creativity challenges based on user performance.  
- **Portfolio-Based Analysis**: Leverages image and pattern recognition for skill scoring.  
- **Tiered Skill Classification**: Categorizes users from Novice to Expert based on performance.  
- **Career Path Recommendation**: Suggests personalized tech-career tracks in creative domains.  
- **Roadmap Visualization**: Shows visual journey from learning to career alignment.  
- **Auto-Level Upgrades**: Recognizes completed courses and updates user skill level.

---

## 🛠️ **Technologies Used**

- **Frontend**: React Native, Tailwind CSS (for responsive and creative UI design)  
- **Backend**: Node.js, Flask (Python) for quiz engine, portfolio analysis, and ML integration  
- **Machine Learning**: TensorFlow & OpenCV for creative pattern analysis  
- **Recommendation System**: Surprise library (collaborative filtering)  
- **Database (optional)**: MongoDB or Firebase to store user profiles, quiz scores, and portfolio links  
- **API**: Flask REST API for frontend-backend communication



## 🔧 **Setup Instructions**

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


