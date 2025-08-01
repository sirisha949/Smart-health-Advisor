🧠 Smart Health Advisor (AI-Powered Medical Recommendation System)

📌 Smart Health Advisor Overview
Smart Health Advisor is a machine learning-based application that offers intelligent health support by recommending medicines, diet plans, precautionary steps, and exercise routines based on user symptoms or diagnoses. It aims to democratize access to early-stage medical advice and wellness guidance.

📝 Abstract
This platform leverages multiple machine learning algorithms to analyze user-reported symptoms and predict probable diseases. Based on the diagnosis, it provides appropriate medicine suggestions and personalized recommendations for lifestyle adjustments including diet, precautions, and workout routines. Designed with a clean frontend and a Flask-powered backend, this tool bridges the gap between users and preliminary healthcare support.

🚀 Features

  Symptom-based Disease Prediction using ML models
  Medicine Suggestions based on predicted illness
  Diet Plan Generator
  Exercise & Workout Recommendations
  Precautionary Guidelines
  Responsive and User-Friendly Web UI
  Modular ML Model Integration
  Real-time Query Handling via Flask API

🛠️ Technologies Used

 Frontend: HTML, CSS, JavaScript
 Backend: Flask, Python
 Machine Learning: SVC, KNN, Random Forest
 Data Processing: Pandas, NumPy, Scikit-learn
 Communication: RESTful API (Flask)

📝 Installation Steps

1. Clone the Repository

bash
git clone https://github.com/your-username/Smart-health-Advisor.git


2. Set Up the Python Environment

bash
cd Smart-health-Advisor-main
pip install -r requirements.txt

3. Run the Flask Application

bash
python app.py

4. Access the Web App

Navigate to `http://127.0.0.1:5000` in your browser.

📁 Folder Structure

Smart-health-Advisor-main/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── result.html
│   └── ...
├── ML/
│   ├── models/
│   │   ├── svc_model.pkl
│   │   ├── knn_model.pkl
│   │   └── randomforest_model.pkl
│   └── preprocessing.py
├── app.py
├── requirements.txt
└── README.md


🔬 Conclusion
Smart Health Advisor is a smart diagnostic support tool built to assist users in making informed health decisions. By combining machine learning intelligence with an accessible web interface, it delivers quick, tailored medical recommendations. The platform is ideal for early-stage triage and wellness tracking, contributing to accessible digital healthcare.


