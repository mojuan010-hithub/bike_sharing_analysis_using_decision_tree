# Bike Sharing — Decision Tree Model

A concise Jupyter Notebook project that trains and evaluates a decision tree model on a bike sharing dataset. The notebook demonstrates data loading, cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and simple visualization of the trained tree.

## Contents
- `bike_sharing_decision_tree.ipynb` — main notebook
- `data/` — store dataset CSV (e.g., UCI Bike Sharing Dataset or equivalent)
- `requirements.txt` — Python dependencies
- `LICENSE` — project license (MIT recommended)

## Features
- Load and preprocess bike-sharing data
- Exploratory analysis (time-based trends, feature correlations)
- Train/test split and baseline comparison
- Train and tune a DecisionTreeRegressor/DecisionTreeClassifier
- Model evaluation: MAE, RMSE, R2 (for regression) or precision/recall/F1 (for classification)
- Decision tree visualization (matplotlib / graphviz)
- Reproducible pipeline with fixed random seed

## Requirements
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Packages: pandas, numpy, scikit-learn, matplotlib, seaborn, graphviz (optional)

Example requirements.txt entry:
```
pandas
numpy
scikit-learn
matplotlib
seaborn
graphviz
jupyter
```
matplotlib
seaborn
graphviz
jupyter
```

Install:
```
pip install -r requirements.txt
```

## Quick start
1. Put your dataset CSV into `data/` (e.g., `data/bike_sharing.csv`).
2. Open the notebook:
```
jupyter notebook bike_sharing_decision_tree.ipynb
```
3. Run all cells (Kernel → Restart & Run All) to reproduce the analysis and model training.

Headless execution:
```
jupyter nbconvert --to notebook --execute bike_sharing_decision_tree.ipynb --output executed_notebook.ipynb
```

## Notebook structure
1. Project overview and objectives  
2. Environment and imports  
3. Load dataset  
4. Data cleaning and preprocessing  
5. EDA and visualization  
6. Feature engineering  
7. Train/test split and baseline models  
8. Decision tree training and hyperparameter tuning  
9. Evaluation and interpretation  
10. Exporting model/artifacts and visualization

## Tips
- Set `random_state` for reproducible results.
- Use cross-validation and grid search for hyperparameter tuning.
- Use `export_graphviz` or `plot_tree` for visualization; install Graphviz system binary to render `.dot` files.

## Results & Evaluation
Document key metrics and model graphs in the notebook outputs. Include a short summary cell with final chosen model parameters and evaluation scores.

## Reproducibility
- Record package versions (e.g., `pip freeze > requirements.txt`).
- Save a copy of the dataset used and the executed notebook (`.ipynb` with outputs).

## License
MIT — see `LICENSE` for details.

## Contributing / Issues
Open issues or pull requests in the repository. For questions, create an issue with steps to reproduce and relevant logs.

