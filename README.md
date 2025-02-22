## Predicting Hazardous NEOs (Nearest Earth Objects)

## Project Overview

This project focuses on predicting hazardous Near-Earth Objects (NEOs) using a real-world dataset from NASA (1910–2024). It involves data cleaning, exploratory data analysis (EDA), preprocessing, handling imbalanced classes, model training, evaluation, and documentation.

## Dataset

- **Source:** NASA NEO Dataset (1910-2024)
- **Contents:** Information about near-earth objects, including their size, velocity, orbit details, and whether they are hazardous.
- **File:** `nearest-earth-objects(1910-2024).csv`

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Project Workflow

### 1. Data Importing and Cleaning

- Load the dataset.
- Handle missing values and duplicates.
- Ensure data integrity and reliability.

### 2. Exploratory Data Analysis (EDA)

- Visualize class distributions.
- Identify trends and patterns using Matplotlib and Seaborn.

### 3. Data Preprocessing

- Encode categorical features.
- Scale numerical features.
- Handle imbalanced classes using **SMOTE** (Synthetic Minority Over-sampling Technique).

### 4. Model Training & Evaluation

- Train machine learning models (Random Forest).
- Evaluate models using:
  - **Precision, Recall, F1-Score**
  - **Confusion Matrix**
  - **ROC-AUC Score**

## Running the Code

Run the Python script to execute the full pipeline:

```bash
python predict_hazardous_neos.py
```

## Results

- The model predicts whether an NEO is hazardous.
- Performance metrics help assess model effectiveness.

## Repository Structure

```
📂 Predicting-Hazardous-NEOs
 ├── nearest-earth-objects(1910-2024).csv  # Dataset
 ├── predict_hazardous_neos.py             # Python script for analysis
 ├── README.md                              # Documentation
```

## Author

**Hoda Mohamed**

##
