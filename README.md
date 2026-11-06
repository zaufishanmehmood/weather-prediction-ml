# Weather Prediction Using Machine Learning 🌤️

## 📌 Project Overview

This project uses Machine Learning regression algorithms to predict the **maximum temperature** using historical weather data.

The project explores weather data, performs data cleaning and preprocessing, trains machine learning models, and evaluates their performance.

## 🎯 Project Objectives

- Understand and explore historical weather data.
- Clean and preprocess the dataset.
- Select relevant features for prediction.
- Train Linear Regression and Random Forest Regression models.
- Evaluate model performance using regression metrics.
- Compare the results of both models.

## 📂 Dataset

The dataset contains historical weather records from **1964 to 2013**.

It includes information such as:

- Date
- Minimum temperature (`min_temp`)
- Maximum temperature (`max_temp`)
- Latitude
- Longitude
- Weather station information

**Target variable:** `max_temp`

The dataset is not included in this repository. Please download the original dataset separately and update the notebook's file path before running it.

## 🛠️ Technologies and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## ⚙️ Project Workflow

1. Load the weather dataset.
2. Explore the dataset using Pandas.
3. Check missing values and duplicate records.
4. Clean inconsistent temperature records.
5. Extract year, month, and day from the date.
6. Select input features and target variable.
7. Split the data chronologically into training and testing sets.
8. Train Linear Regression and Random Forest Regression models.
9. Evaluate and compare model performance.

## 🤖 Machine Learning Models

Two regression algorithms were used:

- **Linear Regression**
- **Random Forest Regressor**

## 📊 Model Performance

The following results were obtained:

| Evaluation Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 5.24 | 3.85 |
| MSE | 40.75 | 26.27 |
| RMSE | 6.38 | 5.13 |
| R² Score | 78.49% | 86.13% |

**Note:** Linear Regression was trained using the full training dataset, while Random Forest was trained using a sample of 100,000 training records. Therefore, this comparison is not fully equal.

## 📈 Results

The Random Forest model achieved a higher R² score in this experiment.

The results show that Random Forest captured patterns in the dataset better than Linear Regression under the training setup used.

## ⚠️ Project Limitation

This project predicts maximum temperature using the same day's minimum temperature, geographical coordinates, and date information.

It is a temperature regression project, not a next-day weather forecasting system.

## 🚀 How to Run

1. Download or clone this repository.
2. Download the original weather dataset.
3. Open `weather_prediction.ipynb` in Google Colab or Jupyter Notebook.
4. Upload the dataset or update its file path.
5. Run the notebook cells in order.

## 📁 Repository Files

- `weather_prediction.ipynb` — Complete project code, analysis, model training, and evaluation.
- `README.md` — Project documentation.

## 👩‍💻 Author

Created as a Machine Learning practice project to develop practical skills in Python, data preprocessing, regression, and model evaluation.
