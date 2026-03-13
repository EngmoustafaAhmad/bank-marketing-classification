## 📂 Project Structure

```
bank-marketing-classification/
│
├── data/
│   ├── raw/
│   │   └── bank-full.csv
│   │
│   └── processed/
│       └── cleaned_data.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_selection.ipynb
│   ├── 04_dimension_reduction.ipynb
│   └── 05_model_training.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_selection.py
│   ├── dimension_reduction.py
│   ├── train_model.py
│   └── evaluate_model.py
│
├── models/
│   └── trained_model.pkl
│
├── reports/
│   ├── figures/
│   │   ├── correlation_matrix.png
│   │   ├── feature_importance.png
│   │   └── confusion_matrix.png
│   │
│   └── project_report.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
```
