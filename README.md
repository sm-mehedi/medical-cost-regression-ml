# 🏥 Medical Insurance Cost Predictor - ML Final Exam Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.6.1-orange)
![Gradio](https://img.shields.io/badge/Gradio-4.x-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Deployed-success)

A complete machine learning pipeline for predicting individual medical insurance costs. Built as a final exam project covering the full ML workflow from data preprocessing to deployment.

## 🌐 Live Demos

| Platform | Link | Status |
|----------|------|--------|
| **🤗 Hugging Face** | [Live Prediction App](https://huggingface.co/spaces/smmehedi71/medical-insurance-ml-exam) | ✅ **Working** |
| **🔬 Google Colab** | [Interactive Notebook](https://colab.research.google.com/drive/1cGePQSrvIJllq_FbxweFMoDoKegW5NhE#scrollTo=jBaYgXlrFiGF) | ✅ **Working** |

## 📊 Project Overview

This project implements a complete machine learning pipeline for predicting medical insurance costs based on personal characteristics. The project covers all 11 required tasks:

### ✅ Tasks Completed:
1. **Data Loading** - Load and verify dataset
2. **Data Preprocessing** - Handle missing values, feature engineering, outlier detection
3. **Pipeline Creation** - Build ML pipeline with preprocessing
4. **Model Selection** - Random Forest Regressor with justification
5. **Model Training** - Train model on training data
6. **Cross-Validation** - 5-fold CV for robustness assessment
7. **Hyperparameter Tuning** - GridSearchCV optimization
8. **Best Model Selection** - Select optimal model
9. **Performance Evaluation** - Comprehensive metrics (MAE, RMSE, R²)
10. **Gradio Interface** - User-friendly web interface
11. **Hugging Face Deployment** - Live deployment with public URL

## 🗂️ Dataset

**Medical Cost Personal Dataset** (Kaggle)
- **Rows**: 1,338 individual records
- **Features**: 7 demographic and health factors
- **Target**: `charges` (individual medical costs)

### Features:
- `age`: Age of primary beneficiary (18-64)
- `sex`: Gender (male/female)
- `bmi`: Body Mass Index (15.96-53.13)
- `children`: Number of dependents (0-5)
- `smoker`: Smoking status (yes/no)
- `region`: Residential area in US
- `charges`: Individual medical costs ($1,121 - $63,770)

## 🛠️ Tech Stack

- **Python 3.8+**
- **Machine Learning**: Scikit-learn 1.6.1, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Web Interface**: Gradio 4.x
- **Deployment**: Hugging Face Spaces
- **Model Persistence**: Joblib


