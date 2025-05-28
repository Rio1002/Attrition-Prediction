# 🎯 Attrition Prediction using Machine Learning

![Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=for-the-badge\&logo=python\&color=blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-DD0031?style=for-the-badge\&logo=streamlit\&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%E2%9C%94-green?style=for-the-badge)

---

## 📌 Project Overview

Predict employee attrition (i.e., who is likely to leave the company) using supervised machine learning techniques.
This project is built with:

* 🔍 **Data analysis & visualization**
* 🤖 **Logistic Regression model**
* 🌐 **Interactive Streamlit Web App**

---

## 📊 Dataset Details

The dataset used is `WA_Fn-UseC_-HR-Employee-Attrition.csv`, containing information such as:

| 📁 Feature                                                      | 💡 Description                      |
| --------------------------------------------------------------- | ----------------------------------- |
| `Age`                                                           | Employee age                        |
| `BusinessTravel`                                                | Travel frequency                    |
| `DistanceFromHome`                                              | Commute distance                    |
| `JobRole`, `JobLevel`                                           | Position and seniority              |
| `OverTime`                                                      | Whether the employee works overtime |
| `MonthlyIncome`, `PercentSalaryHike`                            | Salary details                      |
| `YearsAtCompany`, `TotalWorkingYears`                           | Experience metrics                  |
| `WorkLifeBalance`, `JobSatisfaction`, `EnvironmentSatisfaction` | Satisfaction scores                 |

And many more!

---

## 🗂️ Repository Structure

```
📁 Attrition-Prediction/
├── app.py                # 🚀 Streamlit Web App
├── Logistic_Regression.ipynb  # 📓 ML notebook
├── attrition_model.joblib     # 💾 Trained model
├── utils.py             # 🔧 Helper functions
├── requirements.txt     # 📦 Dependencies
└── dataset.csv          # 📊 Dataset
```

---

## 🚀 How to Run the Project

### 🧰 Step 1: Clone the Repo

```bash
git clone https://github.com/Rio1002/Attrition-Prediction.git
cd Attrition-Prediction
```

### 🧪 Step 2: Install Requirements

```bash
pip install -r requirements.txt
```

### 🌐 Step 3: Launch the Web App

```bash
streamlit run app.py
```

---

## 🌍 Live Demo

👉 Check out the working web app here:
**🔗 [Attrition Prediction App](https://rio1002-attrition-prediction-app-6j3crv.streamlit.app)**

