# Energy Consumption Prediction

## Overview

This project uses machine learning algorithms to predict energy consumption based on historical data, environmental factors (like temperature and humidity), and time of day. The model is trained on real-world data and can be used for energy optimization in various applications.

---

## Technologies Used

- **Python** for the main programming language.
- **Scikit-learn** for building the machine learning model.
- **Flask** for serving the model through a web interface.
- **Matplotlib** and **Seaborn** for data visualization.
- **Pandas** for data manipulation.
- **Jupyter Notebook** for exploratory data analysis and visualization.

---

## Features

- **Data Preprocessing**: Clean and transform raw data to make it ready for model training.
- **Model Building**: Train a predictive model using historical energy consumption data.
- **Visualization**: Visualize the performance of the model using plots.
- **Web Application**: Use a simple Flask app to predict energy consumption in real-time based on user inputs.

---

## Dataset

The dataset used for training the model includes historical energy consumption data along with environmental factors (temperature, humidity, time of day). The dataset is assumed to be available in the `data` directory as a `.csv` file. Example columns in the dataset include:

- **Time**: Hour of the day (or timestamp).
- **Temperature**: Temperature in Celsius.
- **Humidity**: Percentage of humidity.
- **Energy Consumption**: The target variable representing energy consumption in kWh.

---

## Setup Instructions

### Prerequisites

Ensure you have Python 3.6+ installed on your system.

### 1. Clone the repository

```bash
git clone https://github.com/KOMMISETTYSIVANI6/Energy-consumption-prediction.git
cd Energy-consumption-prediction

