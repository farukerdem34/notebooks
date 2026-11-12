# Notebooks

This directory aggregates Jupyter notebooks (originally from Google Colab) by topic. Each notebook has been cleaned: Python comment lines were removed, every code cell is preceded by a Markdown cell explaining its purpose, Turkish text was translated to English, and cell outputs were cleared.

## Structure

- [data-mining/](data-mining/) — Data mining course exercises (statistics, distances, Iris classification, SVM/MLP)
- [machine-learning/](machine-learning/) — General machine learning demos
- [misc/](misc/) — Miscellaneous data science notebooks

## Notebooks

### data-mining

- **DM-Exercise-1.ipynb** — Dataset Generation
  - Generates a random 5-feature dataset and explores descriptive statistics, centralization, transpose, matrix multiplication, covariance and inverse covariance, plus Euclidean, cosine, Manhattan and Mahalanobis distance computations with NumPy/SciPy.
  - Topics: data generation, descriptive statistics, centralization, transpose, matrix multiplication, covariance, inverse covariance, distance metrics

- **DM-Exercise-2.ipynb** — DM Exercise 2: Iris Classification with k-NN and Naive Bayes
  - Analyzes the Iris dataset using cross-validated k-nearest neighbors and Gaussian Naive Bayes classifiers. Compares k-NN accuracy across neighbor counts and fold sizes, then evaluates Naive Bayes with confusion matrices, ROC and precision-recall curves, plus decision boundary visualizations.
  - Topics: Iris dataset, k-NN, cross-validation, Gaussian Naive Bayes, model evaluation, decision boundaries

- **DM-Exercise-3.ipynb** — DM Exercise 3
  - Loads the Iris dataset and evaluates SVM (linear/rbf/poly kernels) and MLP classifiers using k-fold cross-validation, then visualizes their 2D decision boundaries.
  - Topics: Iris dataset, SVM, MLP, cross-validation, decision boundaries, scikit-learn

### machine-learning

- **ml-piknik.ipynb** — Machine Learning: Picnic Prediction (Decision Tree)
  - Trains a DecisionTreeClassifier (entropy criterion) on a picnic dataset to predict whether a picnic will happen from weather/wind features, then visualizes the tree.
  - Topics: pandas, scikit-learn, LabelEncoder, DecisionTreeClassifier, entropy, matplotlib, plot_tree, data preprocessing
  - Companion data: `ml-piknik.csv`

### misc

- **ai&social-media-impact.ipynb** — AI and Social Media Impact on Student Health: Regression Analysis
  - Uses a Kaggle student dataset to analyze the effect of AI and social media usage on mental and physical health scores via regression. Includes preprocessing, EDA, correlation analysis, one-hot encoding, train/test split, standardization, Linear Regression and Random Forest evaluation, sample profile predictions and visualizations.
  - Topics: artificial intelligence, social media, student health, regression, machine learning, data analysis

- **tweet-classification.ipynb** — Multi-Label Classification in Turkish Tweets
  - Multi-label classification of Turkish tweets into six categories using a Kaggle dataset. Texts are vectorized with TF-IDF and classified with a LinearSVC-based multi-output pipeline; includes metrics and visualizations.
  - Topics: Turkish tweet classification, multi-label classification, TF-IDF, LinearSVC, scikit-learn, data analysis, visualization
