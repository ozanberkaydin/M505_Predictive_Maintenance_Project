# M505 Predictive Maintenance Project

This repository contains my individual project for M505 Intro to AI and Machine Learning.

## Project Title

Predictive Maintenance: Machine Failure Prediction Using Machine Learning

## Files

- `M505_Predictive_Maintenance_IndustrialKaggle.ipynb` : original Jupyter Notebook
- `M505_Predictive_Maintenance_IndustrialKaggle.html` : exported HTML report
- `requirements.txt` : required Python libraries
- `data/predictive_maintenance_v3.csv` : dataset used in the project

## Dataset

The dataset used in this project is the Industrial Machine Predictive Maintenance dataset from Kaggle.

The dataset is included in the `data/` folder for reproducibility. The notebook loads it using a relative path:

```python
df = pd.read_csv("data/predictive_maintenance_v3.csv")
