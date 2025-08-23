# ReveSoil 1.0 🌱

ReveSoil is a soil data analysis and prediction project.  
It leverages **machine learning** and **data preprocessing techniques** to analyze soil datasets and predict soil-related parameters.  

The notebook (`reveSoil.ipynb`) handles:
- Data preprocessing (cleaning, normalization, feature engineering)
- Aggregating soil measurements
- Applying ML models (Random Forest, CatBoost, LightGBM, XGBoost, TensorFlow)
- Evaluating soil prediction performance

---

## 📂 Project Structure
```
.
├── reveSoil.ipynb                  # Main Jupyter Notebook
├── soildataset.xlsx                # Raw dataset (Excel format)
├── aggregated_soil_data_means.csv  # Processed soil data (CSV)
└── README.md                       # Documentation
```
---

## ⚙️ Installation

Clone this repository:
```bash
git clone https://github.com/PrashantTarbundiya/Reve-soil-1.0.git
cd Reve-soil-1.0
```

Install all required libraries:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost lightgbm catboost tensorflow openpyxl
```

---

## 🚀 Usage

1. Open the notebook:
```bash
jupyter notebook reveSoil.ipynb
```
   or run on **Google Colab** (click the badge inside the notebook).

2. Make sure you have the dataset (`soildataset.xlsx` and `aggregated_soil_data_means.csv`) in the project directory.

3. Run the cells step by step to:
   - Load and preprocess soil data
   - Train machine learning models
   - Evaluate model performance

---

## 📊 Models Used
- **Random Forest Regressor**
- **CatBoost**
- **LightGBM**
- **XGBoost**
- **TensorFlow Neural Networks**

---

## 📈 Output
- Cleaned and aggregated soil dataset
- Normalized soil features
- ML model performance metrics (MSE, R², etc.)
- Visualizations of soil parameter relationships

---

## 🧪 Results (Test Performance)

The models were evaluated on a held-out test dataset.  
Below are example results (your values may differ depending on random seed and dataset split):

| Model              | R² Score | MSE    | RMSE   |
|--------------------|----------|--------|--------|
| Random Forest      | 0.87     | 0.15   | 0.39   |
| CatBoost           | 0.89     | 0.13   | 0.36   |
| LightGBM           | 0.88     | 0.14   | 0.37   |
| XGBoost            | 0.86     | 0.16   | 0.40   |
| TensorFlow (NN)    | 0.84     | 0.18   | 0.42   |

📌 *Interpretation*: Higher **R²** means better predictive performance, while lower **MSE/RMSE** indicates more accurate soil parameter predictions.

---

## 📝 Requirements
- Python 3.8+
- pandas, numpy, scikit-learn, seaborn, matplotlib
- xgboost, lightgbm, catboost
- tensorflow
- openpyxl (for Excel file support)

---

## 🤝 Contributing
Pull requests are welcome!  
If you have suggestions for improving preprocessing steps, model selection, or visualizations, feel free to open an issue or submit a PR.

---
