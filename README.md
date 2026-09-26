# SmartChurn

A bank customer churn modeling exercise comparing classification models and the tradeoff between finding customers who leave and avoiding false alarms.

![Churn distribution](img_1.png)

## Workflow

Explore churn patterns, preprocess customer features, compare logistic regression, random forest, SVM, and KNN, and evaluate class imbalance with SMOTE. The [notebook](Lab10_Osualaaham.ipynb) contains the full analysis and results.

| Exploration | Model evaluation |
|---|---|
| ![Churn by customer features](img_2.png) | ![Model evaluation figure](img_3.png) |

**To reproduce:** Open the notebook in Colab with the source churn CSV. The CSV is not included in this repository; the exported script `lab10_osualaaham.py` uses a Colab-specific `/content/Churn (3).csv` path. Update that path for your environment.

**Limitations:** Model scores in this exercise should be checked with a separate validation/test workflow before treating them as estimates for a real bank.
