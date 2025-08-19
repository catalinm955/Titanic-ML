# Titanic: Machine Learning from Disaster

This is a portfolio for Data Science and Machine Learning.
The goal is to analyze the Kaggle Titanic dataset and experiment with multiple Machine Learning Models such as Logistic Regression, Decision Tree, Random Forest Classifier, XGBoost to generate the most accurate prediction regarding the survivors of the disaster.

## Project Structure

- `data/raw/` - original CSV files from Kaggle
- `data/processed/` - preprocessed data ready for modeling
- `notebooks/` - Jupyter Notebooks for data exploration and visualization
- `reports/figures/` - generated plots and visualizations
- `src/` - Python code for preprocessing, modeling, and evaluation

## Setup

1. Create a virtual environment
```bash
python -m venv venv
```
2. Activate the environment
```bash
venv/Scripts/activate
```
3. Install libraries
```bash
pip install -r requirements.txt
```
4. (Optional) To add a new library
```bash
pip install <library_name>
pip freeze > requirements.txt
```

## Data
This project **does not include raw or processed data** in the repository.
To reproduce the results, follow these steps:
1. Download the original Titanic dataset from "https://www.kaggle.com/competitions/titanic/data" and place the CSV files in `data/raw`.
2. Run the preprocessing scripts in `src/` to generate the preprocessing data in `data/processed`.
3. Run the notebooks in `notebooks/` to explore, visualize and train models.

## Next Steps

1. [ ] Data preprocessing
2. [ ] Exploratory Data Analysis (EDA) and visualization
3. [ ] Model building and experimentation
4. [ ] Evaluation and comparison of model performance
5. [ ] Feature engineering and fine-tune the model
