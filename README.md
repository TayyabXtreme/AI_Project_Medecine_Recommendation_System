# 🏥 Medical Recommendation System

An AI-powered Flask web application that predicts possible diseases and recommends medication based on user-inputted symptoms. The system leverages machine learning to provide initial medical guidance in a user-friendly and accessible way.

---

## 📋 Table of Contents

- [Abstract](#abstract)  
- [Introduction](#introduction)  
- [Problem Background](#problem-background)  
- [System Overview](#system-overview)  
- [Technologies and Libraries Used](#technologies-and-libraries-used)  
- [Importance in the Real World](#importance-in-the-real-world)  
- [Group Members and Role Distribution](#group-members-and-role-distribution)  
- [Dataset Information](#dataset-information)  
- [Final Output](#final-output)  
- [Conclusion and Future Work](#conclusion-and-future-work)  
- [Installation & Running the Project](#installation--running-the-project)

---

## 🧠 Abstract

Medical Recommendation System is an AI-based model designed to give appropriate recommendations for workouts, diets, and medication based on symptoms provided by the users. Acting similarly to a medical practitioner, the system checks a patient's symptoms and predicts possible conditions and recommends corresponding pharmaceutical treatments. Machine learning improves predictive ability and expands access to basic healthcare.

---

## 🩺 Introduction

This project proposes a Medical Recommendation System intended to support initial health screening and offer first-level recommendations based on user-inputted symptoms. It aims to bridge the gap between patients and healthcare information, especially where immediate access to professionals is limited.

---

## 🚨 Problem Background

- Inadequate access to healthcare in remote areas
- Rising healthcare costs
- Difficulty interpreting large medical datasets
- The need for personalized and timely advice

### 🔍 2.1 Relevant Articles

| Article/Source                         | Key Focus                          | Findings                                             | Relevance                         |
|----------------------------------------|------------------------------------|------------------------------------------------------|-----------------------------------|
| AI in Medical Diagnosis (arXiv)        | Symptom-based ML                   | Decision trees work well (80–85% accuracy)           | Guide model selection             |
| AI’s Role in Health Care (Wired)       | AI health assistance               | Needs lightweight tools for fast usage               | Use of Scikit-learn               |
| AI in Medicine (Time)                  | Personalized health tips           | Effective but limited by online access               | Design a user-friendly interface  |
| Personalized Medicine (Wikipedia)      | Mapping symptoms to diseases       | Works well with simple UIs                           | Supports simple frontend           |
| AI Blood Test for Parkinson’s (Guardian)| Biomarker detection                | Predictive features can enhance models               | Suggests future improvements      |

---

## 🔄 System Overview

### 🔧 Workflow

1. User enters symptoms
2. System preprocesses and encodes symptoms
3. ML model predicts disease
4. App returns recommended treatment and advice

### 🧠 3.1 Suitability of AI

- Detects complex patterns
- Improves with more data
- Handles large and varied input data

---

## ⚙️ Technologies and Libraries Used

| Tool/Library     | Purpose                                  |
|------------------|-------------------------------------------|
| Python           | Backend logic and ML model                |
| Flask            | Web framework                             |
| Pandas           | Data manipulation                         |
| NumPy            | Numeric computation                       |
| Scikit-learn     | ML algorithms (DecisionTree, RandomForest)|
| LabelEncoder     | Preprocessing categorical features        |
| Matplotlib/Seaborn| Visualization for analysis               |

---

## 🌍 Importance in the Real World

- Remote diagnosis for underprivileged areas
- Reduces doctor workload for minor cases
- Helps users self-educate about health
- Chatbots and AI assistants in medicine
- Cost-effective pre-screening

---

## 👥 Group Members and Role Distribution

| Member                  | Role                                   |
|-------------------------|----------------------------------------|
| Tauha Amir              | Data Scientist - Preprocessing, Feature Encoding |
| Muhammad Tayyab Extreme| ML Engineer - Model training, validation |
| Assadullah Bhatti       | Backend Developer - Flask integration |
| Abrar Hussain           | Analyst & Documentation, UI Reports   |

---

## 📁 Dataset Information

- **Features**: Binary symptoms (0/1)
- **Label**: Disease name
- **Preprocessing**: Label Encoding for categorical features
- **Split**: 80% train / 20% test
- **Evaluation**: Accuracy Score
- **Medicine Map**: CSV file links diseases to treatments

---

## 🖥️ Final Output

### 💻 Functional Web App

- Search bar for symptoms
- Clickable symptoms grid
- "Predict" button
- Disease and medicine output shown on screen

### 🌐 UI Preview (based on the screenshot)

- **Input Bar**: `e.g., itching, sleeping, aching`
- **Symptom Tags**: Clickable blue-colored symptom tags
- **Scrollable Grid**: 5-column layout of symptoms
- **Predict Button**: Big red button to trigger ML model
- **Results Panel**: Displays disease and medicine

---

## ✅ Conclusion and Future Work

**Conclusion**: The system improves medical accessibility using AI and gives basic guidance through a friendly web interface. It empowers users with early predictions and helps reduce unnecessary hospital visits.

**Future Enhancements**:

- Add user login & medical history storage
- Include severity detection
- Implement voice symptom input
- Add doctor mode for advanced suggestions
- Add a recommendation tracker for analytics

---

## 🚀 Installation & Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/TayyabXtreme/AI_Project_Medecine_Recommendation_System.git
cd AI_Project_Medecine_Recommendation_System
```


### 2. Install Requirements

```bash

pip install flask numpy pandas
```

### 3. Run the Flask App


```bash

python main.py
```

