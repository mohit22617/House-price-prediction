# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices based on various property features such as bedrooms, living area, location, and house characteristics using Machine Learning techniques.

The goal of this project is to build an end-to-end regression model that can estimate housing prices accurately and demonstrate real-world data preprocessing, visualization, and model evaluation skills.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle categorical and numerical features
* Apply feature engineering techniques
* Train a Machine Learning regression model
* Evaluate model performance using standard metrics

---

## 📊 Dataset Description

The dataset contains housing information with multiple features affecting property prices.

### Key Features

* **price** → Target variable (house price)
* **bedrooms** → Number of bedrooms
* **bathrooms** → Number of bathrooms
* **sqft_living** → Living area size
* **sqft_lot** → Lot size
* **floors** → Number of floors
* **waterfront** → Waterfront availability
* **view** → Quality of view
* **condition** → House condition
* **sqft_basement** → Basement area
* **year built / date** → Construction information
* **city** → Property location

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed unnecessary columns (street, country, statezip)
* Converted date column into useful features (year, month)
* Applied One Hot Encoding on categorical variables
* Handled data types and cleaned dataset

### 2️⃣ Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Feature relationship visualization
* Data distribution analysis

### 3️⃣ Model Training

Algorithm used:

* **Linear Regression**

Dataset split:

* Training set: 80%
* Testing set: 20%

---

## 📈 Model Performance

| Metric                    | Value   |
| ------------------------- | ------- |
| Mean Absolute Error (MAE) | 129,988 |
| R² Score                  | 0.67    |

**Interpretation:**

* The model explains approximately **67% of the variance** in house prices.
* Average prediction error is around **130k**, which is acceptable for a baseline regression model.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📂 Project Structure

```
house-price-prediction/
│
├── data.csv
├── house_price_prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/house-price-prediction.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open the notebook:

```
jupyter notebook
```

4. Run all cells to train and evaluate the model.

---

## 🔍 Future Improvements

* Implement Random Forest and XGBoost models
* Hyperparameter tuning
* Outlier removal
* Model deployment using Flask/Streamlit
* Web-based prediction interface

---

## 💡 Learning Outcomes

* Understanding regression problems
* Feature engineering techniques
* Data visualization for ML
* Model evaluation and interpretation
* End-to-end ML workflow

---

## 👨‍💻 Author

**Mohit**
Machine Learning Engineer

---

]
