# 🏥 Medical Insurance Cost Prediction

![Python](https://img.shields.io/badge/Python-3.14.3-blue.svg?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.8.0-orange.svg?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-Data_Processing-150458.svg?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=flat&logo=jupyter&logoColor=white)

## 📌 Overview
An end-to-end Machine Learning project designed as a pedagogical introduction to supervised learning. This project follows the principles of Part 1 of the book *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*, featuring clear explanations, Exploratory Data Analysis (EDA), and Scikit-Learn pipelines.

The goal is to predict the **medical insurance charges** of individuals based on their personal attributes.

## 📊 The Dataset
We use the publicly available **Medical Cost Personal Datasets**. The dataset contains 1,338 records with the following features:
* **`age`**: Age of the primary beneficiary
* **`sex`**: Gender (male / female)
* **`bmi`**: Body Mass Index
* **`children`**: Number of children covered by health insurance
* **`smoker`**: Smoking status (yes / no) - *Provides a massive split in the data!*
* **`region`**: Residential area in the US (northeast, southeast, southwest, northwest)
* **🎯 Target**: **`charges`** (Individual medical costs billed by health insurance)

## 🤖 Models Evaluated
Through standard preprocessing (One-Hot Encoding, Standard Scaling), we train and evaluate:
1. 📈 **Linear Regression**
2. 🌳 **Decision Tree Regressor**
3. 🌲 **Random Forest Regressor** (👑 *Best Performing Model after Hyperparameter Tuning!*)

## 🚀 Getting Started

Follow these steps to run the notebook locally:

**1. Clone the repository**
```bash
git clone https://github.com/SepehrMohammady/The-Fundamentals-of-ML.git
cd The-Fundamentals-of-ML
```

**2. Set up a Virtual Environment**
```bash
python -m venv insurance_env
# On Windows:
insurance_env\Scripts\activate
# On Mac/Linux:
source insurance_env/bin/activate
```

**3. Install Dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the Notebook**
Open `insurance_project.ipynb` in VS Code or run standard Jupyter:
```bash
jupyter notebook
```

---
*Created for foundational exploration of Data Preprocessing, EDA, and Model Tuning.*
