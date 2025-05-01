# Churn prediction project

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Predicting telecom customer churn using machine learning

# Project Structure
churn_prediction_project/  
├── .gitignore  
├── LICENSE  
├── Makefile  
├── pyproject.toml  
├── README.md  
├── requirements.txt  
├── churn/  
│   ├── __init__.py  
│   ├── config.py  
│   ├── dataset.py  
│   ├── features.py  
│   ├── plots.py  
│   └── modeling/  
│       ├── __init__.py  
│       ├── predict.py  
│       └── train.py  
├── notebooks/  
│   ├── .gitkeep  
│   ├── eda-churn.ipynb  
│   ├── INST414_Sprint2.ipynb  
│   └── data/  
│       └── processed/  
│           └── churn_analysis_results.csv  
└── reports/  
    ├── .gitkeep  
    ├── INST414_Sprint2_Revised_Assignment.pdf  
    └── figures/  
        └── .gitkeep

## Dependencies

To install the required packages, run:

pip install -r requirements.txt

Main libraries used:  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- jupyter  

## Setting up the environment

Create a virtual environment:  
python -m venv venv  

Activate the environment:  
venv\Scripts\activate     (Windows)  

Install dependencies:  
pip install -r requirements.txt  

## Running the data pipeline

To prepare the data, run the following scripts:  
python churn/dataset.py  
python churn/features.py  

## Model training and prediction

Train the model using:  
python churn/modeling/train.py  

Generate predictions using:  
python churn/modeling/predict.py  

## Reproducibility

Follow these steps:  
1. Run dataset.py  
2. Run features.py  
3. Train model with train.py  
4. Predict with predict.py  
5. View results in notebooks/ or reports/

