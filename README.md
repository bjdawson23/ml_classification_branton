# ml_classification_branton
Midterm and Final Project: Classification Analysis

## Overview
This repository contains a comprehensive Jupyter notebook for performing machine learning classification analysis. The notebook includes data exploration, preprocessing, model training with multiple algorithms, evaluation, and visualization.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/bjdawson23/ml_classification_branton.git
cd ml_classification_branton
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `classification_analysis.ipynb` in your browser

## Notebook Contents

The `classification_analysis.ipynb` notebook includes:

1. **Setup and Imports** - Required libraries and configurations
2. **Data Loading** - Load and preview your dataset
3. **Exploratory Data Analysis** - Statistical summaries and visualizations
4. **Data Preprocessing** - Feature scaling and train-test split
5. **Model Training** - Train 7 different classification algorithms:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors
   - Naive Bayes
6. **Model Evaluation** - Compare models using accuracy, precision, recall, and F1-score
7. **Feature Importance** - Analyze feature contributions (for applicable models)
8. **Model Persistence** - Save the best model for deployment

## Usage

The notebook uses the Iris dataset as an example. To use your own data:

1. Replace the data loading section (Section 2) with your dataset
2. Adjust preprocessing steps as needed for your data
3. Run all cells to train and evaluate models
4. Review the results and select the best model for your use case

## Dependencies

All required packages are listed in `requirements.txt`:
- jupyter
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## License

This project is for educational purposes as part of a classification analysis project.
