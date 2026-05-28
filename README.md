# House Price Prediction using Machine Learning

## Overview

This project predicts house prices using Machine Learning algorithms.
The model is trained on housing data containing features such as area, bedrooms, bathrooms, parking, and furnishing status.

The project demonstrates:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training
* Evaluation metrics
* Price prediction

---

## Dataset

The dataset contains housing-related features such as:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Air Conditioning
* Furnishing Status
* Main Road Access
* Guest Room
* Basement
* Preferred Area

Target Variable:

* `price`

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Collection

Loaded the housing dataset using Pandas.

### 2. Data Preprocessing

* Checked missing values
* Converted categorical variables
* Feature encoding
* Data cleaning

### 3. Exploratory Data Analysis (EDA)

Performed:

* Correlation analysis
* Box plots
* Scatter plots
* Heatmaps

### 4. Model Training

Used:

* Linear Regression

### 5. Model Evaluation

Evaluation metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## Project Structure

```bash
House-Price-Prediction/
│
├── hpriceprediction.ipynb
├── Housing.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Results

The Linear Regression model predicts house prices based on housing features with good accuracy.

---

## Future Improvements

* Add Random Forest Regressor
* Add XGBoost
* Deploy using Flask/Streamlit
* Hyperparameter tuning
* Feature selection optimization

---

## Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Regression algorithms
* Model evaluation
* Data visualization
* Real-world ML workflow

---

## Author

Nikhil Dutt

Machine Learning Enthusiast | AI/ML Learner
