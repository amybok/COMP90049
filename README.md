## Effect of feature selections on sentimental analysis of medical practitioners' reviews

This repository contains a Jupyter Notebook that demonstrates the effect of feature selection techniques on sentiment analysis models for medical practitioners' reviews. The project explores multiple models and evaluates their performance using various feature selection methods.

### Dataset 

The dataset used is based on medical reviews on RateMD and has been modified for the purpose of this report.

### Contents

The code in the notebook covers the following:

#### Zero R Baseline Model:

- Provides a benchmark for evaluating other models.

#### Feature Selection Methods

- Chi-Square

- Mutual Information (MI)

Both implemented using SelectKBest from scikit-learn.

- TF-IDF
- Word Embedding using SBERT

#### Models used for classification task

##### K-Nearest Neighbors (KNN)

- Evaluated with no feature selection, Chi-Squared, MI, TF-IDF, and Word Embedding.

##### Gaussian Naive Bayes (GNB)

- Evaluated with no feature selection, Chi-Squared, MI, TF-IDF, and Word Embedding.

##### Decision Tree

- Evaluated for its performance across various feature selection methods.

##### Logistic Regression

- Tested with no feature selection, Chi-Squared, MI, TF-IDF, and Word Embedding.

##### Model selected for Kaggle label prediction

- Selected best-performing model to predict sentiment labels on a Kaggle dataset.

#### Evaluation Metrics

Each model, combined with feature selection methods, is evaluated using:

 - Classification reports

 - Heatmaps for performance visualization

#### Results and discussion

The project provides insights into the performance of various models and feature selection methods, highlighting their impact on sentiment analysis accuracy and interpretability. Please see report for more information.

