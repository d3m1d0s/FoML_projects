# FoML Projects

Semester project for Fundamentals of Machine Learning (Jan Platoš) at VŠB-TUO, winter 2026/27.
Author: Demid Ostiakov (OST0059)

| Part | Topic | Dataset | Notebook | Status |
|---|---|---|---|---|
| 1 | Exploratory and cluster analysis | [Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers) | [bankchurners_eda_clustering.ipynb](project_1/bankchurners_eda_clustering.ipynb) | in progress |
| 2 | Classification | [Bank Account Fraud (NeurIPS 2022)](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022) | | next |

## Part 1: Credit Card Customers

An exploratory analysis of 10,127 credit card customers, followed by a segmentation by behaviour with k-means. Demographics and churn are left out of the clustering and used only to describe the result. The chosen solution has four clusters:

- Heavy users of a small limit
- Low users of a large limit
- High spenders with few products
- Customers with low and declining activity, 42% of whom closed their account, against 16% of all customers

All details are in the notebook, which can also be opened in [Google Colab](https://colab.research.google.com/github/d3m1d0s/FoML_projects/blob/main/project_1/bankchurners_eda_clustering.ipynb).

Tools: Python, pandas, NumPy, scikit-learn, Matplotlib and Seaborn.
