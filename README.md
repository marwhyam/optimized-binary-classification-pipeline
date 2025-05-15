# optimized-binary-classification-pipeline
An optimized machine learning pipeline for binary classification using serial, parallel, and GPU execution modes, benchmarked with Random Forest, XGBoost, LightGBM, and CatBoost.

---

### 2. `optimized-binary-classification-pipeline`

```markdown
# Optimized Machine Learning Pipeline for Binary Classification

This project demonstrates how to build and optimize a machine learning pipeline using serial, parallel, and GPU-based execution. It compares model performance and resource usage under different configurations.

## Features

- Data cleaning, encoding, and normalization
- Parallel processing using Dask
- GPU acceleration using XGBoost, LightGBM, CatBoost
- Accuracy, training time, and resource usage benchmarking

## Technologies Used

- Python
- Dask
- scikit-learn
- XGBoost, LightGBM, CatBoost
- Pandas, NumPy

## Models Implemented

- Random Forest
- Gradient Boosting
- XGBoost (CPU & GPU)
- LightGBM (GPU)
- CatBoost (GPU)

## Performance

- Best Accuracy: CatBoost (0.5995)
- Best Speedup: XGBoost (GPU) – 10.9x
