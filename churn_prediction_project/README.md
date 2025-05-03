# Churn Prediciton Projct

## Projec Structure

churn
├── config.py
├── dataset.py
├── features.py
├── plots.py
└── modeling
├── predict.py
└── train.py
notebooks
├── eda-churn.ipynb
└── data
└── processed
└── churn_analysis_results.csv
raw
└── telco_churn.csv
reports
├── INST414_Sprint2_Revised_Assignment.pdf
├── INST414_Sprint3.pdf
└── figures
.gitignore
LICENSE
Makefile
pyproject.toml
requirements.txt
README.md

## Dependencies
To instll the required pacages, run:

`pip isntall -r requirments.txt`

Main libaries used:
- pandas
- numppy
- matplolib
- seaborne
- scikit-learn
- jupyter

## Setting up the envirnment
Create a virual enviroment:

`python -m venv venv`

Activate the environment:

`venv\Scripts\activate (Windows)`


Install dependencies:

`pip isntall -r requirments.txt`

## Running the data pipline
To perpare the data, run the following scrips:

`python churn/dataset.py`  
`python churn/features.py`

## Model trianing and predction
Train the model using:

`python churn/modling/train.py`

Genrate predictions using:

`python churn/modeling/predict.py`

## Reproducbility
Follow these steps:
1. Run dataset.py
2. Run features.py
3. Train model with train.py
4. Predict with predcit.py
5. View results in notebooks/ or reports/
