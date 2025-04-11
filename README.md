# COSC2753 Assignment 1 – README (s3818552)

## Folder Structure

Please maintain the following folder and file structure after extracting the submission:

```
COSC2753_A1_s3818552/
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── cleaned_train.csv
│   └── processed_train.csv
├── models/
│   └── [Trained model .pkl files]
├── metrics/
│   └── [Saved RMSE score .pkl files]
├── notebooks/
│   ├── Step1_EDA.ipynb
│   ├── Step2_DataCleaning.ipynb
│   ├── Step3_DataProcessing.ipynb
│   └── Step4_ModelSelection_and_Prediction.ipynb
├── COSC2753_A1_Predictions_s3818552.csv
└── README.md
```

## Environment Setup

### Python Version:

Compatible with **Python 3.8 – 3.11**

### Install Required Packages:

To install all required libraries, run:

```
pip install pandas numpy matplotlib seaborn scikit-learn joblib scipy
```

No additional API or external data download is required.

## How to Run the Notebooks

1. Open the `notebooks/` folder.
2. Execute the notebooks **in order**:
   - `Step1_EDA.ipynb`
   - `Step2_DataCleaning.ipynb`
   - `Step3_DataProcessing.ipynb`
   - `Step4_ModelSelection_and_Prediction.ipynb`

Each notebook is self-contained and builds upon the previous one.  
Output files (e.g., processed data, models, metrics, and predictions) are saved to their respective folders.

The final prediction file is:

```
COSC2753_A1_Predictions_s3818552.csv
```

## Submission Deliverables

- PDF Report: `COSC2753_A1_s3818552.pdf`
- Video Demo: 5–10 minutes (recommended)
- Prediction CSV: `COSC2753_A1_Predictions_s3818552.csv`
- Source Code ZIP: `COSC2753_A1_s3818552.zip`
- Includes all notebooks, processed files, and this README

## 🧠 Notes

- Final model selected: **Gradient Boosting Regressor**
- All models are trained with 5-fold cross-validation and validated using R², RMSE, MAE, MAPE, and generalization gap analysis.
- Code and structure tested for reproducibility.

**Student ID**: s3818552  
**Course**: COSC2753 Machine Learning  
**Semester**: 2025A  
**Campus**: SGS
