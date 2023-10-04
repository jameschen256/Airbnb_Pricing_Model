# Airbnb Pricing Model

This repository contains a machine learning model developed to predict Airbnb pricing in New York City based on various factors like location, number of rooms, beds, and more.

## Overview

The `AirbnbPricingModel.ipynb` notebook offers a comprehensive walkthrough of the entire data science pipeline, from data preprocessing to model training and evaluation. The primary goal of this model is to provide accurate price predictions for Airbnb listings in NYC, aiding hosts in setting competitive prices for their properties.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, sklearn, seaborn, matplotlib, and any other library mentioned in the notebook.

## Getting Started

### Setup

1. Clone this repository:

```bash
git clone https://github.com/jameschen256/Airbnb_Pricing_Model.git
```

2. Navigate to the project directory:

```bash
cd Airbnb_Pricing_Model
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `AirbnbPricingModel.ipynb` notebook from the Jupyter dashboard.

### Usage

Run the cells sequentially in the notebook to:

- Load the dataset.
- Conduct exploratory data analysis (EDA).
- Preprocess and clean the data.
- Train the pricing prediction model.
- Evaluate the model's performance.

## Model Highlights

- **Data Exploration**: The notebook begins with an in-depth EDA to understand the dataset's underlying structure and identify any patterns or anomalies.

- **Feature Engineering**: Various features are engineered and selected to improve the model's predictive capability.

- **Model Training**: Utilizes the linear regression algorithm from the Scikit-Learn library to predict Airbnb pricing trends based on the dataset.

- **Evaluation**: The model's performance is measured using the R^2 value, providing insights into its accuracy.
