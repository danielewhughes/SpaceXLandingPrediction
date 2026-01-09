# SpaceX Falcon 9 Landing Prediction

> This repository begins with **data collection** from the official SpaceX API and is designed to expand into **EDA**, **feature engineering**, and **machine learning models** for landing success prediction.Predicting whether the **Falcon 9 first stage** will land successfully using publicly available SpaceX launch data. The motivation: successful landings enable reusability and major cost savings, making SpaceX launches significantly more competitive versus traditional providers.

---

## Goals

1. **Collect** structured launch data (flight details, payload mass, orbit, launch site, outcomes) from the SpaceX API.  
2. **Explore** patterns that influence landing success (e.g., payload, orbit, launch site, flight number).  
3. **Build** machine learning models to predict landing outcomes (e.g., Logistic Regression, SVM, Decision Trees, KNN).  
4. **Evaluate** model performance and interpret feature importance.

## Tech Stack

- **Python** (Pandas, NumPy, scikit-learn, Matplotlib/Seaborn) for data work and modeling.  
- **Jupyter Notebook** for exploratory analysis and reproducible workflows.  
- **SpaceX API** for source data.  

## Getting Started

### 1) Clone the Repository
```bash
git clone https://github.com/danielewhughes/SpaceXLandingPrediction.git
cd SpaceXLandingPrediction
```

### 2) Create and Activate a Virtual Environment
```bash
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows
.venv\Scripts\activate

```

### 3) Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests jupyter
```
