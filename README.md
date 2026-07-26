# CardioAI

CardioAI is a Flask-based web application that predicts the risk of heart disease using machine learning. Users can register, log in, enter clinical details, and receive a prediction along with health recommendations. The application also stores prediction history and allows users to generate PDF reports.

---

## Features

- User Registration & Login
- Heart Disease Risk Prediction
- Prediction History
- Interactive Dashboard
- PDF Report Generation
- Admin Dashboard
- Responsive User Interface

---

## Tech Stack

- Python
- Flask
- HTML
- CSS
- JavaScript
- Bootstrap 5
- SQLite
- Scikit-learn
- Pandas
- Chart.js

---

## Project Structure

```text
cardio-ai/
│
├── app.py
├── database/
├── dataset/
├── ml/
├── models/
├── reports/
├── static/
├── templates/
├── utils/
├── requirements.txt
└── README.md
```

---

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Train the machine learning model

```bash
python ml/train_model.py
```

4. Start the Flask application

```bash
python app.py
```

5. Open your browser and visit

```text
http://127.0.0.1:5000
```

---

## Dataset

This project uses the **UCI Heart Disease Dataset** for training and evaluating machine learning models.

---

## Future Enhancements

- Doctor Portal
- Appointment Scheduling
- Explainable AI
- Cloud Deployment
- Mobile Application

---

