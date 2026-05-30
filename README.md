# 🏀 NBA Game Outcome Prediction

A classification project that predicts NBA game outcomes using PCA for dimensionality reduction on game statistics data.

## 📊 Results

| Metric | Score |
|--------|-------|
| ROC-AUC Score | 0.8592 |

## 📁 Project Structure

```
nba-game-prediction/
│
├── nba_prediction.ipynb   # Main notebook
├── nba_final.csv          # Dataset
└── README.md
```

## 🔍 Approach

1. **Data Cleaning** — Prepared and standardised NBA game statistics
2. **EDA** — Explored game metrics and their relationship to match outcomes
3. **PCA** — Applied Principal Component Analysis to reduce dimensionality and extract key features
4. **Modelling** — Built a classification model using the reduced feature set
5. **Evaluation** — Measured performance using ROC-AUC score (0.8592)

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (PCA, Classifiers)

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/mdsajid4626/NBA-Game-Outcome-Prediction
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook nba_prediction.ipynb
   ```

## 👤 Author

**Mohammed Sajid**  
[LinkedIn](www.linkedin.com/in/mohammmed-sajid-47b92131b) | [GitHub](https://github.com/mdsajid4626)
