# Dax Virani - Iris Analysis

Objective
- Demonstrate a compact EDA and modeling workflow on the Iris dataset: visualization, dimensionality reduction (PCA), and a simple classifier baseline.

Steps performed
- Load dataset (sklearn), inspect distributions and pairwise relationships
- Preprocess (scaling), run PCA, visualize component space
- Train and evaluate a basic classifier (e.g., Logistic Regression)

Tools / Libraries
- pandas, numpy, scikit-learn, seaborn, matplotlib

Outcome (brief)
- Notebook provides visual insights into class separability and a reproducible baseline model for comparison.

How to run

```bash
pip install -r requirements.txt
jupyter lab
jupyter nbconvert --to notebook --execute "Dax Virani - iris.ipynb" --inplace
```

Notes
- Uses sklearn's built-in Iris loader; no external files required.
- Author: Dax Virani
