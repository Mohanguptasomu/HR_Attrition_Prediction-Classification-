# HR Attrition Prediction (Classification) 👨‍💼📊

A Machine Learning web application built using **Streamlit** that predicts whether an employee is likely to leave the company based on various HR-related factors such as job satisfaction, monthly income, work-life balance, overtime, and more.

---

## 🚀 Project Overview

This project uses a trained **Random Forest Classification Model** to predict employee attrition risk.
The application provides an interactive and user-friendly dashboard for HR analytics and employee retention prediction.

---

## 📌 Features

* Interactive Streamlit web application
* Employee attrition prediction
* Real-time prediction probability
* Clean and responsive UI
* HR analytics based prediction system
* Machine Learning model integration
* One-hot encoded categorical feature handling

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle

---

## 📂 Project Structure

```bash id="mrq2tk"
HR_Attrition_Prediction/
│
├── app.py
├── hr_attrition_model.pkl
├── requirements.txt
├── README.md
└── myenv/
```

---

## 📊 Machine Learning Model

The project uses:

* **Random Forest Classifier**

### Input Features

* Age
* Gender
* Marital Status
* Education Level
* Education Field
* Department
* Job Role
* Monthly Income
* Business Travel
* Job Involvement
* Overtime
* Work Life Balance
* Total Working Years
* Years At Company
* Job Satisfaction
* Environment Satisfaction
* Distance From Home
* And more...

### Output

* Employee likely to leave company
* Employee likely to stay in company

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash id="vjlwm1"
git clone https://github.com/Mohanguptasomu/HR_Attrition_Prediction-Classification-.git
```

---

### 2️⃣ Navigate to Project Folder

```bash id="jlwm2"
cd HR_Attrition_Prediction-Classification-
```

---

### 3️⃣ Create Virtual Environment

```bash id="jlwm3"
python -m venv myenv
```

---

### 4️⃣ Activate Environment

#### Windows

```bash id="jlwm4"
myenv\\Scripts\\activate
```

---

## 📦 Install Required Libraries

```bash id="jlwm5"
pip install -r requirements.txt
```

OR

```bash id="jlwm6"
pip install streamlit pandas numpy scikit-learn
```

---

## ▶️ Run the Application

```bash id="jlwm7"
streamlit run app.py
```

---

## 🌐 Streamlit App

After running the command, the app will open in your browser:

```bash id="jlwm8"
http://localhost:8501
```

---

## 📈 Model Workflow

1. Data Collection
2. Data Preprocessing
3. One-Hot Encoding
4. Feature Engineering
5. Model Training
6. Random Forest Classification
7. Prediction & Probability Output
8. Streamlit Deployment

---

## 📸 Application Features

✅ Employee Risk Prediction
✅ Interactive Dashboard
✅ Real-Time Prediction
✅ HR Analytics Support
✅ User Friendly Interface

---

## 📈 Future Improvements

* Add XGBoost & Logistic Regression comparison
* Add SHAP feature importance visualization
* Deploy on Streamlit Cloud
* Add employee analytics dashboard
* Improve UI/UX design
* Add downloadable HR reports

---

## 👨‍💻 Author

**Mohan Gupta Somu**

* GitHub: [Mohanguptasomu GitHub](https://github.com/Mohanguptasomu)
* LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/mohan-gupta-s/)
* streamlit project live server [project live server](https://mohanguptasomuhrattritionpredictionclassification.streamlit.app/)

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
