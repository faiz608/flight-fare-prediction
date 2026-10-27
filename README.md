# ✈️ Flight Fare Prediction Using Machine Learning

A Python-based data analysis and machine learning project that explores flight fares and develops regression models to predict ticket prices.

## 📌 Project Overview

This project analyzes flight fare data to understand how factors such as airline, journey date, route, number of stops, and flight duration relate to ticket prices.

The notebook follows a machine learning workflow that includes exploratory data analysis, data cleaning, feature engineering, model selection, hyperparameter tuning, and model evaluation.

## 🎯 Project Objectives

* Explore and analyze flight fare data.
* Identify missing values and investigate data quality.
* Understand relationships between flight characteristics and ticket prices.
* Perform feature engineering using journey dates and flight information.
* Analyze fare differences across airlines, routes, and stops.
* Train and compare machine learning regression models.
* Tune model hyperparameters using GridSearchCV.
* Evaluate predictions using RMSE, MAE, and R².

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Category Encoders
* Jupyter Notebook

## 📊 Exploratory Data Analysis

The notebook explores flight fares using statistical summaries and visualizations.

The analysis includes:

* Flight price distributions
* Airline-wise price comparisons
* Flight counts by airline
* Price comparisons by number of stops
* Flight duration versus ticket price
* Journey month and day analysis
* Route-wise fare comparisons
* Missing value and outlier analysis
* Correlation analysis

## 🧹 Data Preprocessing and Feature Engineering

The project investigates missing values, duplicate-looking records, and outliers.

It also derives additional features from journey dates, including:

* Journey year
* Journey month
* Journey day
* Day of the week
* Weekend indicator

These features help represent time-related patterns in flight fares.

## 🤖 Machine Learning

The notebook explores regression modelling using Scikit-learn and XGBoost.

The model selection workflow includes:

* Random Forest Regressor
* XGBoost Regressor
* AdaBoost Regressor as an imported candidate
* GridSearchCV for hyperparameter tuning

The notebook evaluates the selected model using a train-test split.

## 📈 Model Evaluation

The project uses the following metrics:

* **RMSE:** Measures the magnitude of prediction errors, penalizing larger errors more heavily.
* **MAE:** Measures the average absolute difference between actual and predicted fares.
* **R² Score:** Measures how much variation in the target variable is explained by the model.

Add the final measured results here after running the notebook successfully.

## 📁 Project Structure

```text
flight-fare-prediction/
├── flight_fairs.ipynb
├── Flight_Fare.xlsx
├── README.md
└── requirements.txt
```

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/faiz608/flight-fare-prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd flight-fare-prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Prepare the Dataset

Place `Flight_Fare.xlsx` in the same directory as the notebook.

The notebook loads the dataset using:

```python
df = pd.read_excel("Flight_Fare.xlsx")
```

### 6. Run Jupyter Notebook

```bash
jupyter notebook
```

Open `flight_fairs.ipynb` and execute the cells in order.

## 🔮 Future Improvements

* Compare additional regression algorithms.
* Improve preprocessing and categorical feature encoding.
* Evaluate models using cross-validation.
* Investigate prediction errors and influential features.
* Save the final trained model for reuse.
* Build an interactive flight fare prediction application.

## 👨‍💻 Author

**Faiz Ali**

GitHub: [@faiz608](https://github.com/faiz608)

Repository: [Flight Fare Prediction](https://github.com/faiz608/flight-fare-prediction)
