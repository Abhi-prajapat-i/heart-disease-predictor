❤️ Heart Disease Predictor
📌 Project Overview

Heart Disease Predictor is a Machine Learning web application that predicts the likelihood of heart disease using key medical attributes.

The application is fully deployed on Render, allowing users to access the model online in real-time.

🌐 Live Demo

  🚀 Deployed Application:
  [https://heart-disease-predictor.onrender.com](https://heart-disease-predictor-w4ff.onrender.com)


🧠 Features Used

The model takes the following medical parameters:

Age - Patient age

RestingBP - Resting blood pressure

Cholesterol - Serum cholesterol level

FastingBS - Fasting blood sugar (1 = high, 0 = normal)

MaxHR - Maximum heart rate achieved

Oldpeak - ST depression induced by exercise


📊 Model Details

Algorithm Used: (RandomForestClassifier with score 81%)

Problem Type: Binary Classification

Output:

0 → No Heart Disease

1 → Heart Disease Detected


🖥️ Application Features

User-friendly input form

Real-time prediction

Deployed on Render

Clean UI using HTML & CSS

Backend powered by Flask


## 🗂️ Project Structure

```
heart-disease-predictor/
│
├── app.py              # Flask backend
├── model.pkl           # Trained ML model
├── requirements.txt    # Project dependencies
├── templates/
│   └── index.html      # Frontend UI
└── README.md
```


⚙️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Flask

HTML & CSS

Render (Deployment)

## 🚀 Run Locally

```bash
git clone https://github.com/Abhi-prajapat-i/heart-disease-predictor.git
cd heart-disease-predictor
pip install -r requirements.txt
python app.py
```
Open:

http://127.0.0.1:5000/
