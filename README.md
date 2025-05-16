# 🌞Solar Power Plant Production Analysis&Prediction⚡

This project is developed to analyze the electricity production data of the **Ikıtelli Solar Energy Plant** for May 2018 and to make production predictions using machine learning models.

## 📚 Table of Contents

- [Installation](#-installation)
- [Dataset](#-dataset)
- [Methodology Overview](#-methodology-overview)
- [Libraries Used](#-libraries-used)
- [Modeling](#%EF%B8%8F-modeling)
- [Results](#-results)

## 🚀 Installation

To install the necessary libraries for the project, you can use the following commands:

!pip install lightgbm

!pip install fbprophet

!pip install pandas

!pip install numpy

!pip install matplotlib

!pip install seaborn

!pip install xgboost

!pip install scikit-learn



## 📊 Dataset

The project utilizes two primary data sources:

1. **⚡ Production Data**
   - 📅 **Time Period:** May 2018
   - ⏱️ **Interval:** 15-minute measurements
   - ⚡ **Production values:** kilowatt-hours (kWh)

2. **🌤️ Weather Data**
   - 🌡️ **Temperature:** Maximum, minimum, and real-time
   - ☁️ **Cloud Cover:** Percentage
   - 💧 **Humidity:** Levels
   - 🌪️ **Wind Speed:** km/h
   - 🌧️ **Precipitation:** mm
   - ☀️ **Sun Hours:** Hours of sunlight
  
## 🔬 Methodology Overview
1. **🧹 Data Preprocessing**
   - Cleaning and organizing raw data
   - Feature engineering
   - Time series analysis

2. **📊 Exploratory Data Analysis**
   - Correlation studies
   - Pattern identification
   - Seasonal trend analysis

3. **🤖 Model Development**
   - Multiple algorithm implementation
   - Hyperparameter tuning
   - Cross-validation

4. **📈 Performance Evaluation**
   - Model comparison
   - Error analysis
   - Prediction accuracy assessment

## 📦 Libraries Used

- **pandas**: For data analysis and manipulation.
- **numpy**: For numerical calculations.
- **matplotlib** and **seaborn**: For data visualization.
- **lightgbm**, **xgboost**: For machine learning models.
- **fbprophet**: For time series forecasting.
- **scikit-learn**: For model evaluation and data preprocessing.

## 🛠️ Modeling

The project includes the following steps:

1. **Loading and Preprocessing Data**: Data is read, missing values are checked, and necessary transformations are applied.
2. **Merging Weather Data with Energy Production Data**: The two datasets are merged using date and time information.
3. **Training Different Machine Learning Models**: Models such as LightGBM, XGBoost, and Random Forest are trained.
4. **Evaluating Model Performance**: The performance of the models is compared, and the best-performing model is identified.
5. **Visualizing Results**: Prediction results and model performances are displayed with graphs.

## 📈 Results

At the end of the project, the performances of different models were compared, and the best-performing model was identified. Additionally, the prediction results were visualized.

- **Best Model:** Random Forest Regressor
- **Success Rate:** 0.8644110671548526


## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🔍 Code And Kaggle Link
Project: [energy_amount_prediction.ipynb](https://github.com/omerfarukyuce/Solar-Power-Plant-Electricity-Production-Amounts-May-2018-Prediction-Machine-Learning-/blob/main/energy_amount_prediction.ipynb)

Kaggle: [may_2018_energy_amount_prediction](https://www.kaggle.com/code/merfarukyce/may-2018-energy-amount-prediction)

## 📊 Datasets
Dataset: [Dataset](https://data.ibb.gov.tr/dataset/ikitelli-gunes-enerjisi-santrali-elektrik-uretim-miktarlari)
