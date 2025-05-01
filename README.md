# Task 5: Heart Disease Prediction with Decision Trees & Random Forests

This Jupyter Notebook (`Task5.ipynb`) demonstrates how to use Decision Tree and Random Forest classifiers to predict heart disease.

## Goal

The main goal is to:
1.  Train a Decision Tree model.
2.  Train a Random Forest model.
3.  Compare their performance in predicting heart disease.
4.  Understand which features are most important for prediction.

## Dataset

*   Uses the `heart.csv` dataset, containing medical information about patients.
*   The 'target' column indicates if a patient has heart disease (1) or not (0).

## Steps in the Notebook

1.  **Load Libraries:** Imports necessary tools like pandas, matplotlib, seaborn, and scikit-learn.
2.  **Load & Clean Data:**
    *   Reads the `heart.csv` file.
    *   Checks basic information about the data.
    *   **Removes duplicate rows**.
3.  **Visualize Data:** Shows the balance of patients with and without heart disease and the correlations between features.
4.  **Prepare Data:** Splits the data into features (X) and the target (y), then divides it into training and testing sets.
5.  **Train Decision Tree:**
    *   Builds a Decision Tree model.
    *   Visualizes the tree structure.
    *   Checks its initial accuracy on the test data.
6.  **Optimize Decision Tree:** Uses cross-validation to find the best `max_depth` for the tree to prevent overfitting.
7.  **Train Random Forest:** Builds a Random Forest model (using the optimized depth).
8.  **Compare Models:** Evaluates and compares the accuracy of the optimized Decision Tree and the Random Forest on the test data.
9.  **Feature Importance:** Shows which medical attributes the models found most useful for prediction.
10. **Cross-Validation:** Uses cross-validation again to compare how well the final models generalize.

## How to Run

1.  Make sure you have Python and the libraries listed below installed.
2.  Download the `heart.csv` dataset and place it in the same folder as `Task5.ipynb`.
3.  Open and run `Task5.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab).

## Key Libraries Used

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn
