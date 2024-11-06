## Logistic Regression: Rock vs. Mine Prediction

## Overview
This project implements a logistic regression model to classify sonar signals as either rocks or mines. Using a dataset of sonar readings, the model aims to distinguish between signals reflected off metal cylinders (mines) and rock surfaces, a common task in underwater object detection.

## Dataset
- **Source**: The dataset contains sonar readings with features representing sound wave intensities.
- **Target**: Binary classification indicating whether the object is a **rock** or **mine**.

## Project Structure
- **Data Preprocessing**: Includes normalization and handling missing values.
- **Model Training**: Logistic regression model trained to classify sonar signals.
- **Evaluation**: Model evaluated with metrics like accuracy, precision, and recall.

## Requirements
- Python libraries: `pandas`, `scikit-learn`, `numpy`, and `matplotlib`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aifedayo/Logistic-Regression-Problem-Rock-vs-Mine-Prediction.git
   ```
2. **Run the Notebook**:
   Open and run the Jupyter notebook to see data analysis, model training, and evaluation steps.

## Results
- The model achieves an accuracy of 82% on the test data, demonstrating its effectiveness in distinguishing between rocks and mines.
