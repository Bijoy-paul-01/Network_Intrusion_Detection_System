# Network Intrusion Detection System (NIDS)

## Overview

This project implements a Machine Learning and Deep Learning based Network Intrusion Detection System (NIDS) using the NSL-KDD dataset. The objective is to detect malicious network traffic and classify various attack types accurately.

The system performs data preprocessing, feature engineering, model training, evaluation, hyperparameter tuning, and attack prediction. Multiple machine learning algorithms are compared to identify the best-performing model for intrusion detection.

---

## Objectives

* Detect malicious network traffic.
* Classify different types of cyber attacks.
* Compare the performance of multiple machine learning models.
* Build a Deep Learning model for intrusion detection.
* Save trained models for future deployment.

---

## Dataset

**Dataset Used:** NSL-KDD (KDDTrain+)

The dataset contains network traffic records labeled as normal or attack traffic and includes various network-based features used for intrusion detection.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow / Keras
* Joblib
* Jupyter Notebook

---

## Machine Learning Models Implemented

### 1. Decision Tree Classifier

Used for classification and comparison of intrusion detection performance.

### 2. Random Forest Classifier

Ensemble learning algorithm used to improve prediction accuracy.

### 3. Support Vector Machine (SVM)

Used for high-dimensional classification of network traffic.

### 4. Artificial Neural Network (ANN)

Deep Learning model developed using TensorFlow and Keras.

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Visualization
4. Label Encoding
5. Feature Scaling
6. Train-Test Split
7. Decision Tree Training
8. Random Forest Training
9. Support Vector Machine Training
10. Model Evaluation
11. Hyperparameter Tuning using GridSearchCV
12. Neural Network Training
13. Attack Prediction
14. Model Saving

---

## Features

* Automatic attack classification
* Data preprocessing pipeline
* Feature scaling and encoding
* Multiple model comparison
* Hyperparameter optimization
* Neural Network implementation
* Confusion Matrix visualization
* Classification Reports
* Saved trained models for deployment

---

## Files Included

```text
Network_Intrusion_Detection_System/
│
├── notebooks/
│   └── NIDS_Project.ipynb
│
├── data/
│   └── KDDTrain+.txt
│
├── models/
│   ├── best_rf_model.pkl
│   ├── scaler.pkl
│   ├── label_encoders.pkl
│   └── attack_encoder.pkl
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

Clone the repository:

git clone https://github.com/yourusername/Network_Intrusion_Detection_System.git

Move to project directory:

cd Network_Intrusion_Detection_System

Install dependencies:

pip install -r requirements.txt

---

## Running the Project

1. Open Jupyter Notebook.
2. Open NIDS_Project.ipynb.
3. Run all cells sequentially.
4. View model training and evaluation results.
5. Test attack detection using sample network traffic.

---

## Results

The project evaluates the performance of:

* Decision Tree
* Random Forest
* Support Vector Machine
* Artificial Neural Network

Random Forest achieved the best performance and was selected as the final prediction model.

---

## Future Enhancements

* Real-time packet monitoring
* Web-based dashboard
* Flask/FastAPI deployment
* Cloud deployment
* Live network traffic analysis
* Integration with cybersecurity monitoring tools

---

## Author

Bijoy Paul

Master of Computer Applications | Data Science Enthusiast

---

## License

This project is developed for educational purposes.
