# Loan Approval Prediction App

A Machine Learning-based web application that predicts loan approval status using applicant information. Built with Python and Flask, the project combines a prediction workflow with a web interface for loan applications.

## Project Overview

The project explores how machine learning can support loan approval prediction based on applicant and financial attributes. It includes a Flask backend, frontend templates, a dataset, and a Jupyter Notebook for model development.

## Features

- Loan approval status prediction
- Flask-based web application
- HTML and CSS user interface
- Dataset exploration and preprocessing
- Jupyter Notebook for model training and experimentation
- User login and loan-related pages, as implemented in the application

## Tech Stack

- **Language:** Python
- **Web Framework:** Flask
- **Machine Learning:** Scikit-learn
- **Data Analysis:** Pandas, NumPy
- **Frontend:** HTML, CSS
- **Development:** Jupyter Notebook

## Project Files

- `app.py` — Flask application
- `model.ipynb` — Model development notebook
- `LoanApprovalPrediction.csv` — Dataset
- `style.css` — Stylesheet
- HTML files — Web application pages
- `README.md` — Project documentation

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Aniljaiswal-3007/Loan-Status-Prediction-ML.git
cd Loan-Status-Prediction-ML
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**macOS/Linux**
```bash
source venv/bin/activate
```

### 3. Install dependencies

Install the packages required by the project. If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

Otherwise, check the imports in `app.py` and `model.ipynb` and install the required packages.

### 4. Run the application

```bash
python app.py
```

Open `http://127.0.0.1:5000/` in your browser if the application starts successfully.

## Model Evaluation

Add verified evaluation metrics, such as accuracy, precision, recall, and F1-score, after evaluating the trained model. Do not report unverified results.

## Future Improvements

- Improve model evaluation and validation
- Add input validation and error handling
- Improve the user interface and accessibility
- Document model limitations and responsible use

## Contributors

Developed collaboratively. Individual contributions should be documented accurately.

## Disclaimer

This project is for educational and demonstration purposes only. Its predictions should not be used as the sole basis for real-world lending decisions.
 

