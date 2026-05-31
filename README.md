# TrafficPolice: ML-Based Network Intrusion Detection System

TrafficPolice is a machine learning based Network Intrusion Detection System using the UNSW-NB15 dataset. It classifies network traffic as Normal or Attack using supervised and unsupervised ML models.

## Features
- Data preprocessing and target encoding
- SMOTE class balancing
- Logistic Regression and Random Forest supervised models
- Isolation Forest and One-Class SVM unsupervised models
- Optuna hyperparameter tuning
- FastAPI dashboard for CSV upload
- Docker containerization
- AWS ECR and Elastic Beanstalk deployment

## Final Results
- Accuracy: 90.06%
- Precision: 99.00%
- Recall: 86.28%
- F1-score: 92.20%

## Run Locally
```bash
pip install -r requirements.txt
uvicorn app.app:app --reload