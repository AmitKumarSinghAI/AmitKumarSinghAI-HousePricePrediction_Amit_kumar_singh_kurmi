# Assignment 1: House Price Prediction Using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques. The dataset contains information about different houses, including area, number of bedrooms, bathrooms, parking spaces, air conditioning, and other features.

The main goal of this project is to analyze the housing dataset, identify the factors that affect house prices, and build models that can predict house prices accurately.

---

## 📂 Project Structure

```text
HousePricePrediction_Amit_kumar_singh_kurmi/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── area_vs_price.png
    |__ scatter_plot.png 
```

---

## 📊 Dataset Information

**Dataset:** Housing.csv

The dataset contains:

* 545 house records
* 13 features
* Target variable: Price

### Features

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status
* Price

---

## 🛠 Tasks Completed

### Task 1: Data Loading and Inspection

* Loaded the Housing dataset.
* Checked dataset shape and data types.
* Verified missing values and duplicates.
* Cleaned and prepared the data.

### Task 2: Data Preprocessing

* Converted categorical variables into numerical format.
* Applied One-Hot Encoding.
* Prepared the dataset for machine learning models.

### Task 3: Exploratory Data Analysis (EDA)

Analyzed relationships between house features and prices using visualizations.

#### Price Distribution

Shows how house prices are distributed.

```text
charts/price_distribution.png
```

#### Correlation Heatmap

Shows relationships between features and house prices.

```text
charts/correlation_heatmap.png
```

#### Area vs Price

Shows the relationship between house size and house price.

```text
charts/area_vs_price.png
```

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

### Linear Regression

A simple regression model used to predict house prices.

### Random Forest Regressor

An ensemble learning model based on multiple decision trees.

---

## 📈 Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

| Model                   | Performance       |
| ----------------------- | ----------------- |
| Linear Regression       | Best Performance  |
| Random Forest Regressor | Lower Performance |

Linear Regression achieved the highest accuracy and was selected as the final model.

---

## 🔍 Key Findings

* House area has a strong impact on price.
* More bathrooms generally increase house value.
* Air conditioning positively affects house prices.
* Parking availability contributes to higher prices.
* Houses with more stories tend to be more expensive.

---

## 📄 Summary Report

A one-page project summary is included in:

```text
summary.pdf
```

---

## 🚀 How to Run the Project

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
analysis.ipynb
```

Run all cells to reproduce the analysis and results.

---

## 📚 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 👨‍💻 Author

*** Amit Kumar Singh Kurmi ***

---

## 📜 License

This project is created for educational and learning purposes.
