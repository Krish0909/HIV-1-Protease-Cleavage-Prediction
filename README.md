# HIV-1 Protease Cleavage Prediction

This project predicts whether a peptide sequence will be cleaved by the HIV-1 protease enzyme. The model uses sequence-based molecular descriptors and trains a machine learning model to evaluate cleavage probabilities.

## Overview

HIV-1 protease is a critical enzyme in the life cycle of the HIV virus. Predicting its cleavage specificity is important for antiviral drug design. This project utilizes data from the **UCI Machine Learning Repository** and applies machine learning techniques to predict cleavage activity.

## Features

- Extracts sequence-based molecular descriptors (e.g., sequence length, amino acid composition, physicochemical properties).
- Implements a Random Forest Classifier for prediction.
- Evaluates the model using ROC AUC and Precision-Recall AUC scores.
- Visualizes ROC and Precision-Recall curves.
- Provides feature importance analysis.
- Makes predictions on new peptide sequences.

---

## Dataset

The dataset used in this project is obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). Specifically, the **HIV-1 protease cleavage dataset** (`1625Data.txt`) contains peptide sequences and corresponding cleavage labels (1 for cleaved, 0 for non-cleaved).

---

## Requirements

To run this project, you need the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`

You can install the necessary packages using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib
