# 🚀 Predictive Maintenance System using Machine Learning

## 📌 Overview

This project is a **Predictive Maintenance System** that uses Machine Learning to predict whether a machine will fail or not based on operational data.

The goal is to **detect failures in advance**, helping industries reduce downtime, improve safety, and optimize maintenance.

---

## 🎯 Objectives

* Predict machine failures before they occur
* Handle imbalanced data using SMOTE
* Build a reliable classification model
* Improve recall for failure detection

---

## 🧠 Machine Learning Approach

* Data Preprocessing (handling missing values, encoding)
* Handling Imbalanced Data using **SMOTE**
* Model Training using:

  * Random Forest Classifier
* Model Evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-score

---

## 📊 Model Performance

* ✅ Accuracy: **98%**
* 🔥 Recall (Failure Class): **97%**
* ⚠️ Precision (Failure Class): **61%**

> Focus was given to **high recall** to ensure failure detection is not missed.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib / Seaborn

---

## 📁 Project Structure

```
project_predictive/
│
├── predictive_machine_failure.ipynb   # Main project notebook
├── README.md                         # Project documentation
```

---

## ⚙️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/vsandeep07/predictive-maintainence-version-1-.git
```

2. Navigate to the folder:

```
cd project_predictive
```

3. Install dependencies:

```
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

4. Run the notebook:

```
jupyter notebook
```

---

## 🌍 Real-World Applications

* 🏭 Industrial machine monitoring
* 🚢 Defense and naval systems
* ✈️ Aircraft maintenance
* 🚗 Automobile diagnostics
* 🏢 Smart manufacturing (Industry 4.0)

---

## 🧠 Key Learnings

* Handling imbalanced datasets using SMOTE
* Importance of recall in critical systems
* End-to-end ML project development
* Git & GitHub workflow

---

## 📌 Future Improvements

* Improve precision using hyperparameter tuning
* Deploy using Streamlit
* Add real-time prediction system
* Integrate IoT sensor data

---

## 👨‍💻 Author
V Sandeep
