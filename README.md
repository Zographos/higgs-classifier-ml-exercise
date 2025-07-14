# higgs-classifier-ml-exercise

## Higgs Signal vs. Background Classification

This repository contains code and a report for the exercise **“Classification for Higgs Signal vs. Background”** using several machine-learning methods:

- **kNN** (k-Nearest Neighbors)  
- **Decision Tree**  
- **Random Forest**  
- **ANN** (Artificial Neural Network)

## Contents
- `HIGGS_8K.csv` – original dataset (8 000 samples, 28 features)  
- `HIGGS Classification - KNN.ipynb` – kNN implementation, hyperparameter tuning, confusion matrices & ROC plots  
- `HIGGS Classification - DecisionTree.ipynb` – Decision Tree implementation & evaluation  
- `HIGGS Classification - RandomForest.ipynb` – Random Forest implementation & evaluation  
- `HIGGS Classification - ANN.ipynb` – Neural network implementation & evaluation  
- `Project_2.pdf` – 2-page write-up + appendix  
- `figures/` – All generated PNG plots (organized by method)

## Dependencies

Make sure you have Python 3.8+ and install:

```bash
pip install \
  numpy \
  pandas \
  scikit-learn \
  matplotlib \
  joblib \
  tensorflow
