# Phishing Website Detection Using Machine Learning

## Overview

Phishing websites are one of the most common cybersecurity threats that attempt to steal sensitive user information such as usernames, passwords, banking credentials, and personal data. This project presents a Machine Learning-based phishing website detection system that analyzes URL patterns and predicts whether a website is legitimate or phishing.

The system uses URL lexical analysis, Count Vectorizer feature extraction, and Logistic Regression classification to achieve high accuracy while maintaining fast prediction speed. The trained model is deployed through a Flask web application for real-time phishing detection.

---

## Features

* Real-time phishing URL detection
* URL lexical analysis and preprocessing
* Count Vectorizer for feature extraction
* Logistic Regression and Multinomial Naïve Bayes models
* Flask-based web application
* Lightweight and scalable architecture
* High detection accuracy (~96%)

---

## Technologies Used

### Programming Language

* Python

### Framework

* Flask

### Libraries

* Scikit-Learn
* Pandas
* NumPy
* NLTK
* Joblib
* Pickle

### Machine Learning Models

* Logistic Regression
* Multinomial Naïve Bayes

---

## Dataset

The dataset was collected from publicly available phishing and legitimate URL repositories including:

* PhishTank
* Kaggle
* UNB Dataset
* Public URL repositories

The dataset contains both phishing and legitimate URLs used for model training and evaluation.

---

## System Workflow

1. Data Collection
2. URL Preprocessing
3. Tokenization and Lexical Analysis
4. Feature Extraction using Count Vectorizer
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Flask Deployment
9. Real-Time URL Prediction

---

## Project Structure

```text
Phishing-Website-Detection-Using-Machine-Learning
│
├── Dataset/
├── templates/
├── app.py
├── train_model.py
├── requirements.txt
├── phishing.pkl
├── phishing_mnb.pkl
├── vectorizer.pkl
├── model_metrics.json
├── run.bat
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Bidyut023/Phishing-Website-Detection-Using-Machine-Learning.git
```

### Navigate to Project Folder

```bash
cd Phishing-Website-Detection-Using-Machine-Learning
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Results

| Model                   | Accuracy |
| ----------------------- | -------- |
| Logistic Regression     | 96.2%    |
| Multinomial Naïve Bayes | 94.1%    |

Logistic Regression achieved the best performance and was selected as the final deployment model.

---

## Future Enhancements

* WHOIS Feature Integration
* HTML Content Analysis
* Browser Extension Development
* Deep Learning Models (CNN, LSTM, RNN)
* Ensemble Learning Approaches
* Real-Time Threat Monitoring Dashboard

---

## Authors

* Bidyut Maji 
* Karan Shaw
* Harsh Raj 
* Jishu Mahato 

Department of Computer Science and Engineering 

Haldia Institute of Technology

---

## Project Guide

Dr. Sabyasachi Pramanik
Associate Professor
Department of Computer Science and Engineering
Haldia Institute of Technology

---

## License

This project is developed for educational and academic purposes as part of the Bachelor of Technology (B.Tech) curriculum.
 
