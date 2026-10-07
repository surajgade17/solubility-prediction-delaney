# Solubility Prediction — Delaney Dataset

Predicts the aqueous solubility (logS) of molecules from their chemical structure using RDKit descriptors and a Random Forest model.

## Overview

Solubility is an important property in drug discovery because a drug must dissolve to be absorbed by the body. This project builds a simple machine learning model that predicts solubility from molecular descriptors.

## Dataset

- **Delaney (ESOL) dataset:** molecules as SMILES strings with measured water solubility (log mol/L)
- Source: DeepChem datasets

## Tools

- Python
- Pandas
- RDKit
- scikit-learn
- Google Colab

## Workflow

1. Load the dataset with Pandas
2. Validate SMILES strings with RDKit
3. Calculate molecular descriptors: molecular weight, LogP, H-bond donors, H-bond acceptors, TPSA
4. Split data into training (80%) and test (20%) sets
5. Train a Random Forest regression model
6. Evaluate the model with R² and RMSE

## How to Run

1. Open `solubility-prediction-delaney.ipynb` in Google Colab
2. Run all cells from top to bottom (RDKit installs in the first cell)

## Author

Suraj Gade
M.Sc. Organic Chemistry, Sanjivani University
GitHub: [surajgade17](https://github.com/surajgade17)