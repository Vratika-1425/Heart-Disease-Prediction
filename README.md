<div align="center">

# ❤️ Heart Disease Prediction

### End-to-End Machine Learning System for Early Heart Disease Risk Prediction

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange?style=for-the-badge&logo=scikit-learn)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient_Boosting-yellow?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-green?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-Experiment_Tracking-blue?style=for-the-badge)
![DVC](https://img.shields.io/badge/DVC-Data_Version_Control-purple?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker)

</div>

---

## 📖 Overview

Heart disease is one of the leading causes of death worldwide, making early diagnosis essential for effective treatment and prevention.

This project is an **end-to-end Machine Learning application** that predicts the likelihood of heart disease using patient clinical data. It encompasses the complete ML lifecycle—from data preprocessing and feature engineering to model training, evaluation, and deployment through an interactive Flask web application.

To ensure reproducibility and scalability, the project also integrates **MLflow** for experiment tracking, **DVC** for data versioning, and **Docker** for containerized deployment.


The project follows an end-to-end Machine Learning workflow including:

- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Experiment Tracking using MLflow
- Data Versioning using DVC
- Flask Deployment
- Docker Containerization

---

# 🏗️ Project Architecture

```
                    Heart Disease Dataset
                              │
                              ▼
                    Data Preprocessing
                              │
                              ▼
                 Feature Engineering
                              │
                              ▼
               Train Multiple ML Models
                              │
                              ▼
             Model Evaluation & Comparison
                              │
                              ▼
               Best Model Selection
                              │
                              ▼
             MLflow Experiment Tracking
                              │
                              ▼
                  Flask Web Application
                              │
                              ▼
                     Prediction Result
```

---

# 📂 Project Structure

```
Heart-Disease-Prediction
│
├── Artifacts/
│
├── mlruns/
│
├── Notebook_Experiments/
│
├── src/
│
├── static/
│
├── templates/
│
├── app.py
├── Dockerfile
├── dvc.yaml
├── dvc.lock
├── requirements.txt
├── setup.py
├── README.md
└── LICENSE
```

---

# 🧠 Machine Learning Pipeline

✔ Data Collection

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Model Training

✔ Hyperparameter Optimization

✔ Model Evaluation

✔ Model Serialization

✔ Flask Deployment

✔ Docker Deployment

✔ MLflow Tracking

✔ DVC Versioning

---

# 📊 Dataset Information

The dataset consists of **13 clinical features** used to determine the likelihood of heart disease.

| Feature | Description |
|----------|-------------|
| Age | Patient Age |
| Sex | Gender |
| Chest Pain Type | Chest pain category |
| Resting Blood Pressure | Blood pressure while resting |
| Cholesterol | Serum Cholesterol |
| Fasting Blood Sugar | Blood Sugar Level |
| Rest ECG | Electrocardiographic results |
| Max Heart Rate | Maximum heart rate achieved |
| Exercise Induced Angina | Yes/No |
| Old Peak | ST Depression |
| Slope | Peak exercise ST slope |
| CA | Major vessels |
| Thal | Thalassemia |
| Target | Heart Disease Prediction |

---

# 🤖 Machine Learning Models

The following algorithms were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost
- XGBoost
- CatBoost
- Extra Trees
- K-Nearest Neighbors
- Support Vector Machine

---

# 📈 Experiment Tracking

ML experiments are tracked using **MLflow**.

Features:

- Parameters Logging
- Metrics Logging
- Model Comparison
- Best Model Tracking
- Artifact Storage

---

# 📦 Data Version Control

The project uses **DVC** for:

- Dataset Versioning
- Pipeline Management
- Reproducibility

---

# 🌐 Web Application

The Flask application allows users to:

- Enter patient information
- Predict heart disease instantly
- Display prediction confidence
- Simple responsive UI

---

# 🛠️ Tech Stack

## Programming Language

- Python

## Machine Learning

- Scikit-Learn
- CatBoost
- XGBoost
- Pandas
- NumPy

## Visualization

- Matplotlib
- Seaborn

## Backend

- Flask

## MLOps

- MLflow
- DVC
- Docker

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git

cd Heart-Disease-Prediction
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Visit

```
http://127.0.0.1:5000
```

---

# 🐳 Docker

Build

```bash
docker build -t heart-disease .
```

Run

```bash
docker run -p 5000:5000 heart-disease
```

---

# 📊 Model Workflow

```
Dataset
   │
   ▼
Cleaning
   │
   ▼
EDA
   │
   ▼
Feature Engineering
   │
   ▼
Model Training
   │
   ▼
Evaluation
   │
   ▼
Best Model
   │
   ▼
Flask API
   │
   ▼
Prediction
```

---

# 🔮 Future Improvements

- User Authentication
- Cloud Deployment (AWS/Azure)
- REST API
- SHAP Explainability
- Streamlit Dashboard
- CI/CD Pipeline
- Kubernetes Deployment
- Real-time Monitoring

---

# 🤝 Contributing

Contributions are always welcome!

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Create a Pull Request

---

# 📄 License

Distributed under the MIT License.

See `LICENSE` for more information.

---

# 👨‍💻 Author

**Vratika Sahota**

AI & Data Science Undergraduate

Machine Learning • Deep Learning • MLOps • Full Stack Development


---

<div align="center">


</div>
