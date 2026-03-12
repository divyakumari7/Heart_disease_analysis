# ❤️ Heart Disease Data Analysis Dashboard

## 📌 Project Overview

Heart disease is one of the leading causes of mortality worldwide. Understanding the factors that contribute to cardiovascular diseases is essential for prevention and early detection.

This project analyzes heart disease data using **Tableau visualizations and dashboards** to identify patterns and risk factors such as lifestyle habits, health conditions, and demographic characteristics.

The dashboards are integrated into a **Flask web application**, allowing users to interact with the visualizations directly through a browser.

---

## 🎯 Objectives

* Analyze heart disease data using visualization techniques
* Identify key risk factors such as smoking, BMI, diabetes, and age
* Create interactive dashboards using Tableau
* Present insights through Tableau Stories
* Integrate dashboards into a web application using Flask

---

## 📊 Dataset Description

The dataset includes several attributes related to lifestyle, health conditions, and demographic information:

| Column           | Description                                  |
| ---------------- | -------------------------------------------- |
| HeartDisease     | Indicates whether a person has heart disease |
| BMI              | Body Mass Index                              |
| Smoking          | Indicates whether the person smokes          |
| AlcoholDrinking  | Alcohol consumption habits                   |
| Stroke           | History of stroke                            |
| PhysicalHealth   | Number of days with poor physical health     |
| MentalHealth     | Number of days with poor mental health       |
| DiffWalking      | Difficulty in walking or climbing stairs     |
| Sex              | Gender                                       |
| AgeCategory      | Age group of the individual                  |
| Race             | Ethnicity category                           |
| Diabetic         | Indicates diabetes condition                 |
| PhysicalActivity | Physical activity in last 30 days            |
| GenHealth        | General health status                        |
| SleepTime        | Average hours of sleep                       |
| Asthma           | Asthma condition                             |
| KidneyDisease    | Kidney disease status                        |
| SkinCancer       | Skin cancer condition                        |

---

## 📈 Data Visualization

The following visualizations were created in Tableau:

* Heart Disease Distribution
* Age Category vs Heart Disease
* Smoking vs Heart Disease
* Diabetes vs Heart Disease
* BMI Distribution
* Physical Activity Analysis
* Sleep Time Analysis
* Gender vs Heart Disease

These charts were combined into an **interactive Tableau Dashboard** for better analysis.

---

## 📊 Dashboard & Story

### Dashboard

The dashboard provides an overview of heart disease risk factors and allows users to explore relationships between health conditions and lifestyle habits.

### Story

The Tableau Story presents insights step-by-step and highlights major findings from the analysis.

---

## 🌐 Web Integration

The Tableau dashboards and stories are embedded into a **Flask web application** so users can interact with them in a browser.

---

## 🛠️ Technologies Used

* Python
* Flask
* Tableau
* HTML
* CSS
* JavaScript

---

## 📂 Project Structure

```
heart-disease-analysis
│
├── app.py
│
├── templates
│     ├── index.html
│     ├── about.html
│     ├── dashboard.html
│     ├── story.html
│     └── contact.html
│
├── static
│     └── style.css
│
└── dataset
      └── heart_disease.csv
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/heart-disease-analysis.git
```

### 2️⃣ Navigate to Project Folder

```
cd heart-disease-analysis
```

### 3️⃣ Install Dependencies

```
pip install flask
```

### 4️⃣ Run the Flask Application

```
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🔍 Key Insights

* Older age groups show higher heart disease prevalence.
* Smoking significantly increases cardiovascular risk.
* Diabetes is strongly associated with heart disease.
* Higher BMI levels may contribute to increased risk.

---

## 🚀 Future Improvements

* Integrate machine learning models for heart disease prediction
* Add real-time health data analytics
* Improve dashboard interactivity

---

## 👨‍💻 Team Member

**Divya Kumari**
**Divankar Singh**
**Ayush Vishwakarma**
**Arpit Srivastav**


B.Tech CSE
KIET Group of Institutions, Ghaziabad

---

## 📜 License

This project is developed for academic purposes.
