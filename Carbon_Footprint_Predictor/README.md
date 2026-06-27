# 🌍 Carbon Footprint Predictor

Predicts an individual's annual CO₂ emissions (kg) based on daily lifestyle factors using a modular scikit-learn Pipeline.

## 📁 Project Structure

```
Carbon_Footprint_Predictor/
├── carbon_footprint_predictor.ipynb   ← Main Jupyter Notebook
└── README.md
```

## 📥 Dataset

**Source:** [Kaggle — Individual Carbon Footprint Calculation](https://www.kaggle.com/datasets/dumanmesut/individual-carbon-footprint-calculation)

Download `carbon_footprint_dataset.csv` from Kaggle and place it in the same folder as the notebook before running.

- 10,000 samples
- 20 features (Diet, Transport, Heating, etc.)
- Target: `CarbonEmission` (annual CO₂ in kg)

## 🛠️ Tech Stack

- Python 3.x
- pandas, numpy
- scikit-learn (Pipeline, ColumnTransformer)
- matplotlib, seaborn

## 🚀 How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook carbon_footprint_predictor.ipynb
```

## 📊 Models

| Model | MAE | R² |
|---|---|---|
| Linear Regression | 285.19 kg | 0.89 |
| Random Forest | 304.29 kg | 0.90 |

## 🔑 Key Features

- Modular sklearn Pipeline with ColumnTransformer
- OneHotEncoding for categorical features
- StandardScaler for numerical features
- Two models trained and compared
- Visualizations: distribution, heatmap, prediction vs actual

## 👤 Author

**Sai Ramya** — GSSoC 2026 Contribution  
GitHub: [@Sai-Ramya-prog](https://github.com/Sai-Ramya-prog)