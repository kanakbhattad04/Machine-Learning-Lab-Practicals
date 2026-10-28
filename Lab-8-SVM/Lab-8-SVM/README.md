# Lab 8: Support Vector Machine (SVM) Classification

## Aim
To implement the Support Vector Machine (SVM) algorithm for classification using Python and Scikit-learn.

## Dataset
**AI4I 2020 Predictive Maintenance Dataset**

The dataset contains machine operating parameters and a machine failure label.

### Features Used
- Type
- Air temperature [K]
- Process temperature [K]
- Rotational speed [rpm]
- Torque [Nm]
- Tool wear [min]

**Target variable:** `Machine failure`

## Algorithms Implemented
1. SVM with Linear Kernel
2. SVM with RBF Kernel
3. Hyperparameter-tuned SVM using GridSearchCV

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. Load and inspect the dataset.
2. Perform exploratory data analysis (EDA).
3. Check for missing values and duplicate records.
4. Visualize the target distribution and feature relationships.
5. Encode categorical features and scale numerical features.
6. Split the dataset into training and testing sets.
7. Train Linear and RBF kernel SVM classifiers.
8. Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
9. Perform hyperparameter tuning using GridSearchCV with 5-fold cross-validation.
10. Compare the performance of the trained models.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Best Model
The best hyperparameters identified through GridSearchCV were:

- **Kernel:** RBF
- **C:** 100
- **Gamma:** 0.1

The tuned model achieved the following test results:

| Metric | Score |
|---|---:|
| Accuracy | 97.95% |
| Precision | 73.68% |
| Recall | 61.76% |
| F1-score | 67.20% |

*Note: These results are based on the current notebook run and may vary if the data or experimental settings change.*

## Repository Contents
- `Support-Vector-Machine.ipynb` — Jupyter Notebook containing the implementation, visualizations
