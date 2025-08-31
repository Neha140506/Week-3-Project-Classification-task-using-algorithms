# Week 3 Project – Student Performance Prediction

## 📌 Overview
This project predicts **student performance outcomes** (Pass/Fail) based on various academic and personal features from the **Student Performance Dataset**.  
The notebook explores preprocessing, training models, and evaluating performance using machine learning techniques.

---

## ⚙️ Features
- Dataset preprocessing:
  - Handle categorical variables with **Label Encoding**
  - Drop irrelevant features (to avoid leakage)
- Binary target creation:
  - Pass if `G3 >= 10`, otherwise Fail
- Models:
  - **Logistic Regression**
  - **Random Forest Classifier**
- Evaluation:
  - Accuracy, Precision, Recall, F1-score
  - Feature importance analysis (Random Forest)

---

## 📂 Dataset
The project uses the **Student Performance Dataset** (`student-mat.csv`), which includes features such as:
- Demographics
- Study habits
- Family background
- Academic history  

Source: [UCI Machine Learning Repository – Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/student+performance)

---

## 🛠️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/week-3-project.git
cd week-3-project

