# Machine Learning Midterm

In this assignment, I experimented with machine learning models using two different datasets: **Breast Cancer** and **Wine**. My objective was to compare the performance of various models and examine whether data scaling influences the results.

## What I did:

- Explored the datasets and generated visualizations.
- Split the data into training, validation, and test sets.
- Tested Decision Tree, KNN, and Gaussian Naive Bayes models.
- Compared model performance using both raw and scaled data.
- Performed clustering using K-Means.
- Saved the results into tables and CSV files.

## Files

- `breast_cancer.ipynb`: Procedures applied to the Breast Cancer dataset.
- `wine.ipynb`: Procedures applied to the Wine dataset, including combined results for both datasets.
- `figures/`: 18 visualizations generated during the study.
- `classifier_runs.csv`, `classifier_summary.csv`, `classifier_test.csv`: Classification results.
- `kmeans_runs.csv`, `kmeans_summary.csv`, `kmeans_test.csv`: K-Means clustering results.
- `report.docx`: Assignment report.
- `requirements.txt`: Required Python libraries.
- `AI_DISCLOSURE.md`: Disclosure regarding the use of artificial intelligence.

## How to run:

You must have Python and Jupyter installed on your computer. The files can also be opened using VS Code. First, install the necessary libraries in your terminal:

```bash
pip install -r requirements.txt
```

Then, open the notebooks in the following order and select **Run All**:

1. `breast_cancer.ipynb`
2. `wine.ipynb`

**Important:** Both notebooks must be in the same folder. Since the results from both datasets are combined in the final section of the Wine notebook, the Breast Cancer notebook must be executed first.

## Summary of results

For the Breast Cancer dataset, the best result was achieved using scaled **KNN (k=7)**, with a test F1 score of approximately **0.971**.

For the Wine dataset, the best result was achieved using scaled **KNN (k=11)**, with a test F1 score of **1.000**.

In this study, I observed that feature scaling is particularly important for KNN and K-Means. More detailed results can be found in the notebook files and the report.