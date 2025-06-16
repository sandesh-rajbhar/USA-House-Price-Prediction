# 🏠 USA House Price Prediction

This project demonstrates a **supervised machine learning regression model** to predict **house prices** in the USA based on various features like number of rooms, population, and location. The analysis includes data exploration, feature engineering, model training, evaluation, and predictions.

---

## 📊 Dataset Description

The dataset contains 5000+ records with the following features:

| Feature | Description |
|--------|-------------|
| `Avg. Area Income` | Average income of residents in the area |
| `Avg. Area House Age` | Average age of houses in the area |
| `Avg. Area Number of Rooms` | Average number of rooms per house |
| `Avg. Area Number of Bedrooms` | Average number of bedrooms per house |
| `Area Population` | Population of the area |
| `Price` | **Target variable** – price of the house |
| `Address` | Text feature (dropped for modeling) |

📁 Dataset source: Included as `USA_Housing.csv`

---

## 🚀 Workflow

### 1. 📌 Data Preprocessing

- Removed unnecessary columns (`Address`)
- Checked for missing values
- Feature scaling (if applicable)

### 2. 📈 Exploratory Data Analysis (EDA)

- Correlation heatmaps
- Pairplots
- Distribution plots of features and target

### 3. 🤖 Model Building

- **Linear Regression** model from `sklearn`
- Trained on 80% of the dataset
- Tested on the remaining 20%

### 4. 📉 Evaluation

- Metrics used:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 📦 Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
