# 📱 Mobile Phone Price Range Prediction

## 📌 Project Overview

This project focuses on predicting the **price range of mobile phones** based on their hardware specifications and connectivity features using Machine Learning.

The objective is to classify a mobile phone into one of four price categories:

- **0 – Low Cost**
- **1 – Medium Cost**
- **2 – High Cost**
- **3 – Very High Cost**

This is a **Multiclass Classification** problem that helps manufacturers estimate the market price of smartphones based on their specifications.

---

## 🎯 Problem Statement

Build a machine learning model capable of predicting the price range of a mobile phone using various hardware and connectivity features.

Accurate price prediction enables manufacturers to:
- Make informed pricing decisions
- Optimize product positioning
- Improve market competitiveness

---

## 📂 Dataset

**Dataset:** `datasets_11167_15520_train.csv`

The dataset contains **2,000 mobile phone records** with **20 input features** and **1 target variable (`price_range`)**.

### Features Include

- Battery Power
- Bluetooth
- Clock Speed
- Dual SIM
- Front Camera
- 4G Support
- Internal Memory
- Mobile Depth
- Mobile Weight
- Number of Cores
- Primary Camera
- Pixel Resolution Height
- Pixel Resolution Width
- RAM
- Screen Height
- Screen Width
- Talk Time
- 3G Support
- Touch Screen
- WiFi

**Target Variable**

`price_range`

| Class | Price Category |
|-------|----------------|
| 0 | Low Cost |
| 1 | Medium Cost |
| 2 | High Cost |
| 3 | Very High Cost |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📊 Project Workflow

- Data Loading
- Data Exploration
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Model Building
- Model Evaluation
- Hyperparameter Tuning using GridSearchCV
- Model Comparison
- Final Model Selection

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

---

## ⚙️ Hyperparameter Tuning

To improve model performance, **GridSearchCV with 5-Fold Cross Validation** was applied on:

- Logistic Regression
- XGBoost

---

## 📈 Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 96.50% |
| KNN | 58.75% |
| Decision Tree | 83.00% |
| Random Forest | 88.00% |
| SVM | 90.00% |
| XGBoost | 94.00% |
| **Tuned Logistic Regression** | **98.25%** |

---

## 🏆 Final Model

**Tuned Logistic Regression**

### Test Accuracy

**98.25%**

### Cross Validation Accuracy

**96.12%**

This model achieved the highest overall performance and was selected as the final model for deployment.

---

## 📁 Repository Structure

```
Mobile-Phone-Price-Range-Prediction/
│
├── datasets_11167_15520_train.csv
├── Mobile_Phone_Price_Range_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Mobile-Phone-Price-Range-Prediction.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all notebook cells.

---

## 📌 Results

- Successfully built a multiclass classification model.
- Compared six machine learning algorithms.
- Improved performance using GridSearchCV.
- Achieved **98.25% test accuracy** using Tuned Logistic Regression.

---

## 📜 License

This project is developed for educational and portfolio purposes.
