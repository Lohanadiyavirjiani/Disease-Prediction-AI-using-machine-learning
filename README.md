# 🩺 Disease Prediction AI

A Machine Learning-based **Disease Prediction System** that predicts possible diseases based on selected symptoms.

The project demonstrates the complete ML workflow, from **data preprocessing and model training to evaluation and deployment through a Flask web application**.

> ⚠️ **Disclaimer:** This project is created for educational purposes only and is not intended to provide medical diagnosis or replace professional medical advice.

## 🚀 Features

* 🔹 Symptom-based disease prediction
* 🔹 Data preprocessing and label encoding
* 🔹 Multiple Machine Learning classification models
* 🔹 Model evaluation and comparison
* 🔹 Best model selection
* 🔹 Interactive Flask web interface
* 🔹 Symptom selection
* 🔹 Disease prediction result
* 🔹 Prediction confidence display

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **XGBoost**
* **Flask**
* **HTML**
* **CSS**

## 🤖 Machine Learning Models

The project uses multiple classification algorithms for disease prediction and compares their performance to select a suitable model.

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

## 🔄 Project Workflow

```text
Symptoms Dataset
       ↓
Data Preprocessing
       ↓
Label Encoding
       ↓
Train/Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Model Comparison
       ↓
Best Model Selection
       ↓
Flask Web Application
       ↓
Disease Prediction
```

## 🌐 Web Application

The Flask-based interface allows users to:

1. Select or enter symptoms
2. Submit the symptoms for prediction
3. Get the predicted disease
4. View the prediction confidence/result

## 📊 Model Evaluation

The trained models are evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

## 📁 Project Structure

```text
Disease-Prediction-AI/
│
├── app.py
├── model/
│   └── trained_model.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
├── dataset/
│   └── Testing.csv
│
├── notebook/
│   └── disease_prediction.ipynb
│
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Lohanadiyavirjiani/Disease-Prediction-AI.git
```

Go to the project folder:

```bash
cd Disease-Prediction-AI
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn xgboost flask
```

Run the Flask application:

```bash
python app.py
```

Then open the local Flask URL in your browser.

## 🎯 Learning Outcomes

Through this project, I learned how to:

* Preprocess real-world datasets
* Encode categorical/target data
* Train multiple classification models
* Compare ML model performance
* Select a suitable model
* Integrate a trained ML model with Flask
* Build an interactive ML web application

## 👩‍💻 Author

**Diya Lohana**

Data Science Student | Machine Learning | Python | Data Analytics

## ⚠️ Disclaimer

This application is an **educational Machine Learning project**. Its predictions should not be considered medical advice or used for actual medical diagnosis. Always consult a qualified healthcare professional for medical concerns.
