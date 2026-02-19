# JPMC-take-home-project

# Income Prediction & Customer Segmentation

Machine learning analysis using U.S. Census Bureau data (1994-1995) to predict income levels and segment customers.

## Requirements

Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

## Instructions to Run

1. Place these files in the same directory as the notebook:
   - `census-bureau.data` (main dataset)
   - `census-bureau.columns` (column names)

2. Open and run the notebook:
```bash
   jupyter notebook census_analysis.ipynb
```

3. Run all cells in order (Cell → Run All)

## Files

- `census_analysis.ipynb` - Main analysis notebook
- `final_report.docx` - Project report
- `census-bureau.data` - Dataset
- `census-bureau.columns` - Column names

## Results

- Classification Model: Macro F1 = 0.8, ROC-AUC = 0.95
- Segmentation: 4 customer segments identified
