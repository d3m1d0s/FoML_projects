# FoML Projects

Semester projects for Fundamentals of Machine Learning (Jan Platoš) at VŠB-TUO, winter 2026/27.
Author: Demid Ostiakov (OST0059)

| Part | Topic | Dataset | Notebook | Status |
|---|---|---|---|---|
| 1 | Exploratory and cluster analysis | [Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers) | [bankchurners_eda_clustering.ipynb](project_1/bankchurners_eda_clustering.ipynb) | done |
| 2 | Classification | [Bank Account Fraud (NeurIPS 2022)](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022) | | next |

## Part 1: Credit Card Customers

An exploratory analysis of 10,127 credit card customers, followed by a segmentation by behaviour with k-means and hierarchical clustering (Ward linkage). Demographics and churn are left out of the clustering and used only to describe the result. The main segmentation, from k-means, has four clusters:

- Heavy users of a small limit
- Low users of a large limit
- High spenders with few products
- Customers with low and declining activity, 42% of whom closed their account, against 16% of all customers

Hierarchical clustering confirms the high spenders and the low-activity customers, and splitting its clusters into their sub-groups shows where the churn is concentrated. Among the top spenders, for example, a group of 213 customers left almost entirely (86%), while the 667 most active ones hardly left at all (2%).

All details are in the notebook, which can also be opened in [Google Colab](https://colab.research.google.com/github/d3m1d0s/FoML_projects/blob/main/project_1/bankchurners_eda_clustering.ipynb).

Tools: Python, pandas, NumPy, SciPy, scikit-learn, Matplotlib and Seaborn.
