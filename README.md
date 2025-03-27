# Model Calibration: Improving Probability Predictions

This project demonstrates how to improve the reliability of classification probabilities using model calibration techniques. We apply calibration to Logistic Regression, Random Forest, and Support Vector Machine (SVM) using the Breast Cancer Wisconsin dataset.

## Objective

To show how raw classifier probabilities can be misleading and how calibration techniques such as Platt Scaling (sigmoid) and Isotonic Regression can be used to produce more trustworthy probability estimates.

## Dataset

- **Name**: Breast Cancer Wisconsin (Diagnostic)
- **Source**: scikit-learn built-in dataset
- **Target**: Binary classification (Malignant vs Benign)

## Key Features

- Training and testing of uncalibrated models
- Use of `CalibratedClassifierCV` from `sklearn`
- Visualization of reliability diagrams
- Calculation of Brier Score for calibration quality
- Comparison of calibrated vs uncalibrated models

## Files

| File | Description |
|------|-------------|
| `model_calibration_breast_cancer.ipynb` | Full implementation with markdowns and visuals |
| `README.md` | Project overview and instructions |
| `requirements.txt` | Python packages required to run this notebook |

## How to Run

1. Install dependencies using:
   ```
   pip install -r requirements.txt
   ```
2. Open the notebook using Jupyter or Google Colab.
3. Run all cells from top to bottom.

## License

This project is licensed for educational use. Dataset provided by scikit-learn (MIT licensed).
