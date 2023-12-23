# Breast Cancer Classification Project

## Overview
This project utilizes scikit-learn to train a Gaussian Naive Bayes classifier for breast cancer classification. It includes data loading, exploration, visualization, model training, and evaluation. Additionally, it demonstrates the use of permutation importance for feature analysis.

## Files
- `cancer_cell_classifier.ipynb`: Python script containing the main code for the project.
- `README.md`: Documentation file explaining the project.

## Getting Started
1. Install the required dependencies:
   ```bash
   pip install scikit-learn pandas seaborn matplotlib
   ```
2. Run the `cancer_cell_classifier.ipynb` script

## Project Structure

**Data Exploration and Visualization:** Utilizes Seaborn for pair plots and bar plots.
**Missing Values Handling:** Removes rows with missing values from the dataset.
**Model Training:** Uses scikit-learn's Gaussian Naive Bayes classifier.
**Model Evaluation Metrics:** Calculates accuracy, precision, recall, F1 score, and confusion matrix.
**Permutation Importance:** Evaluates feature importance using permutation importance.

## Feature Selection

The script can be easily adapted to perform model training and evaluation with specific features. For example, it can be modified to use only the "area error" and "worst area" features.

```python
selected_features = ['area error', 'worst area']
```
## Results

The script outputs model evaluation metrics and displays visualizations, including pair plots, bar plots of permutation importances, and confusion matrices.

## Dependencies

scikit-learn
pandas
seaborn
matplotlib
