# Product Purchase Prediction

Machine learning model that predicts whether a user will purchase a product based on user and product features.

## Models Tested
- Logistic Regression
- Random Forest
- Gradient Boosting (final choice)

## Results
- Gradient Boosting outperformed Logistic Regression and Random Forest
- Evaluated using ROC-AUC and PR-AUC
- Model modularized into training (`fit.py`), prediction (`predict.py`), and reusable class (`push_model.py`)

## Project Structure
- `notebooks/` → `model_comparison.ipynb` shows model evaluation and comparison
- `src/` → Python scripts for training and inference
- `data/` → dataset 
- `archive/` → exploratory notebook, raw scripts not part of final analysis
- `requirements.txt` → Python dependencies

## Usage
1. Place dataset `feature_frame_20210304.csv` in `data/`
2. Train the model: `src/fit.py`
3. Make predictions: `src/predict.py`
