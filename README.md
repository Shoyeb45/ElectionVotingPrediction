# Election Prediction Model

## Description
This project aims to predict election outcomes based on various socio-economic factors. The model utilizes data from surveys to classify voters' preferences between Conservative and Labour parties.

![Build Status](https://img.shields.io/badge/build-passing-brightgreen) <!-- Placeholder for build status badge -->
![License](https://img.shields.io/badge/license-MIT-blue) <!-- Placeholder for license badge -->

## Installation Instructions
To run this project, ensure you have Python installed along with the required libraries. You can install the necessary packages using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

## Usage
1. Load the data from the `Data/Election_Data.xlsx` file.
2. Run the Jupyter notebook `model.ipynb` to perform data analysis, preprocessing, and model training.
3. Follow the steps in the notebook to evaluate different models and their performance.

## Data Description
The dataset contains the following columns:
- **vote**: Party choice (Conservative or Labour)
- **age**: Age in years
- **economic.cond.national**: Assessment of current national economic conditions (1 to 5)
- **economic.cond.household**: Assessment of current household economic conditions (1 to 5)
- **Blair**: Assessment of the Labour leader (1 to 5)
- **Hague**: Assessment of the Conservative leader (1 to 5)
- **Europe**: Attitudes toward European integration (11-point scale)
- **political.knowledge**: Knowledge of parties' positions on European integration (0 to 3)
- **gender**: Gender (Female or Male)

## Model Evaluation
The project evaluates several classification models, including:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- AdaBoost
- Gradient Boosting
- k-Nearest Neighbors (kNN)

Each model's performance is assessed using accuracy, precision, recall, and F1 score.

## License
This project is licensed under the MIT License.
