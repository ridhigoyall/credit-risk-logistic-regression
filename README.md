# Credit Risk Prediction

## Problem

The objective of this project is to predict whether a borrower is likely to default on a loan using financial and behavioral features.

## Model

A Logistic Regression model was used to classify borrowers into default and non-default categories after performing data preprocessing and feature selection.

## Key Result

The model achieved high overall accuracy but showed low recall (~40%) for the default class due to class imbalance in the dataset.

## Conclusion

Although the model performs well in identifying non-default cases, it struggles to detect a significant portion of defaulters. This limitation makes it less reliable for real-world credit risk applications, where identifying high-risk borrowers is critical. Future improvements such as handling class imbalance and adjusting decision thresholds can enhance model performance.

References
* Dataset: [Credit Risk Dataset (Kaggle)](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
* Google Colab Notebook: https://colab.research.google.com/drive/14afpcczI2FIdZ_Vn5AU6a50W3-nfbHAN?usp=sharing
