# Machine Learning Midterm Project

## About the Project

In this project, I worked with two datasets: Breast Cancer Wisconsin and Wine Classification. I compared different machine learning models and checked how feature scaling affected the results.

## Datasets

I used two datasets from scikit-learn:

- **Breast Cancer Wisconsin:** 569 samples, 30 features, 2 classes.
- **Wine Classification:** 178 samples, 13 features, 3 classes.

## What I Did

- Checked missing values, duplicates, and possible outliers.
- Created class distribution graphs, correlation heatmaps, and boxplots.
- Split the data into training, validation, and test sets.
- Compared original features with StandardScaler features.
- Trained Decision Tree, KNN, and Gaussian Naive Bayes models.
- Compared models using validation metrics.
- Evaluated the selected models on the test sets.
- Tested K-Means clustering with scaled and unscaled data.
- Saved the results in CSV files and figures.

## Main Results

| Dataset | Best Classifier | Test Accuracy | Macro F1 |
|---|---|---|---|
| Breast Cancer | Scaled KNN (k=7) | 0.974 | 0.971 |
| Wine | Scaled KNN (k=11) | 1.000 | 1.000 |

Feature scaling was especially useful for KNN and K-Means.

## Project Files

- `breast_cancer.ipynb` — Breast Cancer notebook
- `wine.ipynb` — Wine notebook
- `report.docx` — English project report
- `figures/` — Saved graphs
- `classifier_runs.csv`
- `classifier_summary.csv`
- `classifier_test.csv`
- `kmeans_runs.csv`
- `kmeans_summary.csv`
- `kmeans_test.csv`
- `requirements.txt` — Python package dependencies
- `AI_DISCLOSURE.md` — AI usage information

## How to Run

1. Install Python and the packages listed in `requirements.txt`.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Install the dependencies:

   `pip install -r requirements.txt`

4. Run all cells in `breast_cancer.ipynb`.
5. Run all cells in `wine.ipynb`.

The Wine notebook also creates the combined result CSV files.

## GitHub Repository

https://github.com/emrebeyaziit/machine-learning-midterm

## Video Presentation

https://youtu.be/4J05ROaqaso

## Conclusion

In this project, scaled KNN gave the best classification results for both datasets. Scaling also improved K-Means clustering results, especially for the Wine dataset.