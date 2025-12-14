# Dropout Classification

## Overview
This project builds a machine learning pipeline to predict student dropout using demographic and behavioral features.  
The task is formulated as a binary classification problem with a focus on identifying high-risk students.

## Repository Structure
.
├── data/       # Raw and/or processed datasets
├── figures/    # Generated plots and visualizations
├── results/    # Model outputs, predictions, saved models
├── report/     # Final report (PDF)
├── src/        # Source code and notebooks
├── README.md
├── LICENSE
└── .gitignore

## Environment
- Python 3.x  
- Core libraries: pandas, numpy, scikit-learn, matplotlib, seaborn,shap

(Exact package versions can be added via an environment.yml file if needed.)

## Reproducibility
1. Clone the repository
2. Install required dependencies
3. Run the notebook(s) in `src/` to reproduce results

## Data
The dataset is not included in this repository due to size or access restrictions.  
The raw data can be accessed via Google Drive:
[course-provided data source](https://drive.google.com/drive/folders/1b8WngZk8k7ZFcq4xd9xD2ut_LeooPfeW?usp=drive_link) 
for download instructions.
encoded-data (used for training and test) is in the data file.

## Results
Model performance is evaluated using appropriate classification metrics.  
Key results and figures are stored in the `results/` and `figures/` directories.

## Report
The final project report is available in the `report/` directory.

