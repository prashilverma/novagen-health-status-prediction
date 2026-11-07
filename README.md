# NovaGen Labs - Health Status Prediction

## Project Overview

NovaGen Labs is a Supervised Machine Learning project that classifies individuals as **Healthy or Unhealthy** based on their health indicators, lifestyle habits, and medical history.

The goal is to support health research, participant selection, and risk-based population analysis.

## Dataset

The dataset contains 9,800 individual health records with features such as:

- Age and BMI
- Blood Pressure and Cholesterol
- Glucose Level and Heart Rate
- Sleep and Exercise Hours
- Water Intake and Stress Level
- Smoking, Alcohol, and Diet
- Medical History and Allergies

**Target Variable:** `Target` (Health Status).

## Machine Learning Models

The following classification models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting
- Voting Classifier
- Stacking Classifier

**Best Model:** Random Forest Classifier

**Best Recall:** 94.6%

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Keep `novagen_dataset.csv` in the project folder.
4. Open `novagen.ipynb` in Jupyter Notebook or VS Code.
5. Run all cells.

---

This project was created as part of my Supervised Machine Learning learning journey.