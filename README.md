# Bulldozer Price Prediction

A machine learning project that predicts used bulldozer sale prices using the **Blue Book for Bulldozers** dataset and a Random Forest Regressor.

## Technologies
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
- Jupyter Notebook

## Features
- Processes over **412,000 training records**.
- Handles missing values and categorical data.
- Performs date-based feature engineering.
- Trains and tunes a Random Forest regression model.
- Evaluates predictions using MAE, RMSLE, and R².
- Achieved a reported **88.2% validation R² score**.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/sks2706-dev/Bulldozer-Price-Prediction-model.git
cd Bulldozer-Price-Prediction-model
```

Install dependencies:

```bash
pip install numpy pandas matplotlib scipy scikit-learn notebook joblib
```

Download the dataset from [Kaggle — Blue Book for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data), place the required CSV files in the directory expected by the notebook, and run:

```bash
jupyter notebook
```

Open `bulldozer-price-regression.ipynb` and run the cells in order.

## Project Structure

```text
├── bulldozer-price-regression.ipynb
├── environment.yml
└── README.md
```
