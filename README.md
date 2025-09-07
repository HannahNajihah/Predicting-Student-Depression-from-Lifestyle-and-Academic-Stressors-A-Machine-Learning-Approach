# Predicting Student Depression Using Machine Learning on Lifestyle and Academic Stress Factors

This project explores the application of **machine learning** techniques to predict depression among students based on **lifestyle, academic, and socio-demographic factors**.  
The goal is to analyze mental health data, identify risk factors, and build predictive models that can support early intervention and awareness.

---

## Problem Statement
Depression among students is a growing concern globally. By leveraging data-driven insights, institutions and healthcare professionals can better understand the **impact of academic pressure, sleep, financial stress, and family history** on students' mental health.  

This project applies **data preprocessing, exploratory analysis, and multiple classification models** to predict whether a student is depressed (Yes/No).

---

## Project Workflow

### 1. Data Collection
- Dataset: [Student Depression Dataset](https://www.kaggle.com/datasets/hopesb/student-depression-dataset)  
- Filtered for **students only** to ensure focused analysis.

### 2. Modeling & Evaluation
Implemented multiple classification models:
- **Logistic Regression** – Best performing model (≈80% accuracy, recall = 0.86).  
- **Support Vector Machine (SVM)** – Balanced performance, ≈79.9% accuracy.  
- **Random Forest** – Moderate performance, accuracy ≈77.6%.  
- **K-Nearest Neighbors (KNN)** – Accuracy ≈76.3%.  
- **Decision Tree** – Lowest accuracy, ≈69.8%.  

---

## Key Findings
- **Logistic Regression** was the most effective model, correctly identifying **86% of depressed students**.  
- Nearly **61% of students were predicted as depressed**, showing the need for targeted interventions.  
- Lifestyle factors such as **sleep duration** and **financial stress** were strong predictors of mental health.

---

## Run Notebook in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GGwp-NOBpItVzghutPfgASVNCHmHJ-nS#scrollTo=-xzmpX_dk68u)