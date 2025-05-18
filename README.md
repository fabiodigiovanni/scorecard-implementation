# scorecard-implementation

This project showcases a complete pipeline for credit risk modelling, combining traditional scorecard development with modern machine learning techniques. It includes all steps from data preprocessing to model evaluation and scorecard generation.

## Overview

The goal is to predict the probability of default using both interpretable and high-performing models. This is achieved by developing a logistic regression-based credit scorecard and comparing it with more advanced machine learning models.

## Key Features

- Data preprocessing and exploratory data analysis (EDA)
- Feature binning and Weight of Evidence (WOE) transformation using `toad`
- Credit scorecard development with logistic regression
- Machine learning models: Random Forest, XGBoost
- ROC-AUC analysis and performance comparison
- Scorecard export and interpretability

## Technologies Used

- Python, pandas, numpy, scikit-learn
- toad, xgboost, keras (TensorFlow backend)
- Matplotlib, seaborn, hvplot for visualization

## Folder Structure

- `scorecard_implementation.ipynb`: Main notebook with full implementation
- `data/`: (Optional) Folder for datasets used in the project
- `output/`: (Optional) Folder for model exports or plots

## How to Run

1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Open the notebook and run all cells

## License

This project is licensed under the MIT License.

---

Feel free to open an issue or contribute with improvements, especially regarding model tuning or interpretability techniques!

