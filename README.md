# 🚀 Internship Assignments – Global Tech AI Internship 2025

This repository contains two AI/ML assignments completed during the **MentorBabaa Global Tech AI Internship 2025**:

1. 🩺 **Health Risk Prediction (Mini Version)**  
2. 🤖 **Smart Resume Screener**  

---

## 🩺 Assignment 1: Health Risk Prediction (Mini Version)

### 🔹 Problem
Predict **BMI** from lifestyle factors (Sleep Hours, Daily Steps, Calories Intake) and provide **health tips**.

### 🔹 Approach
- Dataset: 15 samples (Sleep, Steps, Calories, BMI)  
- Standardized features using `StandardScaler`  
- Built **Linear Regression Model in PyTorch**  
- Evaluated with **MSE** and **R² Score**  
- User can input lifestyle data → Predict BMI + Health Tip  

### 🔹 Results
- **Final Loss (MSE):** 0.2430  
- **R² Score:** 0.9397 (~94% accuracy)  
- **Prediction Example:**  
  - Input → Sleep=7, Steps=7000, Calories=2200  
  - Predicted BMI → 23.16  
  - Health Tip → *Normal: Maintain your healthy lifestyle!*  

### 🔹 Tech Stack
`Python`, `Pandas`, `NumPy`, `Scikit-learn`, `PyTorch`, `Matplotlib`, `Seaborn`

---

## 🤖 Assignment 2: Smart Resume Screener

### 🔹 Problem
Automatically check if a **resume matches a job description**.

### 🔹 Approach
- Dataset: 25 JD–Resume pairs (13 Match / 12 No Match)  
- Text preprocessing with **TF-IDF Vectorizer**  
- Trained **Logistic Regression classifier**  
- Evaluated with Accuracy, Precision, Recall, F1-Score  
- Identified **important features** influencing match  

### 🔹 Results
- **Accuracy:** 87.5%  
- **Precision:** 1.00  
- **Recall:** 0.75  
- **F1-Score:** 0.8571  

**Sample Predictions:**  
- React JD vs React Resume → ✅ Match  
- Data Scientist JD vs Chef Resume → ❌ Incorrect (Predicted Match)  
- Backend JD vs Backend Resume → ✅ Match  

### 🔹 Important Features
- Positive → *engineer, aws, software, cloud, developer*  
- Negative → *hr, wordpress, php, mysql*  

### 🔹 Tech Stack
`Python`, `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `Streamlit` (optional)

---

## ⚡ How to Run
```bash
# Clone repo
git clone <repo-link>

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
