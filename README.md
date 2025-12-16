# UPI-Smart-Fraud-Detection-for-Digital-Payments




🚀 UPI-Watch: Smart Fraud Detection for Digital Payments

A Machine Learning–based web application that detects fraudulent UPI transactions using transaction behavior patterns such as time, amount, and frequency.

📌 Project Overview

UPI-Watch is a final-year academic project developed to address the growing problem of fraud in digital payment systems, especially UPI (Unified Payments Interface).
The system uses Machine Learning (Random Forest Classifier) to classify transactions as Fraudulent or Genuine and provides real-time predictions through a Flask-based web interface.

This project demonstrates the practical application of ML, data analysis, and web development in the fintech domain.

🎯 Objectives

Detect fraudulent UPI transactions accurately

Analyze transaction behavior patterns

Build a real-time prediction system

Provide explainable and transparent results

Deploy the ML model using a web application

🧠 Problem Statement

With the rapid increase in UPI usage, fraud cases such as unauthorized transfers, abnormal transaction amounts, and suspicious transaction timings have also increased.
Traditional rule-based systems fail to detect evolving fraud patterns effectively.

Hence, there is a need for a data-driven, intelligent fraud detection system that can:

Learn from historical data

Adapt to new fraud patterns

Provide fast and accurate predictions

💡 Proposed Solution

UPI-Watch uses a Random Forest Machine Learning model trained on transaction-related features such as:

Transaction hour

Day and month

Transaction amount

Transaction frequency

UPI ID characteristics

The trained model is deployed using Flask, allowing users to input transaction details and instantly receive fraud predictions.

🏗️ System Architecture
User (Browser)
      ↓
Web Interface (HTML, CSS)
      ↓
Flask Backend (Python)
      ↓
Random Forest Model (.pkl)
      ↓
Fraud / Genuine Prediction
      ↓
Result Display

🛠️ Tech Stack
🔹 Programming & Libraries

Python

Pandas

NumPy

Scikit-learn

🔹 Machine Learning

Random Forest Classifier

🔹 Web Development

Flask

HTML

CSS

🔹 Tools

Jupyter Notebook

VS Code

Git & GitHub

⚙️ How It Works

User enters transaction details via web form

Flask backend processes the input

Trained Random Forest model predicts the transaction type

Result is displayed as:

✅ Genuine Transaction

⚠️ Fraudulent Transaction

Prediction reasoning is shown for transparency

▶️ How to Run the Project Locally
# Clone the repository
git clone https://github.com/your-username/UPI-Watch.git

# Navigate to project folder
cd UPI-Watch

# Run the application
python app.py


Open browser and go to:

http://127.0.0.1:5000/

📊 Results

High accuracy in detecting fraudulent transactions

Reduced false positives compared to rule-based systems

Efficient real-time predictions

🎓 Academic Relevance

Final Year Engineering Project

Covers:

Machine Learning

Web Application Development

Suitable for Mini Project / Major Project / Capstone

🔮 Future Enhancements

Integration with real banking APIs

Deep Learning models (LSTM for transaction sequences)

Real-time alerts via SMS/Email

Admin dashboard for banks

Online deployment using cloud platforms

👨‍🎓 Developed By

Final Year Student
Department of Computer Science / AI / Data Science

📄 License

This project is developed for educational and academic purposes only.

✅ This README is:

Final-year project friendly
GitHub showcase 
if you want the project codes 
✉ chandrasekharreddy0206@gmail.com



