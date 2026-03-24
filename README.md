# 🧠 Health Risk Assessment & Age Prediction using NHANES Data

## 📌 Project Overview

This project focuses on **predictive analysis of human age and health risks** using metabolic biomarkers from the **NHANES (National Health and Nutrition Examination Survey) 2013–2014 dataset**.

The goal is to leverage **machine learning and data analysis** to uncover relationships between physiological indicators (BMI, glucose, HbA1c, insulin) and aging, enabling insights for **preventive healthcare and public health planning**.

---

## 🎯 Objectives

* Perform **Exploratory Data Analysis (EDA)** on health dataset
* Analyze relationships between **biomarkers and age**
* Build predictive models for **age estimation**
* Compare model performance using evaluation metrics
* Generate insights for **health risk assessment**

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **ML Models:**

  * Linear Regression
  * Random Forest Regressor
* **Dataset:** NHANES 2013–2014 (CDC)

---

## 📂 Dataset Description

The NHANES dataset contains health, nutrition, and clinical data collected by the **CDC**.

### Key Features Used:

| Feature  | Description             |
| -------- | ----------------------- |
| RIDAGEYR | Age (Target Variable)   |
| RIAGENDR | Gender                  |
| BMXBMI   | Body Mass Index         |
| LBXGLU   | Blood Glucose           |
| LBXGLT   | HbA1c (Glycohemoglobin) |
| LBXIN    | Insulin Level           |
| PAQ605   | Physical Activity       |

* 📊 Total records used: **2,278 (after cleaning)**

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handled missing values
* Removed outliers
* Encoded categorical variables
* Train-test split (80/20)
* Feature scaling (for Linear Regression)

### 2. Exploratory Data Analysis

* Distribution plots (Age, BMI)
* Scatter plots (BMI vs Age, Glucose vs Age)
* Correlation matrix

### 3. Model Building

* Linear Regression (baseline model)
* Random Forest Regressor (non-linear model)

### 4. Evaluation Metrics

* Mean Squared Error (MSE)
* R² Score

---

## 📊 Results

| Model             | MSE    | R² Score |
| ----------------- | ------ | -------- |
| Linear Regression | 344.13 | 0.175    |
| Random Forest     | 281.46 | 0.325    |

### 🔑 Key Finding:

* Random Forest significantly outperformed Linear Regression
* Indicates **non-linear relationships in biological data**

---

## 📈 Key Insights

### 🧬 Biomarker Relationships

* Strong correlation: **Glucose ↔ HbA1c (0.69)**
* BMI strongly linked with **insulin resistance (0.55)**
* HbA1c increases with age → indicator of metabolic aging

### 📊 Population Trends

* Average age: **41.79 years**
* Average BMI: **27.95 (overweight range)**
* Glucose levels increase with age → higher diabetes risk

---

## 💡 Applications

* Early detection of **chronic diseases**
* Public health **policy planning**
* Personalized healthcare recommendations
* Automated **risk prediction systems**

---

## 🚀 Future Scope

* Use advanced models (XGBoost, Neural Networks)
* Add more biomarkers (cholesterol, BP, lifestyle data)
* Integrate **real-time health monitoring (IoT/wearables)**
* Build **interactive dashboards or web apps**

---

## 📸 Project Visualizations

*(Add screenshots here: EDA graphs, model outputs, etc.)*

---

## 👨‍💻 Author

**Mohammad Sajid**

* 🎓 B.Tech CSE (Data Science)
* 💡 Aspiring Data Science & Data Engineering Engineer

🔗 LinkedIn: https://www.linkedin.com/in/sajid123

---

## 📌 How to Run

```bash
# Clone the repository
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run the notebook/script
jupyter notebook
```

---

## ⭐ Project Highlights

* Real-world **healthcare dataset (NHANES)**
* Applied **EDA + Machine Learning pipeline**
* Demonstrates **data-driven healthcare insights**
* Focus on **predictive analytics & model comparison**

---

## 📜 License

This project is for educational and research purposes only.
