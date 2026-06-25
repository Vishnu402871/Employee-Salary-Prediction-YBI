
# 💼 EMPLOYEE SALARY PREDICTION

> Built with `Streamlit`, `scikit-learn`, `xgboost`, `pandas`, and `joblib`

---

## 📑 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Testing](#testing)
- [License](#license)

---

## 📖 Overview

**Employee Salary Prediction** is a streamlined ML-based web tool for estimating employee salaries based on inputs like age, gender, education, experience, and job title. It empowers HR professionals and analysts to make fast, informed decisions.

---

## 🚀 Features

✅ **Model Training & Tuning**: Uses XGBoost for efficient regression and smart feature handling  
✅ **Interactive Web App**: User-friendly Streamlit interface for real-time predictions  
✅ **Pre-trained Model**: Easily deploy the app with no need for retraining  
✅ **Production-Ready**: Scalable code and reusable model pipeline  
✅ **Data Pipeline**: Combines preprocessing and model inference in one neat flow

---

## 📁 Project Structure

```
employee-salary-prediction/
├── app.py                      # Streamlit web application
├── train_model.ipynb           # Model training notebook file
├── better_salary_model.joblib  # Trained salary prediction model
├── salary-data.csv             # Training data
├── requirements.txt            # Python dependencies
└── README.md                   # You are here!
```

---

## 🛠️ Getting Started

### 🔧 Prerequisites

Make sure you have:

- Python 3.8+
- Git
- Pip

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mohammadsarfarazafzal/employee-salary-prediction.git
   cd employee-salary-prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

### 🚀 Usage

To launch the app locally:

```bash
streamlit run app.py
```

The app will be accessible at: `http://localhost:8501`

---

## 🧪 Testing

If you wish to run tests (if added), use:

```bash
pytest
```

---


---

## 🙌 Acknowledgments

- [Streamlit](https://streamlit.io/)
- [scikit-learn](https://scikit-learn.org/)
- [XGBoost](https://xgboost.readthedocs.io/)
- [pandas](https://pandas.pydata.org/)
- Developed by [Mohammad Sarfaraz Afzal](https://github.com/mohammadsarfarazafzal)

---
