# Stroke Risk Prediction

This project applies classical machine learning models to predict stroke occurrence from demographic and clinical data.

## Repository Structure
```
stroke-prediction/
│
├── data/
│   └── Stroke_dataset.csv        # dataset used for training/evaluation
│
├── notebooks/
│   └── Stroke_Prediction.ipynb   # main Jupyter notebook (code and results)
│
├── reports/
│   └── final_report.pdf          # final project report (summary of results)
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## Dataset
- **File**: `Stroke_dataset.csv` (in `data/`)
- Contains demographic and clinical features (e.g., age, BMI, hypertension) and a binary target column indicating stroke occurrence.
- The notebook expects this exact file name and path.

## Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- KNN
- Support Vector Classifier (SVC)

Metrics reported: Accuracy, Precision, Recall, F1-score (with special focus on the stroke class), ROC–AUC, and confusion matrices.

## Environment Setup
Requires Python 3.9+. Install dependencies using:

```bash
pip install -r requirements.txt
```

## Running the Project
1. Clone the repo and create a virtual environment.
2. Ensure `data/Stroke_dataset.csv` exists in the correct folder.
3. Launch Jupyter and run the notebook:

```bash
jupyter lab
# or
jupyter notebook
```

4. Open `notebooks/Stroke_Prediction.ipynb` and run all cells.

## Outputs
- Model performance comparison (tables and plots).
- Confusion matrices and ROC curves for all models.
- Final discussion and evaluation in `reports/final_report.pdf`.

## Author
- Harish Padmanabhan

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
