# Logistic Regression Machine Learning Project - Titanic

## 1. Project Overview

This project implements a Logistic Regression model to help to predict who lives in Titanic. Logistic Regression is a statistical model used for binary classification tasks, estimating the probability that an instance belongs to a particular class.

## 2. Dataset Source

https://www.kaggle.com/c/titanic

## 3. Features
- Data Preprocessing: Data cleaning, normalization, and splitting into training and testing sets.
- Model Training: Training a Logistic Regression model using scikit-learn.
- Model Evaluation: Evaluating the performance of the model using metrics such as accuracy, precision, recall, F1-score, and plot the ROC curve.
- Visualization: Visualization the ROC curve.


## 4. Project Structure
    ├── train.csv                   # Dataset file 
    ├── titanic_survival.ipynb      # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/titanic.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook titanic_survival.ipynb
```
## 6. Usage

Open the sonar.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- Data Loading and Preprocessing: Load data from data/ folder and perform necessary preprocessing.
- Model Training: Train an SVM model with adjustable hyperparameters.
- Model Evaluation: Evaluate the model using accuracy, precision, recall, F1-score.

## 7. Results in Test
| Metric    |  Value   |
|-----------|----------|
| Accuracy  |  80%   |
| Precision |  79%   |
| Recall    |  77%   |
| F1-Score  |  78%   |

## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







