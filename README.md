
# 🧠 Disease Prediction Using Machine Learning

A Flask-based web application that uses machine learning algorithms to predict four major diseases — **Heart Disease**, **Liver Disease**, **Diabetes**, and **COVID-19** — based on user inputs like symptoms or test data.

---

## 🚀 Overview

The goal of this project is to provide an accessible and intelligent disease screening system using machine learning models. The user-friendly web interface allows individuals to input medical parameters and receive fast, accurate predictions — all without visiting a hospital.

---

## 🔑 Key Features

- 🌡️ Predicts 4 diseases using trained ML models:
  - Heart Disease
  - Liver Disease
  - Diabetes
  - COVID-19
- 📊 Multiple algorithms per disease (Naïve Bayes, KNN, Random Forest, Decision Tree)
- 💾 Prediction history stored using SQLite
- 🌐 Clean web interface using Flask, HTML & CSS
- 📁 Datasets sourced from Kaggle and UCI repositories
- ✅ Accuracy over 90% for most predictions

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Python (Flask)
- **ML Libraries**: Scikit-learn, Pandas, NumPy
- **Database**: SQLite
- **Templating**: Jinja2 (Flask)

---

## 📁 Folder Structure

```
Disease-Predictor/
├── static/             # CSS and JavaScript files
├── templates/          # HTML templates (Jinja2)
├── models/             # Trained ML models (.pkl files)
├── data/               # Raw datasets (CSV, etc.)
├── app.py              # Main Flask application
├── database.db         # SQLite database for user history
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── .gitignore          # Files to ignore in Git
```

---

## 🛠️ Installation Guide

### 📌 Prerequisites
- Python 3.7+
- Git (optional but recommended)

### 💻 Steps

```bash
# Clone the repository
git clone https://github.com/Amangaur31/Disease-Predictor.git
cd Disease-Predictor

# (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate   # On Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

Then open your browser and navigate to:  
👉 http://127.0.0.1:5000

---

## 📊 ML Algorithms Used

Each disease is predicted using multiple models. These include:

- ✅ Naïve Bayes
- ✅ K-Nearest Neighbors (KNN)
- ✅ Random Forest
- ✅ Decision Tree

The model with the highest accuracy is prioritized in the dropdown list on the UI.

---

## 📂 Datasets

- 🫀 [Heart Disease – UCI Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease)
- 🏥 [Liver Patient Dataset – UCI Repository](https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset))
- 🩺 [Diabetes – Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- 😷 [COVID-19 Symptoms – Kaggle](https://www.kaggle.com/code/midouazerty/symptoms-covid-19-using-7-machine-learning-98)

---

## 📌 Disclaimer

> This application is a final-year academic project and is **not intended for real-world clinical use**. It is a demonstration of machine learning capabilities in health prediction scenarios.

---

## 🙏 Acknowledgements

- [Kaggle Datasets](https://www.kaggle.com/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Flask Documentation](https://flask.palletsprojects.com/)
