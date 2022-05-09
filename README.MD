# DLH Project
## Overview
This project is to reproduce the approach from ”Applying Convolutional Neural Networks to Predict the ICD-9 Codes of Medical Records” by Jia-Lien Hsu, Teng-Jie Hsu, Chung-Ho Hsieh and Anandakumar Singaravelan.

## Usage
### Install
To run the code, the following python modules are needed: pandas, numpy, sklearn, tensorflow, keras, reduce, re
### Dataset
Johnson, Alistair, et al. "MIMIC-III Clinical Database" (version 1.4). PhysioNet (2016), https://doi.org/10.13026/C2XW26.
`NOTEEVENTS.csv` 
`DIAGNOSES_ICD.csv`
### Run the code
1.  Run jupyter notebook

`jupyter notebook`

2.  Open the `Extract_ChiefComplaint.ipynb`, please make sure `NOTEEVENTS.csv` and `DIAGNOSES_ICD.csv` are in the same path, and run the notebook to get the csv file with chief complaint and corresponding ICD-9 Code
3. Open the `Prediction_Model.ipynb` and run the notebook to train the model
