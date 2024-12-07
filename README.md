# 🩸 Give Life: Predict Blood Donations

This project aims to predict whether a blood donor will donate blood again based on their donation history. The analysis uses machine learning models to process and analyze the dataset provided. One of the tools used for this project is **TPOT**, an automated machine learning (AutoML) library that optimizes machine learning pipelines using genetic programming. 🌟

---

## 📝 Overview

Blood donation is a critical part of healthcare, saving lives in emergencies, surgeries, and for patients with chronic illnesses. Predicting future donations helps healthcare organizations manage blood supply effectively. 🏥

This project uses data from a mobile blood donation vehicle in Taiwan. The dataset includes features related to donation frequency, recency, and volume to predict if a donor will donate again. 🚐🩸

---

## 🤖 TPOT: Tree-based Pipeline Optimization Tool

### What is TPOT?

TPOT is an open-source AutoML tool that automates the process of designing and optimizing machine learning pipelines. It uses **genetic programming** to identify the best combination of preprocessing steps, models, and hyperparameters for your dataset. 🧬✨

### 🔑 Key Features:
1. 🛠️ **Pipeline Automation**: Automatically builds and optimizes end-to-end machine learning pipelines.
2. 🧪 **Genetic Programming**: Uses evolutionary algorithms to find the best combinations of model components.
3. 🤝 **Scikit-learn Integration**: Compatible with scikit-learn, and pipelines can be exported as Python code.
4. ⚙️ **Customizability**: Allows users to define parameters like population size, generations, and mutation rates.

### 🌟 Why Use TPOT for This Project?

- **Efficiency**: Automates tedious tasks like model selection and hyperparameter tuning.
- **Exploration**: Quickly identifies the best-performing pipelines without manual trial-and-error.
- **Interpretability**: Outputs human-readable code that can be further customized or directly deployed.

---

## 📊 Dataset

The dataset follows the **RFMTC marketing model**, which is adapted for blood donation:

- **R (Recency)**: How recently the donor gave blood.
- **F (Frequency)**: How often the donor has given blood.
- **M (Monetary)**: Volume of blood donated (c.c.).
- **T (Time)**: How long the donor has been donating.
- **C (Class)**: The target variable indicating whether the donor will donate again (1 = Yes, 0 = No).

---

## 🚀 Project Highlights

1. **🔧 Data Preprocessing**:
   - Handled high-variance features by applying normalization techniques like log normalization.
   - Split data into training and testing sets for evaluation.

2. **🤖 TPOT Integration**:
   - Used TPOT to automatically search for the best pipeline.
   - Evaluated multiple models and preprocessing steps.
   - Exported the best-performing pipeline for deployment.

3. **📈 Performance Metrics**:
   - Evaluated pipelines using metrics like **Area Under the Curve (AUC)** for classification.
   - Improved model performance through feature engineering and pipeline optimization.

---

## 🛠️ How to Run This Project

### 📦 Prerequisites
- Python 3.7+
- Required libraries: `numpy`, `pandas`, `scikit-learn`, `tpot`, and `jupyter`

### 🏃 Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/give-life-predict-blood-donations.git
