# NYC-Yellow-Taxi-Fare-Prediction

# 🚕 NYC Yellow Taxi Fare Prediction

This project focuses on analyzing the **NYC Yellow Taxi Trip dataset** and building a **Machine Learning regression model** to predict the **total taxi fare amount** based on trip-related features such as distance, duration, and fare components.

The project demonstrates end-to-end **data analysis, feature selection, model training, and deployment** using **Python and Gradio**.

---

## 📌 Problem Statement

Taxi fare estimation is important for both passengers and service providers. Incorrect fare prediction can lead to customer dissatisfaction and revenue loss.

**Objective:**  
Build a machine learning model that accurately predicts the **total fare amount** for NYC Yellow Taxi trips using historical trip data.

---

## 📊 Dataset

- **Source:** NYC Yellow Taxi Trip Records (Kaggle)
- **Dataset Size:** 12,000+ rows
- **Target Variable:** `total_amount`
- **Selected Features:**
  - `trip_distance`
  - `trip_duration_min`
  - `fare_amount`
  - `mta_tax`
  - `tolls_amount`

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Deployment:** Gradio  

---

## 🔍 Project Workflow

1. **Data Understanding**
   - Loaded NYC Yellow Taxi dataset
   - Analyzed data structure and feature types

2. **Data Preprocessing**
   - Handled missing values
   - Removed outliers
   - Selected important features using correlation analysis

3. **Exploratory Data Analysis (EDA)**
   - Distribution plots for fare and distance
   - Correlation heatmap
   - Scatter plots to study relationships

4. **Model Building**
   - Applied regression models
   - Split data into training and testing sets
   - Evaluated performance using R² score and MAE

5. **Model Deployment**
   - Saved trained model using `pickle`
   - Built a user-friendly prediction interface using **Gradio**

---

## 📈 Model Performance

- **Model Type:** Regression Model
- **Evaluation Metrics:**
  - R² Score
  - Mean Absolute Error (MAE)


pip install pandas numpy matplotlib seaborn scikit-learn gradio

