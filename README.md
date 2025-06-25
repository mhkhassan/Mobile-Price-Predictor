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
## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mobile-price-predictor.git
```

## 2. Install Dependencies
Ensure you have Python 3.9+ installed.
```bash
pip install requirements.txt
```

## 3. Install Jupyter (if not already: optional)
```bash
pip install jupyter
```

## 4. Download Dataset
Download Cellphone.csv from Kaggle and place it in the root project directory

---
## ▶️ Usage

## 1. Launch Jupyter Notebook
```bash
jupyter notebook
```

## 2. Open and Run
- `Open mobile_price_predictor.ipnyb`
- `Run all cells to:`
 - `Perform EDA`
 - `Preprocess data`
 - `Train the model`
 - `Launch the Tkinter GUI`

## 3. Use the GUI
- `Input mobile features in the GUI`
- `Click "Predict Price"`
- `View the Predicted Price instantly`
- `Visuals (e.g., actual vs predicted) will also appear in the notebook.`

> ⚠️ **Note**: Make sure your system supports graphical output for Tkinter. It may not work on headless servers.
---

## 🤝 Contributing
Contributions are welcome!

1. **Fork** the repository

2. **Clone** your forked repo:
   ```bash
   git clone https://github.com/your-username/mobile-price-predictor.git
   cd mobile-price-predictor
   ```

3. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes** and commit them:
   ```bash
   git commit -m "Add: your description of the feature or fix"
   ```

5. **Push** the changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request** on GitHub with a clear title and description of your changes.

---
## 💡 Guidelines
- `Follow the PEP8 Python style guide.`
- `Write clear, concise commit messages.`
- `Include comments to explain complex code logic.`
- `Ensure your changes do not break existing functionality.`
- `Test your features before submitting a pull request.`
