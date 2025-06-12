# Medical Data Visualizer

This Python project uses `pandas`, `matplotlib`, and `seaborn` to analyze medical data collected during routine examinations.

## Features

- Adds a calculated `overweight` column using BMI.
- Normalizes health indicators like cholesterol and glucose.
- Generates:
  - **Categorical Plot**: Distribution of lifestyle/health features split by cardiovascular disease presence.
  - **Heat Map**: Correlation between medical measurements and lifestyle factors.

## Files

- `medical_data_visualizer.py`: Core logic and plotting functions.
- `main.py`: Used to generate and save the plots.
- `medical_examination.csv`: Dataset of patient data.

## How to Run

1. Clone the repo
2. Install dependencies:

```bash
pip install pandas seaborn matplotlib

