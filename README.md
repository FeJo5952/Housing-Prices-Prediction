# 🏠 Housing Prices Prediction – Kaggle Competition

This project is a solution to the [Housing Prices Competition](https://www.kaggle.com/competitions/home-data-for-ml-course) competition on Kaggle. The objective is to predict house sale prices using a selection of numerical features and a basic regression model.

---

## 📌 Project Summary

- **Goal:** Predict the final sale price of houses based on various numerical features.
- **Model Used:** Random Forest Regressor
- **Features Selected:**
  - `LotArea`, `YearBuilt`, `1stFlrSF`, `2ndFlrSF`, `FullBath`, `BedroomAbvGr`, `TotRmsAbvGrd`
- **Libraries:** `pandas`, `sklearn`

---

## 📁 Repository Contents

```
📦 housing-price-prediction/
├── data/
│ ├── train.csv ← Training dataset
│ └── test.csv ← Test dataset
├── housing-price-ml-competition.ipynb ← Main notebook
├── submission.csv ← Prediction output for Kaggle
├── requirements.txt ← Project dependencies
└── README.md ← This file
```

---

## 🛠 How to Run the Project (Using VS Code)

### 1. Download the Repository

- Click the green **"Code"** button and choose **Download ZIP**
- Extract the ZIP file to your computer

### 2. Install VS Code

Download and install Visual Studio Code from [https://code.visualstudio.com](https://code.visualstudio.com)

### 3. Open the Project

- Open VS Code → **File → Open Folder**
- Select the extracted project folder

### 4. Set Up Python and Jupyter

- Install the **Python** and **Jupyter Notebook** extension
- This also installs **Jupyter Notebook support**
- If you don’t have Python installed, VS Code will help you install it

### 5. Open and Run the Notebook

- Open `housing-price-ml-competition.ipynb`
- Click **Run All** or run each cell one-by-one

### 6. Required Libraries

This project only uses basic libraries. If needed, install them with:
```bash
pip install -r requirements.txt
```

---

## 📄 Output

- The model makes predictions on the test dataset
- Results are saved in `submission.csv` in the format required for Kaggle submission

---
## 🌲 Why Random Forest Regressor?

**Random Forest Regressor** is an ensemble machine learning algorithm that combines the predictions of multiple decision trees to produce more accurate and stable results.

It works by:
- Building many decision trees on random subsets of the data
- Averaging their predictions to reduce overfitting and improve generalization

**Why I used it for this project:**
- Handles both linear and non-linear relationships well
- Robust to outliers and missing data
- Requires minimal preprocessing and tuning
- Performs reliably for beginner-level regression tasks

Overall, Random Forest is a strong baseline model for predicting housing prices, especially when working with a mix of numerical features.

## 🔖 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

Feel free to fork, learn, and improve this solution!
