# 📱 Mobile Price Predictor

A machine learning project that predicts mobile phone prices using a **Linear Regression** model. It includes **Exploratory Data Analysis (EDA)**, **data preprocessing**, **model training**, and a **Tkinter-based GUI** for interactive predictions.

---

## 📚 Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 🚀 Project Overview

This project utilizes a linear regression model to estimate mobile phone prices based on various features. The process includes:

- 📊 **EDA**: Visual insights into relationships between features and price  
- 🧹 **Preprocessing**: Cleaning and preparing the data  
- 🧠 **Model Training**: Building and evaluating a linear regression model  
- 🖥️ **GUI**: A user-friendly Tkinter interface for inputting features and predicting prices  
- 📈 **Visualizations**: Actual vs. predicted price plots and feature importance charts  

---

## 📂 Dataset

The dataset is sourced from Kaggle: **Mobile Price Prediction**. It contains:

- **161 rows**  
- **14 columns** (with `Price` as the target variable)

> 📌 **Note**: The dataset (`Cellphone.csv`) is **not** included due to licensing constraints. Please download it from [Kaggle](https://www.kaggle.com/) and place it in the project directory.

---

## 🔍 Features

The model uses the following 13 features for prediction:

- `Product_id`: Unique identifier  
- `Sale`: Number of units sold  
- `Weight`: Weight in grams  
- `Resolution`: Screen resolution in inches  
- `PPI`: Pixels per inch  
- `CPU Core`: Number of CPU cores  
- `CPU Freq`: CPU frequency (GHz)  
- `Internal Mem`: Internal memory (GB)  
- `RAM`: RAM (GB)  
- `RearCam`: Rear camera resolution (MP)  
- `Front_Cam`: Front camera resolution (MP)  
- `Battery`: Battery capacity (mAh)  
- `Thickness`: Thickness in mm  

---
