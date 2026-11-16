# Lab 6: Decision Tree Classification

**Objective:** Train and visualize a Decision Tree on the Wine Quality dataset; study the effect of `max_depth` and splitting `criterion` (gini vs entropy). Target: `quality`.

## How to run
1. Place **winequality.zip (or winequality-red.csv)** in this folder (dataset not included).
2. `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. `jupyter notebook Lab6_Decision_Tree_Classification.ipynb` and run all cells.

## Conclusion
- Training accuracy rises to 1.0 with unlimited depth while test accuracy stays ~0.59-0.61 → overfitting.
- Best test accuracy: entropy, max_depth=10 (0.609). Gini and entropy perform similarly (weighted F1 ≈ 0.607).
- Results are from a single split, so small differences aren't conclusive.
