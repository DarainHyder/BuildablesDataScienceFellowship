# Buildables Data Science Fellowship

This repository documents my 12-week intensive journey through the Buildables Data Science Fellowship, showcasing a progression from foundational data analysis to deploying advanced machine learning models. It serves as a comprehensive log of projects, codebases, and skills acquired during this transformation into a Data Scientist.

<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

</div>

---

## 📂 Main Projects

This section highlights the three major milestones of my fellowship: the comprehensive Final Project, the high-intensity Hackathon entry, and an insightful Mini Project.

### 1. 🛡️ Final Project: Cyberbullying Detection System
**Type:** End-to-End NLP Multiclass Classification System
**Location:** [`Week_10-12/CyberBullying-DetectionSystem`](Week_10-12/CyberBullying-DetectionSystem)

**Overview:**
A robust Natural Language Processing (NLP) pipeline designed to identify and classify toxic online behavior. The system moves beyond binary classification to detect specific types of cyberbullying (Age, Ethnicity, Religion, Gender, Other).

**Key Technical Features:**
*   **Model:** Logistic Regression with Class Balancing (`class_weight="balanced"`) handling imbalanced real-world data.
*   **Preprocessing:** Custom pipeline including Tokenization, Lemmatization, and TF-IDF Vectorization.
*   **Deployment:**
    *   **API:** High-performance REST API built with **FastAPI**.
    *   **Frontend:** Interactive web application developed using **Streamlit**.
*   **Impact:** Enables real-time content moderation to foster safer digital communities.

### 2. 🌌 Hackathon Project: ExoVision-AI (NASA Space Apps)
**Type:** 48-Hour Global Hackathon Submission
**Location:** [`Week_7/NASA-Space-App`](Week_7/NASA-Space-App)

**Overview:**
Developed during the **NASA Space Apps Challenge 2025**, ExoVision-AI is an automated system for classifying celestial objects as "Confirmed Exoplanets" or "Candidates" using NASA's K2 Planets and Candidates Catalog.

**Key Technical Features:**
*   **Algorithm:** Ensemble approach utilizing **XGBoost** (for performance) and **Decision Trees** (for interpretability), achieving ~99% accuracy.
*   **Data Pipeline:** Automated missing value imputation and feature engineering on stellar parameters.
*   **Interface:** Full-stack web application built with **Flask**, featuring CSV upload capabilities and real-time visualization dashboards (ROC curves, heatmaps).

### 3. 📊 Mini Project: Fellowship Feedback Analysis
**Type:** Exploratory Data Analysis (EDA) & Visualization
**Location:** [`Week_3/Mini-Project`](Week_3/Mini-Project)

**Overview:**
A data-driven analysis of feedback gathered from fellowship participants. This project focuses on cleaning raw survey data and visualizing insights to improve the cohort experience.

**Key Technical Features:**
*   **Data Cleaning:** Handling messy real-world survey data using **Pandas**.
*   **Visualization:** Creating actionable reports and dashboards using **Matplotlib** and **Seaborn**.
*   **Deliverable:** Comprehensive analysis report identifying key trends in curriculum effectiveness and student satisfaction.

---

## 🗺️ Fellowship Roadmap

| Phase | Duration | Focus Area | Key Technologies |
| :--- | :--- | :--- | :--- |
| **Phase I** | Weeks 1-4 | Foundations & EDA | Python, Numpy, Pandas, Matplotlib, Seaborn |
| **Phase II** | Weeks 5-8 | Classical Machine Learning | Scikit-Learn, XGBoost, Clustering, Dimensionality Reduction |
| **Phase III** | Weeks 9-12 | Deep Learning & Deployment | TensorFlow/Keras, NLP, Flask/FastAPI, Docker |

---

## 🛠️ Technical Skills

*   **Programming & Scripting:** Python, SQL, Bash.
*   **Data Manipulation:** Pandas, NumPy.
*   **Machine Learning:** Scikit-Learn, XGBoost, Model Evaluation, Hyperparameter Tuning.
*   **Deep Learning:** Neural Networks, LSTM, Transfer Learning (TensorFlow/Keras).
*   **Deployment & Ops:** Flask, FastAPI, Streamlit, Git/GitHub.
*   **Visualization:** Matplotlib, Seaborn, Plotly.

---

<div align="center">
  <sub>© 2025 Syed Darain Hyder Kazmi. Maintained as part of the Buildables Data Science Fellowship.</sub>
</div>
