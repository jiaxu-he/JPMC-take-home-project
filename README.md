# Income Prediction & Customer Segmentation

Machine learning analysis using U.S. Census Bureau data (1994-1995) to predict income levels and segment customers.

## Requirements

Install required packages:
```
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

## Instructions to Run

1. **Extract the data:**
   - Unzip `TakeHomeProject_OCT2025.zip` 
   - Place the unzipped data files (`census-bureau.data` and `census-bureau.columns`) in the same directory as the notebook

2. **Open and run the notebook:**
```
   jupyter notebook project_final_code.ipynb
```

3. **Run all cells in order** (Cell → Run All)

## Files

- `project_final_code.ipynb` - Main analysis notebook
- `final_report.docx` - Project report
- `TakeHomeProject_OCT2025.zip` - Dataset (extract before running)

## Results

- Classification Model: Macro F1 = 0.8, ROC-AUC = 0.95
- Segmentation: 4 customer segments identified
