# ✈️ Airline Customer Satisfaction Prediction

This project builds a machine learning model to predict **customer satisfaction** based on airline service and flight-related features. It uses data preprocessing, exploratory analysis, feature engineering, and classification models to understand what impacts satisfaction levels.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [EDA & Data Cleaning](#eda--data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Results & Evaluation](#results--evaluation)
- [Streamlit Deployment](#streamlit-deployment)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)

---

## 📈 Project Overview

The goal of this project is to predict whether an airline customer is **satisfied** or **neutral or dissatisfied** with their flight experience using classification algorithms. Insights from this model can help airlines improve their services and personalize customer experiences.

![image](https://github.com/Gaurav-1111/Airline_Customer_Prediction_Satisfaction/blob/main/Customer_Satisfaction_Prediction%20.jpg)

---

## 📊 Dataset Description

The dataset contains various passenger feedback and flight information:

- Demographics: `Gender`, `Age`, `Type of Travel`, `Class`
- Flight details: `Flight Distance`, `Arrival Delay`, `Departure Delay`
- In-flight services: `Seat comfort`, `Cleanliness`, `Baggage handling`, etc.
- Target variable: `Satisfaction` (Satisfied / Dissatisfied)

---

## 🧹 EDA & Data Cleaning

- Removed unnecessary columns: `id`, `Unnamed: 0`
- Treated missing values in **Arrival Delay** using the median
- Identified and handled outliers in:
  - `Flight Distance`
  - `Arrival Delay in Minutes`
  - `Departure Delay in Minutes`
  - `Check-in Service`
- Checked for duplicates and correlation between numerical features

---

## 🧠 Feature Engineering

- Converted ordinal categorical ratings into meaningful text labels
- Applied encoding to convert categorical variables into numeric format
- Prepared the dataset for machine learning by selecting relevant features and transforming data types

---

## 🤖 Model Building

- Train-test split: 80:20
- Applied classification models:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Support Vector Machine
- Evaluated with metrics like:
  - Accuracy


## 📊 Results & Evaluation

- Random Forest performed best with high accuracy and balanced precision/recall.

## 🚀 Streamlit Deployment

The project is deployed using **Streamlit** to provide an interactive web interface where users can input passenger features and receive real-time satisfaction predictions.[Streamlit](https://airline-customer-prediction-satisfaction.streamlit.app/)


