# Hazardous Space Object Detection

This project uses machine learning to find out if Near-Earth Objects (NEOs) are dangerous to Earth.

## Dataset

The main data is in `neo.csv`. It has information about NEOs, like their size, speed, and distance. The key column is `hazardous` (0 for safe, 1 for dangerous).

## Notebooks

- **neo_eda.ipynb**: Checks the data. Looks at shape, missing values, and how features relate to each other.
- **neo_balancing_data.ipynb**: Fixes unbalanced data if one class has more examples.
- **neo_outlire.ipynb**: Finds and removes strange data points (outliers).
- **random_forest.ipynb**: Trains a Random Forest model to predict if an NEO is hazardous. Shows accuracy and other scores.
- **svm_neo.ipynb**: Trains an SVM model for the same prediction. Uses RBF kernel.
- **xgboost_neo.ipynb**: Trains an XGBoost model to predict hazardous NEOs. Shows precision, recall, and F1-score.

## Requirements

You need Python and these libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost


## How to Run

1. Open the notebooks in VS Code (with Python extension installed).
2. Run the cells one by one.
3. Make sure `neo.csv` is in the same folder.

## Project Files

- `neo.csv`: The dataset.
- `neo_eda.ipynb`: Data exploration.
- `neo_balancing_data.ipynb`: Data balancing.
- `neo_outlire.ipynb`: Outlier handling.
- `random_forest.ipynb`: Random Forest model.
- `svm_neo.ipynb`: SVM model.
- `xgboost_neo.ipynb`: XGBoost model.
- `archive.zip`: Extra data.
- `Introduction-to-Hazardous-Space-Object-Detection.pptx`: Presentation.
