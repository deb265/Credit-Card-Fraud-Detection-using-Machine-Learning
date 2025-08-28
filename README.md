# Credit Card Fraud Detection

This repository contains a Jupyter Notebook implementation for detecting fraudulent credit card transactions. The dataset is highly imbalanced, with very few fraud cases compared to normal transactions. The objective is to train and evaluate machine learning models that can detect fraud while minimizing false positives.

## Dataset
You can download the dataset from the link below:  
[Download Dataset (creditcard.csv)](https://media.geeksforgeeks.org/wp-content/uploads/20240904104950/creditcard.csv)

## Features
- Preprocessed numerical features (anonymized due to confidentiality).  
- *Amount*: Transaction amount.  
- *Class*: Target label (0 = Non-Fraud, 1 = Fraud).  

## Workflow
1. Load and preprocess data.  
2. Perform exploratory data analysis (EDA).  
3. Handle class imbalance.  
4. Train machine learning models.  
5. Evaluate performance using metrics like precision, recall, and F1-score.  

## Requirements
- Python 3.x  
- Jupyter Notebook  
- pandas, numpy, scikit-learn, matplotlib, seaborn  

Install dependencies:  
```bash
pip install -r requirements.txt

```
## Results

The notebook evaluates multiple models and compares their ability to detect fraud effectively. Key focus is on recall and F1-score, as catching fraud is more important than overall accuracy.
