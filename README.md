# Customer Churn Prediction Project

This project performs end-to-end customer churn analysis and machine learning modeling using the notebook `PDS_Project.ipynb`.

## Project Files
- `PDS_Project.ipynb`: Main notebook for EDA, feature engineering, training, and evaluation.
- `EDA_Report.html`: Auto-generated EDA report using `ydata-profiling`.
- `PDS_Report_13.pdf`: Project report.
- `requirements.txt`: Python dependencies.

## Dataset Requirement
The notebook expects this dataset file in the project root:

- `Customer-Churn-Records.csv`

Place it in the same folder as `PDS_Project.ipynb` before running cells.

## Environment Setup
### 1. Create virtual environment
```powershell
python -m venv .venv
```

### 2. Activate environment (Windows PowerShell)
```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies
```powershell
pip install -r requirements.txt
```

### 4. Open notebook
Run `PDS_Project.ipynb` in Jupyter or VS Code Notebook.

## Notes
- The notebook includes SMOTE and multiple ML models (Logistic Regression, SVM, Decision Tree, Random Forest, XGBoost).
- Hyperparameter tuning with RandomizedSearchCV is included and can be time-consuming.
- `random_forest_model.pkl` may be generated when saving the model and is ignored by `.gitignore`.

## Push to GitHub
```powershell
git init
git add .
git commit -m "Initial commit: churn project"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```
