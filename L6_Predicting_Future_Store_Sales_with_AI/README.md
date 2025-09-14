# Time Series Analysis & Forecasting Project

This project demonstrates time series analysis and forecasting using ARIMA and SARIMA models to predict airline passenger numbers.

## Setup Instructions

### 1. Install Dependencies
First, install the required Python packages:

```bash
pip install -r requirements.txt
```

### 2. Download the Dataset
The dataset is available in the GitHub repository. You have two options:

**Option A: Clone the repository (recommended)**
```bash
git clone https://github.com/GeeksforgeeksDS/21-Days-21-Projects-Dataset.git
```

**Option B: Download manually**
1. Go to: https://github.com/GeeksforgeeksDS/21-Days-21-Projects-Dataset
2. Download the repository as ZIP
3. Extract it to your project directory

### 3. Run the Notebook
```bash
jupyter notebook 6_Predicting_Future_Store_Sales_with_AI.ipynb
```

## Project Overview

This notebook covers:
- Time series decomposition and visualization
- Stationarity testing using Augmented Dickey-Fuller test
- Data transformation techniques (log transform and differencing)
- ARIMA model building and evaluation
- SARIMA model for seasonal data
- Forecasting and model comparison

## Dataset
- **File**: `airline_passenger_timeseries.csv`
- **Description**: Monthly airline passenger data from 1949-1960
- **Features**: Month, Passengers (in thousands)

## Requirements
- Python 3.8+
- Jupyter Notebook
- All dependencies listed in `requirements.txt`

