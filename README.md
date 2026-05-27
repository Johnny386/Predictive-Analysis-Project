# Predictive-Analysis-Project

## Overview

This project aims to predict whether a previous donor will donate for a certain campaign to an NGO. The predictive model is built based on comprehensive transactional and demographic data spanning 18 years of donor history.

## Project Objective

The primary goal is to develop a machine learning model that can identify high-probability donors for targeted fundraising campaigns, enabling the NGO to optimize marketing spend and improve campaign effectiveness.

## Dataset

- **Time Period**: 18 years of historical data
- **Data Types**: 
  - Transactional data (donation history, amounts, frequency)
  - Demographic data (donor characteristics, location, etc.)
- **Target Variable**: Whether a donor will contribute to a specific campaign

## Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Multiple machine learning models
- Model evaluation and comparison
- Predictive insights for donor targeting

## Technology Stack

- **Language**: Python
- **Notebooks**: Jupyter Notebooks
- **Key Libraries**: 
  - pandas (data manipulation)
  - scikit-learn (machine learning)
  - matplotlib/seaborn (visualization)
  - numpy (numerical computing)

## Project Structure

```
Predictive-Analysis-Project/
├── README.md
├── notebooks/                      # Jupyter notebooks with analysis
├── data/                          # Dataset files
├── models/                        # Trained model artifacts
└── results/                       # Output reports and visualizations
```

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required packages: pandas, scikit-learn, matplotlib, seaborn, numpy

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Johnny386/Predictive-Analysis-Project.git
cd Predictive-Analysis-Project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Usage

Navigate to the notebooks directory and open the analysis files to:
- Explore the donor data
- Review model development and training
- Examine prediction results and insights

## Model Performance

The models are evaluated using appropriate metrics for binary classification, including accuracy, precision, recall, and AUC-ROC scores.

## Key Insights

The analysis provides actionable insights on:
- Donor behavior patterns
- Key predictive factors for campaign donations
- Campaign targeting recommendations

## Results

The trained models can be used to:
- Score existing donors for campaign potential
- Identify donor segments most likely to respond
- Optimize resource allocation for fundraising efforts

## Author

**Johnny386**

## License

This project is provided as-is for educational and analytical purposes.

---

**Last Updated**: 2026-05-27
