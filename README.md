# Credit Card Fraud Detection Using Machine Learning

## Overview
This project demonstrates the application of machine learning models, particularly the Random Forest classifier, to detect fraudulent credit card transactions. Given the vast amount of transactions processed daily, it’s crucial to have robust and accurate methods to identify and prevent fraud.

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders.

- **Number of Transactions:** 284,807
- **Number of Fraudulent Transactions:** 492
- **Features:** 30, including `Time`, `Amount`, and anonymized variables `V1` to `V28`

## Models Used
- **Random Forest Classifier:** A robust ensemble learning method that operates by constructing multiple decision trees and outputting the mode of the classes (classification) or mean prediction (regression) of the individual trees.

## Implementation

### Prerequisites
- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

### Installation
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
