# Credit Card Fraud Detection

This project aims to develop a machine learning model for the detection of fraudulent transactions in credit card data. The dataset contains anonymized features and transaction amounts, and the goal is to predict whether a transaction is fraudulent (Class 1) or not (Class 0).

## Dataset

The dataset consists of the following columns:

- **id**: A unique identifier for each transaction.
- **V1-V28**: Anonymized features representing various transaction attributes (e.g., time, location, etc.).
- **Amount**: The transaction amount.
- **Class**: Binary label indicating whether the transaction is fraudulent (1) or not (0).

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for the project.
- `notebooks/`: Includes Jupyter notebooks for data analysis, model building, and evaluation.
- `model_xgboost.pkl`: The saved XGBoost model for fraud detection.
- `documentation/`: This folder contains project-related documents and resources.

## Environment Requirements

Ensure you have the following libraries and tools installed in your Python environment:

- Python 3.7 or higher
- Libraries: pandas, scikit-learn, xgboost, imbalanced-learn, matplotlib
- Jupyter Notebook (optional)

## Model Training

To train the XGBoost model, follow the steps outlined in the 'training_model.ipynb' notebook located in the 'notebooks/' directory.

## Model Evaluation

Model evaluation is performed in the 'evaluation_model.ipynb' notebook, also found in the 'notebooks/' directory. Performance metrics such as precision, recall, F1-score, and AUC are used to assess the model's effectiveness.

## Using the Trained Model

To use the trained model in an application or production environment, you can load it from the 'model_xgboost.pkl' file using the code provided in the "Loading the Model from the File" section in the 'evaluation_model.ipynb' notebook.

## Visualizing Results

In addition to performance metrics, feature importance visualization is provided in the 'evaluation_model.ipynb' notebook. The visualization is presented in a horizontal bar chart.
