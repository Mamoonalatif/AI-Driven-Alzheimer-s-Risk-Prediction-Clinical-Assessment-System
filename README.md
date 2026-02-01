# AlzRiskAI 🧠
**AI-powered Alzheimer’s Clinical Risk Assessment System**  

> Predicts Alzheimer’s disease risk in older adults using machine learning and deep learning models with interpretable clinical insights.  

## Project Overview

AlzRiskAI is an AI-driven clinical decision-support system designed to predict Alzheimer’s disease risk. Using demographic, clinical, cognitive, and lifestyle data, it provides accurate risk scores and interpretable insights for early intervention and research purposes.

## Features

- **Data Preprocessing & Cleaning:** Handles missing values, categorical encoding, and feature scaling.
- **Exploratory Data Analysis:** Correlation heatmaps, boxplots, KDE plots, and statistical summaries.
- **Feature Engineering & Selection:** Random Forest importance, correlation filtering, and key predictor selection.
- **Machine Learning Models:** Random Forest, Logistic Regression, Support Vector Machine (SVM).
- **Deep Learning Model:** Multi-Layer Perceptron (MLP) with dropout layers and Adam optimizer.
- **Model Evaluation:** ROC-AUC, precision-recall, confusion matrices, classification reports, cross-validation.
- **Interpretability:** SHAP-based feature importance for explainable AI.
- **Interactive Assessment Dashboard:** Jupyter Notebook widgets for patient input and risk evaluation.
- **Automated Report Generation:** Generates professional HTML risk reports for clinical use.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/AlzRiskAI.git
cd AlzRiskAI
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Place the dataset `alzheimers_disease_data.csv` in the project directory.

## Usage

1. Open Jupyter Notebook:

```bash
jupyter notebook
```

2. Run `AlzRiskAI.ipynb` to:

   * Load and preprocess data
   * Explore dataset visually
   * Train ML/DL models
   * Evaluate models and generate SHAP explanations
   * Use interactive widgets for patient risk assessment and HTML report generation

## Dataset

Contains older adults’ clinical, cognitive, and lifestyle data:

* Demographics: Age, Gender, Ethnicity
* Cognitive/Functional: MMSE, ADL, Functional Assessment, BMI
* Health & Lifestyle: Sleep, Hypertension, Diabetes, Family History
* Binary & categorical features for predictive modeling

## Results

* High accuracy using Random Forest and MLP models
* SHAP identifies key predictors: Memory Complaints, MMSE, BMI, Functional Assessment, Hypertension
* Interactive dashboard generates patient-specific risk scores and professional reports

## Technologies Used

* Python 3.10+
* pandas, numpy
* matplotlib, seaborn, missingno
* scikit-learn (Random Forest, Logistic Regression, SVM)
* TensorFlow / Keras (MLP)
* SHAP (interpretability)
* ipywidgets (interactive dashboard)
* Jupyter Notebook

