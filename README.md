# 🩺 Breast Cancer Classification — MLOps Project

An end-to-end **Machine Learning Operations (MLOps)** project for breast cancer classification using machine learning. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and experiment tracking using **MLflow**.

---

## 📌 Project Overview

Breast cancer is one of the most common types of cancer worldwide. Machine learning can assist in analyzing clinical and demographic data to identify patterns associated with patient outcomes.

This project applies machine learning techniques to a breast cancer dataset and builds a reproducible ML workflow following MLOps principles.

The project focuses on:

- 📊 Data preprocessing and analysis
- 🔍 Exploratory Data Analysis (EDA)
- 🧹 Data cleaning
- 🤖 Machine learning model development
- 📈 Model evaluation
- 🧪 Experiment tracking using MLflow
- 🔄 Reproducible ML workflow
- 📦 Dependency management
- 🐙 Git and GitHub version control

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze the breast cancer dataset.
2. Perform data preprocessing and feature preparation.
3. Explore relationships between patient characteristics and outcomes.
4. Train machine learning classification models.
5. Evaluate models using appropriate performance metrics.
6. Track experiments and model performance using MLflow.
7. Maintain the project using Git and GitHub.
8. Build a reproducible MLOps-oriented machine learning workflow.

---

## 📂 Dataset

The project uses the `Breast_Cancer.csv` dataset.

### Dataset Information

| Property | Value |
|---|---:|
| Number of records | 4,024 |
| Number of columns | 16 |
| Problem type | Classification |
| Target variable | `Status` |

### Features

The dataset contains demographic, clinical, tumor, and treatment-related information.

| Feature | Description |
|---|---|
| `Age` | Patient age |
| `Race` | Patient race |
| `Marital Status` | Patient marital status |
| `T Stage` | Tumor stage |
| `N Stage` | Node stage |
| `6th Stage` | Sixth edition cancer stage |
| `differentiate` | Tumor differentiation level |
| `Grade` | Tumor grade |
| `A Stage` | American Joint Committee stage |
| `Tumor Size` | Tumor size |
| `Estrogen Status` | Estrogen receptor status |
| `Progesterone Status` | Progesterone receptor status |
| `Regional Node Examined` | Number of regional lymph nodes examined |
| `Reginol Node Positive` | Number of positive regional lymph nodes |
| `Survival Months` | Patient survival period in months |
| `Status` | Patient outcome / target variable |

> **Note:** This project is intended for educational and research purposes. It is not a medical diagnostic system and should not be used for clinical decision-making.

---

## 🏗️ Project Architecture

```text
                    ┌─────────────────────┐
                    │   Breast Cancer     │
                    │      Dataset        │
                    │ Breast_Cancer.csv   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Preprocessing  │
                    │ & Feature Engineering│
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Exploratory Data  │
                    │      Analysis       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Model Training      │
                    │                     │
                    │ ML Classification   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Model Evaluation    │
                    │                     │
                    │ Accuracy            │
                    │ Precision           │
                    │ Recall              │
                    │ F1 Score            │
                    │ ROC-AUC             │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MLflow         │
                    │ Experiment Tracking │
                    └─────────────────────┘
