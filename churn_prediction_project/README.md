# Churn prediction project

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Predicting telecom customer churn using machine learning

## Project Organization

├── LICENSE <- Open-source license if one is chosen  
├── Makefile <- Makefile with convenience commands like make data or make train  
├── README.md <- The top-level README for developers using this project.  
├── data  
│   ├── external <- Data from third party sources.  
│   ├── interim <- Intermediate data that has been transformed.  
│   ├── processed <- The final, canonical data sets for modeling.  
│   └── raw <- The original, immutable data dump.  
├── docs <- A default mkdocs project; see www.mkdocs.org for details  
├── models <- Trained and serialized models, model predictions, or model summaries  
├── notebooks <- Jupyter notebooks. Naming convention is a number (for ordering)  
│   the creator's initials, and a short - delimited description.  
├── pyproject.toml <- Project configuration file with package metadata for  
│   churn and configuration for tools like black  
├── references <- Data dictionaries, manuals, and all other explanatory materials.  
├── reports <- Generated analysis as HTML, PDF, LaTeX, etc.  
│   └── figures <- Generated graphics and figures to be used in reporting  
├── requirements.txt <- The requirements file for reproducing the analysis environment.  
├── setup.cfg <- Configuration file for flake8  
└── churn <- Source code for use in this project.  
    ├── init.py  
    ├── config.py  
    ├── dataset.py  
    ├── features.py  
    ├── modeling  
    │   ├── init.py  
    │   ├── predict.py  
    │   └── train.py  
    └── plots.py  

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
source venv/bin/activate  (macOS/Linux)  

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

